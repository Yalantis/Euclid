# Euclid

This project is an implementation of the User Profile Interface Animation. Made in [Yalantis] (https://yalantis.com/?utm_source=github)

Check this [project on Dribbble] (https://dribbble.com/shots/1744157-User-Profile-Interface-Animation)

<img src="https://d13yacurqjgara.cloudfront.net/users/125056/screenshots/1744157/99miles-userprofile-animation_1-1-3.gif" alt="alt text" style="width:200;height:200">

#Note

depends on <a href="https://github.com/ozodrukh">Ozodrukh's</a> animation util for CircularReveal animation

#Usage

At the moment, it's just an example of implementation of above interface in your android project.
On later stages we are planning to create highly customisable library for good-looking interface.

But, if you want to use it in your project, you need to:

1. Include the library as local library project.
2. add this to your projects build.gradle file:<br>
   ```groovy
   	repositories {
   	    maven {
   	        url "https://jitpack.io"
   	    }
   	}

   ```
   <br> for CircularReveal module

3. Extend you activity from EuclidActivity
4. Implement getAdapter() method, so you return your own data.

*For a working implementation, Have a look at the Sample Project - sample*

#Customization

You can override several methods to adjust animation durations or radius of circle that
reveals the avatar.

#Compatibility
  
  * Android JELLYBEAN 4.1+
  
# Changelog

### Version: 1.0

  * Pilot version

#### Let us know!

We’d be really happy if you sent us links to your projects where you use our component. Just send an email to github@yalantis.com And do let us know if you have any questions or suggestion regarding the animation. 

P.S. We’re going to publish more awesomeness wrapped in code and a tutorial on how to make UI for Android (iOS) better than better. Stay tuned!
  
## License

    Copyright 2017, Yalantis

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.

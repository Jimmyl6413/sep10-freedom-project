# Entry 4: Choosing a Tool for the Freedom Project
##### February 12, 2024
### Update
After completing the research on softwares and hardwares on traveling, I began looking for tools I can use to help me with my Freedom Project. I am now on step 4 of the project, planning. I will be planning and choosing some tools for this project.

### Content
In this blog entry I will be going over what tools I chose and how I tinkered with the tools I choosed. I will be able to explain how to use the tool and what it will be useful for in this project.

##  [Animated.css](https://animate.style/)
**Animated.css** has a variety of animations and features that we can use on different elements and codes. I was able to test out Animated.css in [this practice file](..//tool/animated-css.html). I looked through the tutorials and the basics of using Animated.css. I added animated.css directly to my practice html file using the CDN and started testing all the animations like bounce, backInDown, and more. I tested it out with divs and classes and then came across keyframes which I had a hard time understanding. I used w3schools to learn how to use keyframes and tried it. I used animated.css to animate different elements using divs and key frames.
```css
 .my-element {
  display: inline-block;
  margin: 0 0.5rem;

  animation: fadeInUp; /* referring directly to the animation's @keyframe declaration */
  animation-duration: 4s; /* don't forget to set a duration! */
}
```
This class allow an element to have a specific animation with a inline black and animation duration.
```html
 <h2 class="animate__animated animate__rubberBand animate__delay-3s" id="test2"> Welcome to my practice html file for animated.css!</h2>
```
By using this class I was able to make my h1 have an animation called rubberBand with a delay of three seconds.


## [A-Frame](https://aframe.io/)
#### Context
A-frame is an open source web framework for building 3d animations and allowing people to make things more realistic. We are able to create reality expierences on a-frame by using html and css. A-frame can be used on all platforms and devices.
### How I tinkered with A-frame
I started by making a [practice html file](../tool/a-frame.html) for A-frame. I went to the **installation** page on A-frame and installed A-frame by using the CDN:```<script src="https://aframe.io/releases/1.5.0/aframe.min.js"></script>```.
I tried:
```
 <a-scene>
      <a-assets>
        <img id="sky" src="sky.png">
      </a-assets>
      <a-sky src="#sky"></a-sky>
      <a-sky color="#6EBDC4"></a-sky>

    <!-- Box -->
    <a-box color= "black" width="8" height="4.5" depth="0.2" position="0 3 -7" >
      <!-- Circle-->
      <a-circle color="blue" position="2 0 0.11" side="double">

      </a-circle>
    </a-box>
  </a-scene>
```
This allowed me to create a box and circle with relative positioning. I was able to have a light blue sky background. I also learned that we can import models and images by using ```<a-assets></a-assets>``` by having the model downloaded and saved and using a ```<img id="" scr=""``` which I haven't tried yet.

[Click Here to Learn More about A-frame](https://www.youtube.com/watch?v=ktjMCanKNLk&list=PL8MkBHej75fJD-HveDzm4xKrciC5VfYuV)


## Engineering Design Process (EDP)
I am working on step 4 of the Engineering Design Process where I will be learning how to use tools to help me with my Freedom Project. I will be using these tools to **create a prototype** for my Freedom project in step five.
## Skills

### Self-learning
Since we all chose different tools we had to learn how to use these tools before we begin making a prototype of our project. My tools were A-frame and Animated.css. I learned how to use my tools through various testing and watching videos. After testing different codes over and over again and using guides on A-frame I was able to create a 3D model of shapes and backgrounds. I also learned to animate different elements to appear differently using Animated.css.

### How to Google
When I first started testing out my tools I didn't know what some of the codes did or how to use them. For example, I didn't know what ```@keyframe``` was used for so I searched up "Keyframe css". This brought me to [w3schools](https://www.w3schools.com/cssref/css3_pr_animation-keyframes.php) where I learned that keyframes are used to specify the animation code. By searching up various codes that I never saw or learned before I was able to undertsand how to use them. I was also able to test them out in w3schools. Learning how to google the right information you are looking for can save you a lot of time.



### Next steps
I will be using the tools that I learned to create a prototype of my freedom project. This is gonna be a blast!







[Previous](entry03.md) | [Next](entry05.md)

[Home](../README.md)

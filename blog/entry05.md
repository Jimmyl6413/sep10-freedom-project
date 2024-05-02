# Entry 5: Tinkering with Animated.css and A-frame
##### April 8, 2024

### Update
After choosing my tools that I will be using for my Freedom Project, I began tinkering with my tools over the course of 5 weeks.
### Context
 In this blog I will be going through a series of things that I did to tinker with [Animated.css](https://animate.style/) and [a-frame](https://aframe.io/).

 ## Process of learning Animated.css
 I started by importing animated.css through CDN ```<link rel="stylesheet"  href="https://cdnjs.cloudflare.com/ajax/libs/animate.css/4.1.1/animate.min.css"
/>``` to my LOYO practice on bootstrap components. I decided to practice animated.css in my LOYO practice so that I can tinker and learn on my own about bootstrap components. It's a win, win. I was able to learn more about delays, durations, repeats, and more animated.css etc. I used delays to delay the time that the text will fade in, in each section.
```html

  <h1 class="animate__animated animate__tada animate__delay-2s" id="test2"> Hello!</h1>
  <h2 class="animate__animated animate__rubberBand animate__delay-3s" id="test2"> Welcome to my practice html file for animated.css!</h2>
  <p class="animate__animated animate__fadeIn animate__slower">

```
I implemented animations to my text, paragraphs, titles, navbar, and [more!](https://github.com/hstatsep-students/bootstrap-components-practice-Jimmyl6413/blob/main/index.html).

I was still confused about some parts of animated.css but I was able get a better understanding of animated.css by [watching](https://www.youtube.com/watch?v=VzbBcVRquYA) a video. I usually undertstand something better when it's explained to me so this was very helpful.

### Takeaways
I was able to learn different components of bootstrap and then using the left over time to style what I made even more by using animated.css. By doing so, I was able to make my website more interesting and catch the users attentions. I countinued on practicing animated.css

## Process of learning A-frame
I starting by looking through the different documents of a-frame and tried to make an environment or multiple environments that will suit in my Freedom Project.I learned how to make different environments using a-frame by watching [this](https://www.youtube.com/watch?v=K_1RdCVuu98), which I was able to understand very well.

```html
<head>
 <script src="https://unpkg.com/aframe-environment-component/dist/aframe-environment-component.min.js"></script>

</head>
<a-entity environment="preset: forest; dressingAmount: 500"></a-entity>
<a-scene>

```
I also learned that we can view the a-frame inspecter by clicking Control + alt + I on the keyboard. By using control + alt + I, I was able to change my environment according to my likings. It was very helpful and saved me a lot of time. As I as exploring the different environments that I can use, I also found out how to use images as a background for a-frame.

```html
<a-sky src="https://t3.ftcdn.net/jpg/00/81/26/82/360_F_81268225_eVHynMTlVQf3wVdYOoUEz8d8KolhVZm0.jpg"></a-sky>
```
It's the same thing as adding an environment but instead we need the ```src``` and the image link.


## Skills

### LOYO - Learn On Your Own
Over the course of 5 week we had to learn our own tool that we picked for the Freedom Project. For me, I picked animated.css and a-frame which were 2 great tools when it came to making basic models and designing websites. I tinkered with my tools until I got comfortable with my tool. Codes that i didn't understand, I would go on youtube and look for explanations or solutions. Using youtube helped a lot as there were a variety of videos to choose from that had clear explanation

### Use Youtube Efficiently
When I was stuck on some code in animated.css or a-frame that I didn't undertsand, I would go on Youtube and search for solutions. Youtube is a great place to look for solutions because there is actually somebody explaining and teaching the topic you want to know or don't understand. There is a variety of videos to choose from and of course I don't have time to watch every single video that pops up. I would just skim through the titles of the video and look for one that is similar to what I searched.







[Previous](entry04.md) | [Next](entry06.md)

[Home](../README.md)

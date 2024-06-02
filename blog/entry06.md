# Entry 6: Making the MVP of my FP
##### May 1, 2024
### Update
As we approach the end of the FP we started coding (Finally) our MVP FP which means the bare minimum FP website that we can code for now.

### Content
In this blog I will be going through different challenges and success while coding my MVP FP. It was full of challenges but also fun because me and my partner Joe coded from scratch and didn't use any bootstrap templates. The hardest parts of this website was making it responsive and choosing a suitable color scheme that will make our website unique and pop out!

## Process of Coding the MVP of my FP
We have been learning how to code for months now and it's finally the time to code our own website on the topic we chose in the beginning of the school year. For this FP I have a partner, Joe who worked on the MVP FP with me. We didn't jump straight into coding but instead, we made 2 which allowed us to make a layout of the website and what it would look like on mobile and larger screens. Below are the wireframes that me and my partner made:

[Wireframe-1](../prep/wireframe1.png)
[Wireframe-2](../prep/wireframe2.png)
[Wireframe-3](../prep/wireframe3.png)
[Wireframe-4](../prep/wireframe4.png)
[Wireframe-5](../prep/wireframe5.png)
[Wireframe-6](../prep/wireframe6.png)
[Wireframe-7](../prep/wireframe7.png)
[Wireframe-8](../prep/wireframe8.png)

After we finished the basic layouts of our website we began coding and quickly came across our first problem: communication and teamwork. It was very hard for 2 people to work together as merge conflicts can get very annoying. For instance, when I git pulled Joe's changes it deleted half of my work that I had finished and I had to redo everything all over again. We were using cards for all of our information as we figured that it's the best choice for the topic that we chose.

```html
<!-- SIMO Solis Lite Portable Mobile Hotspot -->
      <div class="col-md-6" style="padding-top:40px;">
        <div class="card white">
          <img src="img/Charger.jpg" class="card-img-top" alt="Try again later!">
          <div class="card-body">
            <h5 class="card-title ptserif">SIMO Solis Lite Portable Mobile Hotspot</h5>
            <p class="card-text ptserif"><strong>Description:</strong>  The SIMO Solis Lite Portable Mobile Hotspot is a favorite regarding the travel industry as it serves the purpose of entertainment. These are some of the most important features the invention has: </p>
            <ul>
              <li class="ptserif">Provides reliable WiFi throughout 135+ countries
              </li>
              <li class="ptserif">Guarantees 16+ hours of WiFi without charging
              </li>
              <li class="ptserif">
                Is small in size, making suitability for everyday carry
              </li>
              <li class="ptserif">Can connect ten smartphones at a time; it comes in handy when traveling in a large group
              </li>
              <li class="ptserif">Is able to function without the use of SIM cards
              </li>
              <li class="ptserif">Is sustained by offered plans that are flexible, affordable, and vaulable
              </li>
            </ul>
            <a href="https://www.amazon.com/SIMO-Portable-International-Multi-Carrier-Connected/dp/B08YKB6VMN" target="blank" class="btn btn-primary">Check it out!</a>
          </div>
        </div>
      </div>
    </div>
  </div>
</div>
</section>

```

We also used columns and rows to make the cards organized and next to eachother. After putting all the information into our website we began making it responsive to medium and small screens by using media queries like shown below:

```css

@media (min-width:2500px){
    iframe {
        padding-top:35px;
        height:500px;
        width:1900px;
        padding-left:660px;
    }
}
@media (min-width:1901px) and (max-width:2499px){
    iframe {
        padding-top:35px;
        height:500px;
        width:1500px;
        padding-left:540px;
    }
}
@media (min-width:1550px) and (max-width:1900px){
    .background {
        background-image: url(img/sunset.jpg);
        background-repeat: no-repeat;
        background-size: cover;
        height:1700px;
        width:auto;
}
    .title {
        font-size:110px; text-align:center; color:white; padding-top:280px;
    }

    iframe {
        padding-top:35px;
        height:500px;
        width:1440px;
        padding-left:160px;
    }
}

@media (min-width:1517px) and (max-width:1549px){
    iframe {
        padding-top:35px;
        height:500px;
        width:1400px;
        padding-left:120px;
    }

    .background {
        background-image: url(img/sunset.jpg);
        background-repeat: no-repeat;
        background-size: cover;
        height:950px;
        width:auto;
}
}

@media (min-width:1400px) and (max-width:1516px){
    iframe {
        padding-top:35px;
        height:500px;
        width:1350px;
        padding-left:90px;
    }

    .background {
        background-image: url(img/sunset.jpg);
        background-repeat: no-repeat;
        background-size: cover;
        height:1000px;
        width:auto;
}
    .title {
        font-size:110px;
        text-align:center;
        color:white;
        padding-top:300px;

}
}

@media (min-width:1200px) and (max-width:1399px){
    .background {
        background-image: url(img/sunset.jpg);
        background-repeat: no-repeat;
        background-size: cover;
        height:950px;
        width:auto;
    }

    iframe {
        padding-top:35px;
        height:500px;
        width:1100px;
        padding-left:100px;
    }
}


@media (min-width:901px) and (max-width:1199px){
    iframe {
        padding-top:35px;
        height:500px;
        width:910px;
        padding-left:120px;
    }

    .background {
        background-image: url(img/sunset.jpg);
        background-repeat: no-repeat;
        background-size: cover;
        height:900px;
        width:auto;
}
}

@media (max-width:900px){
        iframe{
            padding-top:35px;
            padding-left:125px;
            width:640px;
            height:500px;
        }
}

@media (max-width:676px) {

    .height {
        height:600px;
    }

    .height2 {
        height:600px;
    }

    iframe {
        padding-left:35px;
        padding-top:20px;
        height:550px;
        width:500px;
    }

    .background {
        background-image: url(img/sunset.jpg);
        background-repeat: no-repeat;
        background-size: cover;
        height:580px;
        width:auto;

}
}

@media (max-width:376px){
    iframe{
        padding-left:35px;
        padding-left:20px;
        height:350px;
        width:350px;
    }
}

```

#### One of the Challenges

Making the whole website responsive was the most challenging and time consuming (as ou can tell from the code above) part as we need to figure out different break points and css to make it smoot like butter. We also used columns to make it responsive.

```bash
class="col-md-6 col-lg-6 col-sm-12"

```

This was extremely helpful and saved us plenty of time for better disgns. It was very challenging but we tried things out and eventually got the website running smoothly.



## Engineering Design Process (EDP)
We are now on **step 5** of the _engineering design process_ where we create the prototype of the website and approach **step 6**, making it even better!

## Skills

### Contribution
Contributing to the FP was very important because I was working with a partner and we both had our own parts to code. No body was gonna do all the work and let you benefit from their work. For me, I was in charge of all the design, layout, and navbar of the website while my partner, Joe was in charge of responsivness of the website and information to make sure that our website has what it needs and everything matches the topic we are trying to express. Contribution is crucial when it comes to working as a team because if you are lacking or your team is lacking then it would just be a total disaster as work pile up.

### Creativity
This is the first time that we are offically making a website with what we learned so far and creativity was very important. I thought of different disgns and layouts for my FP website that will make it look unique and pop. Creativity is very important when it comes to design etc as we want to be creative with the color schemes and layout.


## Take Aways
* Teamwork
* Communication
* Time management
* Creativity
* Design
* There is more to come as we approach **Steps 6, 7, and 8** of the FP!

## Next Steps
We will start to make our website go beyond MVP and make it even better than before by spending more time and effort on it.

















[Previous](entry05.md) | [Next](entry07.md)

[Home](../README.md)

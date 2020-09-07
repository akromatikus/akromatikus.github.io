---
 layout: basic_page
---




{:refdef: style="text-align:center;" }

<figure>
  <figcaption>A quick display of the controls of a simple 3-D printed paddle boat which I designed using Autocad.</figcaption>
  <div style="text-align: center;margin-bottom: 30px"><iframe class="video" width="789" height="444"       src="https://www.youtube.com/embed/HEWLz2Ls8z0" 
  frameborder="10px" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe></div>

  <figcaption>The paddle boat in action. A simple bouyancy calculation ensured that the boat would only vertically displace about one inch of water. Also, I calculated drag forces on the paddles and boat which led to a theoretical speed of about a quarter meter per second, and this ended up being less than ten percent off from the actual speed.</figcaption>
    <div style="text-align: center;margin-bottom: 30px"><iframe class="video" width="789" height="444" src="https://www.youtube.com/embed/1vOjTd4pV0Q" 
    frameborder="10px" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe></div>

  <figcaption>The heart of the boat, containing the stepper circuits, arduino, tranciever, and battery. One of the most interesting realizations I had while making it was the design of the rubber band gears. The bands kept sliding off, so I decided to make the gears concave, only for the problem to be made worse! Consequently, I decided to make them convex instead, and this worked! Some research confirmed that this is indeed a legitimate approach to the problem that has been known for centuries. Finding and understanding unintuitive solutions to a problem is one of science's most endearing qualities.</figcaption>
  <img src="/Images/reciever.JPG" class="round" />
  
  <figcaption>The controller for the boat. Making the physical controls functional was quite fun. I tried to make everything as compact as possible for this project. Was that necessary? No, but it was a fun challenge nonetheless.</figcaption>
  <img src="/Images/controller.JPG" class="round" />

  <figcaption>Some drum pads I designed, with piezos underneath. I am able to get some nice, realistic drum sounds out of these, especially in regards to cymbals and hi-hats. Since the proximity of an excitation to a piezo changes the amplitude, three piezos are used on the edges of each pad so that any tapping in the middle gives consistent results. Each pad has different thicknesses and densities to shape the sound in different ways.  </figcaption>
  <img src="/Images/Piezo_Drums.jpg" class="round" />
  
  <figcaption>A foot pedal I designed using a load cell. The pressure signal is sent to a pc using an arduino and serial, and that signal is used to control any parameters I want inside a DAW (digital audio workstation). Its primary purpose is as a hi-hat foot pedal. Originally, a piezo underneath would be triggered by tapping the pedal against the base. This signal would then be used to create a "foot" tap sound. However, it proved unreliable, so I opted to used the position of the pedal to trigger an impulse instead, with the velocity of the pedal determining the amplitude of the impulse.</figcaption>
  <img src="/Images/fp_angled.JPG" class="round" />

  <figcaption>A quick demonstration, used as a wah wah pedal. A few modifications were made to make the pedal sturdier, including the added spring.</figcaption>
    <div style="text-align: center;margin-bottom: 30px"><iframe class="video" width="789" height="444" src="https://www.youtube.com/embed/4us0tjXX_cY" 
    frameborder="10px" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe></div>

  <figcaption>A hi-hat demonstration combining the piezo pads and the foot pedal, along with some software voodoo in max/msp (A work in progress). The piezo pads send audio to a pc, which converts the audio into pulses which are then convolved with various drum samples. The pedal fades between these samples, and also chokes the open hat samples like a real hi-hat would.</figcaption>
    <div style="text-align: center;margin-bottom: 30px"><iframe class="video" width="789" height="444" src="https://www.youtube.com/embed/ZcGDD9cZw5U" 
    frameborder="10px" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe></div>
  
  <figcaption>A view from the side.</figcaption>
  <img src="/Images/fp_side.JPG" class="round" />
  
  <figcaption>A top view.</figcaption>
  <img src="/Images/fp_top.JPG" class="round" />

  <figcaption>A side project I've been working on. But I've recently put it on pause in favor of more important projects, like my solar powered, bluetooth enabled pet rock, and my underwater hairdryer.  </figcaption>
  <img src="/Images/hadron.jpg" class="round" />
  
</figure>
{: refdef}






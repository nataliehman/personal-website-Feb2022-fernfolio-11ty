---
title: Prototyping smart device experiences
metaDescription: A project on prototyping smart devices using ProtoPie and LittleBits. This was showcased in Adobe Max 2018, UX Playground and Digital Age Summit.
summary: ADOBE
client: Adobe
cover: smart-device-cover.png
tags:
  - Research
  - Data analysis
  - Prototyping
  - Testing
  - Animation
---

### Personal note

This was my first design project after finishing the [UX Playground course](https://www.meetup.com/ux-playground-the-user-experience-meetup/events/241328389/). I mainly focused on developing a smart device prototype, which utilised my knowledge and experience with technology. Within a few months, I learned to use [ProtoPie](https://www.ProtoPie.io/) and [LittleBits](https://sphero.com/collections/all/family_LittleBits) to create complex interactive prototypes without coding. It was a fun learning experience and useful to find out what prototyping tools are available for designing smart device experiences without any code. I also had the opportunity to explore animation and create interactions for the prototypes.

### Overview

With more smart devices entering the market, managing our daily activities and acquiring information has become increasingly convenient. These smart capabilities have created an extra layer of complexity, which can be challenging for designers to develop strategies and solutions. Designers may need to explore areas such as electronics, to better understand how the interactions between humans, hardware and software can affect the overall user experience of a smart device.

### Creating a smart device prototype

Our goal was to showcase the features of Adobe XD by developing a smart device prototype and presenting it at [Adobe Max 2018](https://2018.max.adobe.com/sessions/max-online/#24803). It was also showcased at [UX Playground in WeWork, London](https://www.meetup.com/UX-Playground-The-User-Experience-Meetup-for-Londoners/events/254440446/) and [Digital Age Tech Summit, Istanbul](https://digitalagesummit.com/en/schedule/the-smartest-kid-on-the-block-designing-and-prototyping-smart-device-experiences/).

The following are the key areas we focused on:

- How can we design and prototype user experiences for smart devices?
- What tools are currently available to prototype smart devices?
- How can we utilise these tools to develop a simple framework for prototyping smart devices?

### Team

Natalie Man, Front-end Developer, Smartology
Chakib Labidi, UX Consultant and UX Playground founder
Stephanie Howard, Digital Designer, Nelson Bostock

### Resources and tools for developing smart device experiences

Our research covered topics such as UI kits, interfaces, and prototyping. My task was to develop the prototype, so my research covered key points such as:

- What is the difference between prototyping smart device interfaces vs non-smart device interfaces?
- What are the challenges?

![Non-smart device UI research](/static/img/smart-device/non-smart-ui-research.png) <figcaption>Research for prototyping with non-smart device interfaces.</figcaption>

![Smart device UI research](/static/img/smart-device/smart-ui-research.png) <figcaption>Research for prototyping with smart device interfaces.</figcaption>

I also researched what prototyping tools Adobe XD can integrate with. However, from my experience with the UX Playground course, we tested [ProtoPie](https://www.ProtoPie.io/) as the tool for prototyping animation and interaction (this was before Adobe implemented the Auto-animate feature into XD).

We contacted ProtoPie who suggested we use [Arduino](https://blog.ProtoPie.io/arduino-prototyping-with-ProtoPie-7932ececfec5) and [LittleBits](https://www.youtube.com/watch?v=Iv25TVsOHdU) for smart device prototyping. I knew Arduino required programming but LittleBits needed research as I was not familiar with the product.

![My demo on a light switch using LittleBits' tutorial](/static/img/smart-device/LittleBits-experiment.png) <figcaption>My demo on a light switch using LittleBits' tutorial.</figcaption>

### Understanding interactions between human, hardware and software

For ideation, we explored how we interact with physical interfaces e.g. light switches, and how they are designed in existing smart devices. This helped us to plan our process and divide the work within the team.

![Ideation session](/static/img/smart-device/our-process.png) <figcaption>Our workflow process to create the smart device prototypes.</figcaption>

Throughout this phase, I was experimenting with LittleBits and ProtoPie. It helped us to see what types of simple interactions we can prototype for the project. The process was mostly trial and error due to limited resources for integrating LittleBits with ProtoPie. However, it was an interesting challenge as it felt like I was doing programming visually e.g. logical steps and conditional states for triggering animations, considering the inputs and outputs, and how inputs may produce the output.

![ProtoPie light dimming prototype connected to LittleBits components](/static/img/smart-device/littlebits-protopie-light-prototype.webp) <figcaption>Light dimming prototype (ProtoPie) connected to LittleBits components. The Light Wire component turns on at 40% brightness when I use the Light Dimmer component. The light becomes 100% brightness when I use the slider.</figcaption>

https://vimeo.com/320971006

Due to the complexity of developing the prototype digitally and physically, I had to do this in two parts:

- Create prototypes in ProtoPie
- Integrate LittleBits to the ProtoPie prototypes

#### Creating prototypes in ProtoPie

From our Ideation, we focused on creating prototypes for the following interactions:

- To control lights by dimming and switching them on/off
- Play music with the option to skip songs
- Monitor and change room temperature on the AC unit

We also researched animations and interactions created by other designers for inspiration. However, we were mindful of creating animations/interactions that should feel familiar and natural (as to the real world) e.g. [adjusting brightness with a slider](https://dribbble.com/shots/3572111-Adjust-the-brightness-level-Principle-working-file%E2%80%9D).

Before prototyping, Stephanie created the designs in Adobe XD. I then imported them into ProtoPie and experimented with different solutions. It was an iterative process until we found a solution that matches the vision we had for each of the prototypes.

![A test prototype for controlling light](/static/img/smart-device/light-switch-prototype.png) <figcaption>A test prototype for creating sliders and switches to control light.</figcaption>

![A dashboard prototype for iPad](/static/img/smart-device/dashboard-ipad-prototype.png) <figcaption>Creating the dashboard prototype for iPad.</figcaption>

![A music player prototype for Pixel 2](/static/img/smart-device/musicplayer-pixel2-prototype.png) <figcaption>Creating the music player prototype for Pixel 2.</figcaption>

![A ac prototype for iPhone](/static/img/smart-device/ac-iphone-prototype.png) <figcaption>Creating the air conditioning controller prototype for iPhone.</figcaption>

### Integrating LittleBits with the prototypes

When the prototypes are complete, the next step is to include LittleBits. So far, the only method for connecting ProtoPie and LittleBits is to have the same message ID. This is like a destination address for sending and receiving messages. The ID is entered into ProtoPie and the bridge app (provided by ProtoPie) to enable communication between the two.

Again, I had to do many tests and iterations because the hardware can change the states and inputs/outputs of the prototype. The process was time-consuming because integrating LittleBits added another layer of complexity.

The following videos are all of the prototypes demonstrated at Adobe Max 2018, UX Playground and Digital Age Tech Summit.

https://vimeo.com/320971419

<br/>     

https://vimeo.com/320973092

<br/> 

https://www.youtube.com/watch?v=NF3dL5OCfcE

### Sharing with the community

Our work was showcased at:

- [UX Playground at WeWork London with 75 signups](https://www.meetup.com/UX-Playground-The-User-Experience-Meetup-for-Londoners/events/254440446/)
- [Adobe Max 2018 in Los Angeles](https://2018.max.adobe.com/sessions/max-online/#24803)
- [Digital Age Tech Summit in Istanbul](https://digitalagesummit.com/en/schedule/the-smartest-kid-on-the-block-designing-and-prototyping-smart-device-experiences/)

![Chakib explaining LittleBits to the audience at UX Playground at WeWork London.](/static/img/smart-device/ux-playground.png) <figcaption>Chakib explaining LittleBits to the audience at UX Playground (WeWork London).</figcaption>

[![Recording of Chakib presenting at Adobe Max 2018](/static/img/smart-device/adobe-max-2018.png)](https://2018.max.adobe.com/sessions/max-online/#24803 "Adobe Max 2018") <figcaption>Recording of Chakib presenting at Adobe Max 2018 in Los Angeles.</figcaption>

![Chakib presenting at Digital Age Tech Summit in Istanbul.](/static/img/smart-device/digital-age-tech-summit.png) <figcaption>Chakib presenting at Digital Age Tech Summit in Istanbul. Photo by [Digital Age Tech Summit](https://digitalagesummit.com/en/galeri/) </figcaption>
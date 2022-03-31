---
title: Prototyping smart device experiences
emoji: 🚀
metaDescription: A project on prototyping smart devices using Protopie and LittleBits. This was showcased in Adobe Max 2018, UX Playground and Digital Age Summit.
summary: A project on prototyping smart devices using Protopie and LittleBits. This was showcased in Adobe Max 2018, UX Playground and Digital Age Summit.
tags:
  - Research
  - Data analysis
  - Prototyping
  - Testing
  - Animation
---

### Personal note

Creating prototypes with hardware was a fun yet challenging experience. ProtoPie can create high fidelity complex prototypes without coding, which made the process less intimidating. However, it can be time consuming as it requires testing.

When prototyping, there should be a plan on what tasks the team will do. This ensures that the final prototype achieves the vision the team has. It also helps the team to know what research is required and what solutions are possible after reviewing.

### Overview

This project focused on the tools available for prototyping with smart devices.

We prepared this project as part of the [Adobe Max event](https://2018.max.adobe.com/sessions/max-online/#24803), which took place on 15-17 October 2018. The project was also showcased in a [UX Playground meetup event](https://www.meetup.com/UX-Playground-The-User-Experience-Meetup-for-Londoners/events/254440446/) on 26 September 2018.

### Creating interactive smart device prototype

To create an interactive smart device prototype with Adobe XD, which showcases its features and how it can prototype concepts.

The following are the key areas we focused on:

- How can we design and prototype user experiences for smart devices?
- What tools are currently available to prototype smart devices?
- How can we utilise these tools to develop a simple framework for prototyping smart devices?

### Team

Natalie Man, UX Designer, Smartology
Chakib Labidi, UX Consultant and UX Playground founder
Stephanie Howard, Digital Designer, Nelson Bostock

### Research

Our research covered topics such as UI kits, interfaces, and prototyping. Since I will develop the prototype, I researched on several key points such as:

- What is the difference between prototyping smart device interfaces vs non-smart device interface?
- What are the challenges?

![Non-smart device UI research](/static/img/non-smart-ui-research.png) <figcaption>Research for prototyping with non-smart device interfaces.</figcaption>

![Smart device UI research](/static/img/smart-ui-research.png) <figcaption>Research for prototyping with smart device interfaces.</figcaption>

I also researched what prototyping tools Adobe XD can integrate with. However, from my experience with the UX Playground project, we used ProtoPie as the tool for prototyping animation and interaction (this was before Adobe implemented the Auto-animate feature into XD).

We spoke with a staff member from ProtoPie, who suggested us to use Arduino and LittleBits for smart device prototyping. I knew Arduino required programming, so I researched LittleBits as I had no knowledge on what it does.

![Smart device UI research](/static/img/littlebits.png) <figcaption>LittleBits is a tool for teaching people from all ages to build, prototype and invent with electronics.</figcaption>

### Ideation

For ideation, we explored how we interact with physical interfaces e.g. light switch, and how they are designed in existing smart devices. This is mainly to help us understand how we can do hardware prototyping.

![Ideation session](/static/img/ideation-session.png) <figcaption>One of our ideation session with Stephanie joining us online.</figcaption>

Throughout this phase, I was experimenting and testing how LittleBits work with ProtoPie. This exercise allowed us to see what types of interactions we can prototype for the project.

![Experimenting with LittleBits](/static/img/littlebits-light-dimming.png) <figcaption> Stephanie testing light dimming with LittleBits.</figcaption>

It was mostly trial and error because of limited resources on integrating LittleBits with ProtoPie. However, it was an interesting challenge as it felt like a programming exercise e.g. logical steps and conditional states for triggering animations considering the inputs and outputs for a process and how the inputs may produce the output.

![A light switch prototype for testing ProtoPie and LittleBits (off state)](/static/img/littlebits-protopie-light-off-test.png) <figcaption>A light switch prototype for testing ProtoPie and LittleBits (off state).</figcaption>

![A light switch prototype for testing ProtoPie and LittleBits (on state)](/static/img/littlebits-protopie-light-on-test.png) <figcaption>A light switch prototype for testing ProtoPie and LittleBits (on state).</figcaption>

### Prototyping

Aside from learning new tools, it was also my first experience creating animations for a UX project. Throughout the process, I was always testing and to keep the prototypes simple, we planned this phase into two parts:

- Create prototypes in ProtoPie
- Integrate LittleBits to show interactions between software and hardware

#### Creating prototypes in ProtoPie

From our Ideation, we have created prototypes for the following interactions:

- To control lights by dimming and switching them on/off
- Play music with the option to skip songs
- Monitor and change room temperature on AC unit

For inspiration, we researched animations created by designers on Dribbble. However, we also considered that the animation should feel familiar in relation to the real world e.g. [adjusting brightness with a slider](https://dribbble.com/shots/3572111-Adjust-the-brightness-level-Principle-working-file%E2%80%9D).

Before prototyping, Stephanie created the designs in Adobe XD. I then imported them into ProtoPie and experimented with different solutions. It was an iterative process until we found a solution that matches the vision we had for each of the prototype.

![A prototype for controlling light](/static/img/light-switch-prototype.png) <figcaption>A test prototype for creating sliders and switches to control light.</figcaption>

### Integrating LittleBits with the prototypes

When the prototypes are complete, the next step is to include LittleBits. So far, the only method for connecting ProtoPie and LittleBits together is to have the same message ID. This is like a destination address for sending and receiving messages. The ID is entered into ProtoPie and the bridge app (provided by ProtoPie) to enable communication between the two.

https://vimeo.com/320971006
&nbsp;
&nbsp;
Again, I had to do many tests and iterations because the hardware can change the states and inputs/outputs of the prototype. The process was time consuming because integrating LittleBits added another layer of complexity.

The following videos are two of the prototypes demonstrated at the Adobe Max 2018 and UX Playground event.

https://vimeo.com/320971419

https://vimeo.com/320973092

https://www.youtube.com/watch?v=643GX1C8vdk

### Event
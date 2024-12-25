# Gendy Cloud

*2022 - Networked music, multichannel, web interface, Csound*  

The "Gendy Cloud" is a networked, multichannel music piece that will be realized in real time by a telematic ensemble. Performers are composers, researchers, interface designers, and musicians. The ensemble members could control their instruments remotely by either using their interfaces, custom-built devices, live coding, or a web interface. Any performer can control one or more instances of the Gendy-based instrument. The control parameters are limited to reduce the learning curve and increase the adaptability to the existing interfaces. However, extensive use of stochastic processes in the instrument allows performers to create varied timbre, patterns, and textures in a multichannel diffusion system.  

The project is initially inspired by an event during Xenakis22: The Centenary Symposium <sup><a id="fnr.1" class="footref" href="#fn.1" role="doc-backlink">1</a></sup>. The participants gathered in the front of the building where Iannis Xenakis was wounded which led him to lose one eye. The composers in the organizations prepared an audio stream that participants can use on their mobile phones to join. Then the streaming sound that was made by a modern version of the GENDYN (a dynamic stochastic sound synthesis algorithm conceived by Iannis Xenakis) appeared in phones. It was a touching moment that we could be able to commemorate a great composer through his work. The idea arose from the event that if it is possible to build a software instrument based on the GENDYN algorithm many people can join in to control the audio outcome remotely.  

The Gendy Cloud has three components:  

-   A computer in the concert venue that hosts the audio software which is built on the Csound programming language.
-   An interface that can produce OSC messages. Performers that can join from any physical location. They would use either the existing web interface or their interfaces.
-   Remote OSC, a library that works as a server/client architecture and manages the data traffic between the performers and the host computer. Thanks to Remote OSC, there is no need to configure a router, IP, etc. to communicate over the Internet.  
    
    ![img](../images/GendyCloud-WORC-ensemble.png)

Gendy Cloud is the first piece that the *WORC*, a networked music ensemble has performed. The main proposition is instead of streaming audio between the peers and then to the audience, to build instruments that can be performed remotely only by sending OSC messages over the Internet. Since the amount of data is very small in terms of bytes even without a broadband Internet connection the performance will be possible without compromising audio quality. The goal of the performance is to create a dynamic "cloud" of stochastic noises.  

The *WORC* ensemble is a real-time, telematic, collaboration project in that members are composers, researchers, interface designers, and musicians. The composition of the members opens possibilities for further research on collaborative music-making in several dimensions. All practitioners of computer music are invited to join.  

The Csound audio code has a sound generator instrument that utilizes the Gendy opcode. There can be unlimited instances of the instrument so that a performer can play one or more Gendy instruments. Gendy opcode can generate a wide variety of sounds and random changes in sound can be triggered by the performer. The built-in stochastic pattern generator makes creating different textures easy. It also lifts the pressure of being alert for remote performance. A mute/unmute option is also provided for additional control. The already existing web interface matches those performing parameters with two sliders (for pattern generator), a button (for triggering new sound), and a mute switch.  

The movements of sounds in a multichannel system are controlled by random processes which also depend on the duration of the sound event. If it is shorter than one second the location of the sound is static. Otherwise, it moves randomly from one location to another.  

- Demo
  [https://youtu.be/QDBQICae23A](https://youtu.be/QDBQICae23A)

The previous performances:

- **ICSC International Csound Conference**
  /mdw - University of Music and Performing Arts (Vienna, Austria), 18 September 2024/

  [https://www.youtube.com/shorts/6h8mm8lxjOM](https://www.youtube.com/shorts/6h8mm8lxjOM)
  
  34 performers at location: Conference participants

- **IEEE International Symposium on the Internet of Sounds**
  /Fraunhofer Institute for Integrated Circuits IIS (Erlangen, Germany), 1 October 2024/

  [https://www.youtube.com/watch?v=SkRsG-N8_Is](https://www.youtube.com/watch?v=SkRsG-N8_Is)

  46 performers at location: Symposium participants
  
- **SONIFIED Symposium**
   /Arter Museum (Istanbul, Turkey), 29 December 2022/

   [https://www.youtube.com/watch?v=uBC3avitRGg](https://www.youtube.com/watch?v=uBC3avitRGg)

   Seven performers from five cities: Danny Fratina  (Boston, USA), Umut Eldem  (Antwerp, Belgium), Dimitri Papageorgiou (Thessaloniki, Greece), Vasilis Agiomyrgianakis (Athens, Greece),  Nihan Tahtaişleyen (Istanbul, Turkey), Manolis Ekmektsoglou (Istanbul, Turkey), Serkan Sevilgen (Istanbul, Turkey), 

- **XNPM22: Xenakis Networked Performance Marathon**
  /Athens Conservatory (Athens, Greece), 17 December 2022/

  [https://www.youtube.com/watch?v=bKlwMrMdlnI](https://www.youtube.com/watch?v=bKlwMrMdlnI)

  Five performers from three cities: Iannis Zannos(Japan), Vasilis Agiomyrgianakis (Greece), Serkan Sevilgen (Greece), Manolis Ekmektsoglou(Istanbul), Nihan Tahtaişleyen(Istanbul)

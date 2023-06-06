---
title: Music
---

# Nophesis

*2023 - Fixed media, algorithmic composition, soundscape*

<https://soundcloud.com/serkansevilgen/soundscape-w-urban-birds-and-noise>

The sound materials for the piece are the recorded sounds in Istanbul. Two sets of recordings, birds and human-made noises, hint different nature of sounds we hear in the city. The audio samples are matched randomly to create pairs. Spectral analysis and resynhesis tools in Csound are used to generate cross-synthesized sounds where the amplitude and frequency values from each audio are mashed together. 

# Gendy Cloud

*2022 - Networked music, multichannel, web interface, Csound*  

The "Gendy Cloud" is a networked, multichannel music piece that will be realized in real time by a telematic ensemble. Performers are composers, researchers, interface designers, and musicians. The ensemble members could control their instruments remotely by either using their interfaces, custom-built devices, live coding, or a web interface. Any performer can control one or more instances of the Gendy-based instrument. The control parameters are limited to reduce the learning curve and increase the adaptability to the existing interfaces. However, extensive use of stochastic processes in the instrument allows performers to create varied timbre, patterns, and textures in a multichannel diffusion system.  

The project is initially inspired by an event during Xenakis22: The Centenary Symposium <sup><a id="fnr.1" class="footref" href="#fn.1" role="doc-backlink">1</a></sup>. The participants gathered in the front of the building where Iannis Xenakis was wounded which led him to lose one eye. The composers in the organizations prepared an audio stream that participants can use on their mobile phones to join. Then the streaming sound that was made by a modern version of the GENDYN (a dynamic stochastic sound synthesis algorithm conceived by Iannis Xenakis) appeared in phones. It was a touching moment that we could be able to commemorate a great composer through his work. The idea arose from the event that if it is possible to build a software instrument based on the GENDYN algorithm many people can join in to control the audio outcome remotely.  

The Gendy Cloud has three components:  

-   A computer in the concert venue that hosts the audio software which is built on the Csound programming language.
-   Performers that can join from any physical location. They would use either the web interface or their interfaces (that can produce OSC messages).
-   Remote OSC, a library that works as a server/client architecture and manages the data traffic between the performers and the host computer. Thanks to Remote OSC, there is no need to configure a router, IP, etc. to communicate over the Internet.  
    
    ![img](images/GendyCloud-WORC-ensemble.png)

Gendy Cloud is the first piece that the Networked Music Ensemble (the name is hidden for anonymity) has performed. The main proposition is instead of streaming audio between the peers and then to the audience, to build instruments that can be performed remotely only by sending OSC messages over the Internet. Since the amount of data is very small in terms of bytes even without a broadband Internet connection the performance will be possible without compromising audio quality. The goal of the performance is to create a dynamic "cloud" of stochastic noises.  

The ensemble is a real-time, telematic, collaboration project in that members are composers, researchers, interface designers, and musicians. The composition of the members opens possibilities for further research on collaborative music-making in several dimensions. All practitioners of computer music are invited to join.  

The Csound audio code has a sound generator instrument that utilizes the Gendy opcode. There can be unlimited instances of the instrument so that a performer can play one or more Gendy instruments. Gendy opcode can generate a wide variety of sounds and random changes in sound can be triggered by the performer. The built-in stochastic pattern generator makes creating different textures easy. It also lifts the pressure of being alert for remote performance. A mute/unmute option is also provided for additional control. The already existing web interface matches those performing parameters with two sliders (for pattern generator), a button (for triggering new sound), and a mute switch.  

The movements of sounds in a multichannel system are controlled by random processes which also depend on the duration of the sound event. If it is shorter than one second the location of the sound is static. Otherwise, it moves randomly from one location to another.  

-   Demo  
    <https://youtu.be/QDBQICae23A>

The previous performances:  

-   XNPM22: Xenakis Networked Performance Marathon  
    Athens Conservatory (Athens, Greece), 17 December 2022  
    <https://www.youtube.com/watch?v=bKlwMrMdlnI>  
    
    WORC Ensemble members:  
    Five performers from three cities.  
    
    -   Iannis Zannos(Japan)
    -   Vasilis Agiomyrgianakis (Greece)
    -   Serkan Sevilgen (Greece)
    -   Manolis Ekmektsoglou(Istanbul)
    -   Nihan Tahtaişleyen(Istanbul)

-   SONIFIED Symposium  
    Arter Museum (Istanbul, Turkey), 29 December 2022  
    <https://www.youtube.com/watch?v=uBC3avitRGg>  
    
    WORC Ensemble members:  
    Seven performers from five cities.  
    
    -   Danny Fratina  (Boston, USA)
    -   Umut Eldem  (Antwerp, Belgium)
    -   Dimitri Papageorgiou (Thessaloniki, Greece)
    -   Vasilis Agiomyrgianakis (Athens, Greece)
    -   Nihan Tahtaişleyen (Istanbul, Turkey)
    -   Manolis Ekmektsoglou (Istanbul, Turkey)
    -   Serkan Sevilgen (Istanbul, Turkey)


# Mar8

*2022 - Fixed media, field recordings, multichannel, Csound*  

<https://soundcloud.com/serkansevilgen/mar8-stereo-mix> (Stereo mix)  

The sound materials for the piece are the recordings of the police helicopters that I made from my home window during the Women’s March at Istiklal Street on March 8th, 2021. I extracted 15 audio files after an hour of recording that you hear a helicopter comes into the soundscape and goes. The sound doesn’t move circularly in 8-channel diffusion but goes across the listening hall from many directions to eventually build up a thick and almost suffocating soundscape above the audience.  


# Sounding Microcosmos (w. Ipek Oskay)

*2022 - Live electronics, networked music, web audio, Python, Arduino, Csound*  

<https://www.youtube.com/watch?v=-ARbqdgwxSU>  

A real-time, telematic, biodata sonification project with Ipek Oskay. It was performed at **NIME 2022**, **SMC 22**, **Taking Place and Making Place Conference**, **Earth Day Art Model Telematic Festival**.  

See details and performance videos [here](https://serkansevilgen.com/sounding-microcosmos/)  


# Symphony in Blue 2.0 (w. Istanbul Coding Ensemble)

*2021 - Live Coding, Networked music, SuperCollider*  

<https://www.youtube.com/watch?v=L_mgsEHc3KY>  

Istanbul Coding Ensemble (ICE), Jerfi Aji, and Scott Wilson perform “with live coding based on machine listening data shared over network” version of “Symphony in Blue” by composer Kamran Ince.  

Istanbul Coding Ensemble (ICE) is a laptop orchestra of ITU/MIAM and has a focus on improvisation with musical algorithms using ‘just-in-time’ programming techniques and real-time communication with ad-hoc network music systems.  

The recorded performance was presented in the following events:  

-   **Transformations of Musical Creativity in the 21st Century Conference.** (27 June 2021)
-   **18th Brazilian Symposium on Computer Music.** (October 24 - 27 2021)
-   **22nd ISMIR Conference.** (November 8 - 12 2021)
-   **ICLC 2021 - International Conference on Live Coding.** 2021 (December 15-17 2021)
-   **SONIFIED Symposium 2022** (December 29-39 2022)

Live performance  

-   **EELISA Research-based Learning Symposium.** (17-18 May 2022).

<https://www.youtube.com/watch?v=WN5rQFDp3_A>  


# N, for Violin and Electronics

*2021 - Mixed composition, Lilypond, Csound*  

<https://www.youtube.com/watch?v=aKCNPT1IOjk>  


# Inside Outside (w. Fulya Ucanok)

*2021 - Mixed music, live electronics, MaxMSP*  

<https://www.youtube.com/watch?v=3zH30QuRSJQ&t=907s>  
<https://soundcloud.com/serkansevilgen/inside-outside-with-fulya-ucanok>  

Presented in **Impro Dance Festival** (27 May 2021). Dancers reacted to the music during a Zoom session.  

Fulya Ucanok ~ inside piano  
Serkan Sevilgen ~ Soundscapes  


# Coding Coppers

*2021 - Live electronics, live Coding, Python, SuperCollider, Arduino*  

<https://www.youtube.com/watch?v=2FMzYgew6co>  

Live coding is usually associated with computer-based sound generation. In this piece I try to explore the area of live coding for acoustic objects. Live coding with Python language acts as an interface to control the servo motors which are attached to an Arduino board. A microphone picks the sound and a Supercollider-based live coding interface manipulates the sounds gently. The piece is inspired by the work of Andre Valle. However the output is aimed at generating more limited sets of sounds and not excessive manipulation respecting the silent moments.  

Presented at [**ICMC 2022**](https://icmc2022.files.wordpress.com/2022/07/icmc2022_programme.pdf).  


# The Curtain and Beyond (w. Fulya Ucanok)

*2020 - live electronics, Csound*  

<https://www.youtube.com/watch?v=u9f-rb_YWTo>  

In this performance, the duo delves into the discourses around the Pythagorean curtain that has been an inspiration for the acousmatic tradition. Taking it literally, the performance integrates an actual curtain in physical space performance conditions, However, they use other virtual tools to create the curtain for network performances. The curtain aims to weave together historical and current discourses around acousmatic music practice. Integrating the acousmatic into a live performance setting, they create dialogues between parallel worlds of source-bonded/source-ambiguous sound events, various forms of presences/absences, the real/unreal, and linearity/non-linearity in the narrative.  

Performed live at the [Network Music Festival](https://networkmusicfestival.org/programme/performances/fulya-ucanok-and-serkan-sevilgen-the-curtain-and-beyond/), 2020  


# Transfigured Walls

*2020 - Fixed media, binaural, Csound*  

<https://soundcloud.com/serkansevilgen/transfigured-walls-a-binaural-acousmatic-piece-use-earphones>  

During the COVID-19 pandemic composers and musicians persevere with producing new works. However, since the only distribution channel is online we lost the ability to create multichannel music that we can design a spatial experience in physical venues. In this fixed media piece, I deliberately target the audience that consumes music with earphones. I used Csound’s HRTF (Head Related Transfer Function) opcodes to create a virtual binaural space that I can specify the dimensions of the room, reflection coefficients of the walls, floor, and ceiling. The listener would enjoy the 3D soundstage with moving sounds in all dimensions.  

It was presented during the **Share the Sound Concert** (2020) and **Tehran International Electronic Music Festival** (2022)  


# Image sonification in memoriam Ertuğrul Oğuz Fırat

*2020 - Fixed media, Python, Csound*  

<https://soundcloud.com/serkansevilgen/image-sonification-in-memoriam-ertugrul-oguz-firat>  

This piece was composed in memory of the Turkish composer, painter, and poet Ertuğrul Oğuz Fırat (1923-2014). One of the composer’s paintings, Politika, is used as a material for the image sonification. The RGB (red, green, blue) channel data of each pixel in Politika was read with Python programming language. In Csound, image data is mapped to several parameters to reveal the patterns in the painting in the rhythmic texture.  

It was presented during the homage concert on 10 February 2020 at **ITU/MIAM Library** and **SIIDS - Sound, Image and Interaction Design Symposium** (2020)  


# Wanderer

*2019 - Fixed media, multichannel, Csound*  

<https://soundcloud.com/serkansevilgen/octophonic-site-specific-piece-for-the-miam-gallery> (Stereo render)  

This piece is composed for an 8-channel diffusion system in which speakers are spread through MIAM Gallery. Works for the concert are site-specific, composed for a bespoke multichannel diffusion system, making the event fall somewhere between an installation and a concert. Attendees are encouraged to move around to tailor their audio-spatial experience. The piece is consists of distinct sections that I explore different sonic textures. The sections are self-contained and don’t present a particular progression. The musical material is laid out and sufficient time is given to the listener to consume the possibilities in limited musical material. The piece was composed solely in Csound.  

It was presented during the “Sonic Tales from the Crypt” concert on 26 December 2019 at **ITU/MIAM Gallery** and in the **Festival of Sound Art and Transmedia Ecos Urbanos (Mexico and CCRMA/Stanford)**  


# Spectral Collage

*2019 - Sound Installation, MaxMSP, field recordings*  

<https://soundcloud.com/serkansevilgen/spectral-collage-render-1>  

Proof-of-concept render of a sound installation work that is supposed to be run for the duration of an exhibition. Layers of sounds from field recordings of a city/site are torn down gradually with a very steep-sloped, brick wall type filter. After a while what we hear is slow but everchanging frequencies which any audio layers can hardly be distinguishable.  


# Strng Wnd

*2019 - Fixed media, Soundscapes*  

<https://soundcloud.com/serkansevilgen/strng-wnd>  

"I try to detect and record soundscapes that resemble my ideas of sound design and composition. Awareness of sonic environment and making decisions, what and how to record makes recording more like a compositional process. In this track I have removed the wind shield from Sennheiser MKH 416 shotgun microphone and exposed it to a very strong wind."  

Presented at the **Istanbul Soundscape Concert** (2019)  


# Released soundscapes

Two soundscape pieces published in the 2013 World Listening Day compilation by Sonic Field.  
Sonic Field is a bilingual, interdisciplinary network around sonic arts, sound studies and aural culture.  
<http://sonicfield.org>  

-   <https://sonicterrain.bandcamp.com/track/istanbul-subway>
-   <https://sonicterrain.bandcamp.com/track/istanbul-gezi-park-protests>


# Binaural Recordings of Soundinit Soundwalks

<https://soundcloud.com/serkansevilgen/sets/soundinit-soundwalks>  


# Various Field Recordings

Mono, stereo and binaural field recordings over the years  

<https://soundcloud.com/serkansevilgen/sets/field-recordings>  


# Footnotes

<sup><a id="fn.1" href="#fnr.1">1</a></sup> <https://xenakis2022.uoa.gr/>

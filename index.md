title: JSDay Madrid 2017
class: animation-fade
layout: true

<!-- This slide will serve as the base layout for all your slides -->
.bottom-bar[
  {{title}}
]

---

class: impact

# {{title}}
## { ...rest }

---

# The Agenda 

## The Flash Talks

10 min quick talks about cool stuff, companies and whoever wanted to say anything (seriously they invited people from the audience up to the stage).

## The Talks

Specific talks about different topics (mostly about JS and the universe around it).

---

## Day Uno

### http://2017.jsday.es/#5642674782601216

- PRDeving: Construyendo un Rasterizador 3D con iluminacion dinámica en JS vanilla en 10 minutos

- Creating good-ol' PDFs and Emails with React (amazing how this has gotten so much attention lately)

- Splitting the Monolith from a Front-End point of view (Spotahome commercial - not cool)

---

## Day Dos

### http://2017.jsday.es/#5740078466859008

- IoT
- VR
- Forensics / Debugging
- Containers and how to manage a lot of them
- More IoT
- Front End Security
- ES...N
- JavaScript engines
- Substack

---

## ¿Una plataforma de IoT sólo con JS? Es posible... y además, ¡barato!

**José Manuel García García**

http://2017.jsday.es/#5740078466859008/104184002

- Controllers
- Sensors
- Integration between controllers & sensors

---

## ¿Una plataforma de IoT sólo con JS? Es posible... y además, ¡barato!...

### Libraries

- CyclonJS
- Johnny Five

### Low level

- mraa

### High level

- jsump_grove

---

## ¿Una plataforma de IoT sólo con JS? Es posible... y además, ¡barato!...

### Links

- https://github.com/semagarcia

- https://github.com/semagarcia/JSDayES2017-iot-platform

- @semagarcia

---

## Building VR experiences

**Belen Albeza**

http://2017.jsday.es/#5740078466859008/102034003

### A-Frame 

- WebVR
- Custom elements
- No JS for designers
- Uses ThreeJS and WebGL
  - Primitives from ThreeJS
- Entity-Component-System
- Positional audio (work in progress)

---

## Building VR experiences...

### Links

- https://aframe.io/

- https://github.com/belen-albeza/

- https://github.com/belen-albeza/building-vr

- belen@mozilla.com

- @ladybenko

---

## Técnicas Forenses en JavaScript

**Eduardo Sada**

http://2017.jsday.es/#5740078466859008/102064002

### Chrome Dev Tools on a rush

- Enable Chrome Experimental Features by clicking shift 6 times (Canary?)
- Blackboxing from Chrome
- Flow Events
- End goal: Google Chrome as Editor (even with version control)
- App Audits - lighthouse style? (reference @links)
- Speedracer.js - Chrome audits from node
- API performance js

---

## Técnicas Forenses en JavaScript...

### Links

- https://github.com/eduardosada

- https://github.com/GoogleChrome/lighthouse

- @aeroalquimia

---

## Creando una arquitectura de microservicios en node.js y Kubernetes

**Paul Goldbaum**

http://2017.jsday.es/#5740078466859008/99974002

### Networking between containers

- Containers asynchronously starting and stopping (sometimes not on purpose)
- Architecture
  - Synch via http (status => ping)
  - Graceful shutdown
  - Asynch messages using a message bus with pub/sub

---

## Creando una arquitectura de microservicios en node.js y Kubernetes...

### Elixir

Used to scale up apps (bear in mind it is hard, you probably don't need Elixir right away)

### Links

- CTO @ http://www.seedtag.com

- https://elixir-lang.org/

- @paulgoldbaum

---

## Invisible o desaparece

**Juliet Moreiro Bockhop**

http://2017.jsday.es/#5740078466859008/97064002

### Corporate sponsored talk (Microsoft)

The world is more connected than what we imagine: Amazon's Alexa helped out in a murder case.

They showcased their new tools: apis (vision, language, etc) and services for IoT.

They came up with a cool example to do so: a real-time sentiment engine for a specific twitter search (a hashtag selected for the talk) would send data to an internet-connected-lightbulb and shine accordingly (blue: neutral; red: bad; green: cool).

---

## Invisible o desaparece...

### Links

- https://www.slideshare.net/JulietRMoreiroBockho/invisible-o-desaparece-jsdayes-2017-76164849

- https://github.com/nebgnahz/awesome-iot-hacks

- @julietsvq

---

## Un paso más en seguridad FrontEnd con Web Crypto API

**Jon Roji**

http://2017.jsday.es/#5740078466859008/102874001


### Web Cripto API

- Security on top of https
- Directly in JS
- Using Private & Public keys

---

## Un paso más en seguridad FrontEnd con Web Crypto API...

### Use case

Send cyphered & encripted data from a client to another client via a server.

A messaging app that offers end to end encription.

This way the server cannot interfere (nor read) the messages, nor tamper, etc.

---

## Un paso más en seguridad FrontEnd con Web Crypto API...

### Links

- https://github.com/jroji

- https://github.com/serenity-frontstack

- @Jnroji

---

## ES7 & ES8 vs V8

**Rafael Casuso Romate**

http://2017.jsday.es/#5740078466859008/103414002

### JS version release process

- How do new features get into the proposal and then to the spec

### New features coming

- Async & Await
- Webworkerrs & Atomics
- Object entries & object values

---

## ES7 & ES8 vs V8...

### New features coming...

- String padding
- Get own property descriptors

### ES9 in the future

- Object destructuring
- Async iteration
- Import (in runtime)

---

## ES7 & ES8 vs V8...

### Links

- CTO @StayApp && @SnowStormIO

- https://www.slideshare.net/RafaelCasusoRomate/javascript-editions-es7-es8-and-es9-vs-v8

- @Rafael_Csuso

---

## Demystifying (JavaScript) engines

**Alejandro Oviedo**

http://2017.jsday.es/#5740078466859008/99964005

### Toretto's complex (yep from Fast & Furious)

> Devs love benchmarks, because they always want to be using the best tools.

He decided to learn how the differente browser engines deal with JS.

JITs cannot handle _with_, _try & catch_ and _eval_.

He showcased JIT optimizations with loop examples.

---

## Demystifying (JavaScript) engines...

### Links

- https://github.com/a0viedo

- https://github.com/a0viedo/demystifying-js-engines

- @a0viedo

---

## the web these days

**James Halliday** (aka Substack, aka creator of browserify and tape)

http://2017.jsday.es/#5740078466859008/97864001


This mad genius (using only two slipers and vi) showcased:

- a peer-to-peer descentralized social network (you can follow people and avoid spam and no central authority sets rules or sells your data)

- a webGL example with live audio (generated using the web audio API)

---

## the web these days...

### Links

- https://github.com/substack

- https://github.com/substack/jsday-es-2017

- https://github.com/substack/jsday-madrid-workshop

- https://github.com/ssbc/secure-scuttlebutt

- @substack

---

### EOF 

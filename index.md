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
## You should've been there

---

# The Agenda 

## The Flash Talks

10 min quick talks about cool stuff, companies and whoever wanted to say anything (seriously they invited people from the audience up to the stage)

## The Talks

Specific talks about different topics (mostly about JS and the universe around it)

---

## Day Uno

### http://2017.jsday.es/#5642674782601216

- PRDeving: Construyendo un Rasterizador 3D con iluminacion dinámica en JS vanilla en 10 minutos

---

## Day Dos 

- IoT
- VR
- Forensics (debugging)
- Containers and how to manage a lot of them
- + IoT
- Front End Security
- ESN
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

### high level

- jsump_grove

---

## Building VR experiences

**Belen Albeza**

http://2017.jsday.es/#5740078466859008/102034003

### A-Frame 

- Make WebVR
- Custom elements
- No JS for designers
- Uses ThreeJS and WebGL
  - Primitives from ThreeJS
- Entity-Component-System (Unity type of architecture - although they haven't formally described their apprach as 'ECS')
- Positional audio (work in progress)

---

## Building VR experiences...

### Links

- https://aframe.io/
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
  - Terminal Drawer - not just there yet
- App Audits - lighthouse style?
- Speedracer.js - Chrome audits from node
- API performance js

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

## Creando una arquitectura de microservicios en node.js y Kubernetes

### Elixir

Used to scale up apps (bear in mind it is hard, you probably don't need Elixir right away)

---

## Invisible o desaparece

**Juliet Moreiro Bockhop**

http://2017.jsday.es/#5740078466859008/97064002

### Corporate sponsored talk (Microsoft)

They wanted to showcase thier new tools, apis (vision, language, etc) and services. for IoT so they came up with a cool example to do so: a real-time sentiment engine for a specific twitter search (a hashtag selected for the talk) would send data to an internet-connected-lightbulb and shine accordingly (blue: neutral; red: bad; green: cool).

She also mentioned how the world is more connected than what we imagine. She mentioned a situation where Amazon's Alexa helped out in a murder case. And how there are new and unexpected situations: new skills needed, unsecure IoT devices.

---

## Invisible o desaparece...

### Links

- https://github.com/nebgnahz/awesome-iot-hacks

---

## Un paso más en seguridad FrontEnd con Web Crypto API

**Jon Roji**

http://2017.jsday.es/#5740078466859008/102874001

https://github.com/jroji

### Web Cripto API

- Security on top of https
- Directly in JS
- Using Private & Public keys

---

## Un paso más en seguridad FrontEnd con Web Crypto API...

### Use case

Send cyphered & encripted data from a client to another client via a server.

e.g. - a messaging app that offers end to end encription. This way the server cannot interfere (nor read) the messages, nor tamper, etc.

---

## ES7 & ES8 vs V8

**Rafael Casuso Romate**

@Rafael_Csuso

CTO @StayApp && @SnowStormIO

http://2017.jsday.es/#5740078466859008/103414002

Slides: https://www.slideshare.net/RafaelCasusoRomate/javascript-editions-es7-es8-and-es9-vs-v8

### JS version release process

- How do new features get into the proposal and then to the spec

---

## ES7 & ES8 vs V8...

### New features coming

- Async & Await
- Webworkerrs & Atomics
- Object entries & object values
- String padding
- Get own property descriptors

### ES9 in the future

- Object destructuring
- Async iteration
- import (in runtime)

---

## Demystifying (JavaScript) engines

**Alejandro Oviedo**

http://2017.jsday.es/#5740078466859008/99964005

https://github.com/a0viedo

https://twitter.com/a0viedo

### Toretto's complex (yep from Fast & Furious)

> Devs love benchmarks, because they always want to be using the best tools.

He decided to learn how the differente browser engines deal with JS.

JITs cannot handle _with_, _try & catch_ and _eval_.

He showcased JIT optimizations with loop examples.

---

## Demystifying (JavaScript) engines...

### Links

https://github.com/a0viedo/demystifying-js-engines

---

## the web these days

**James Halliday** (aka Substack, aka creator of browserify and tape)

http://2017.jsday.es/#5740078466859008/97864001

https://github.com/substack/jsday-es-2017

https://github.com/substack/jsday-madrid-workshop

This mad genius (using only two slipers and vi) showcased:

- a peer-to-peer descentralized social network (https://github.com/ssbc/secure-scuttlebutt)
- a webGL example with live audio (generated using the web audio API)

---

### EOF 

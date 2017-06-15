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
- Kubernetes
- Visible or Invisible
- Front End Security
- ESN
- Javascript engines
- substack

---

## ¿Una plataforma de IoT sólo con JS? Es posible... y además, ¡barato!

**José Manuel García García**

http://2017.jsday.es/#5740078466859008/104184002

- Controllers
- Sensors
- Integration between controllers & sensors

---

## ¿Una plataforma de IoT sólo con JS? Es posible... y además, ¡barato!

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

## Building VR experiences

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

# There's more

## Syntax highlighting

You can also add `code` to your slides:
```html
<div class="impact">Some HTML code</div>
```

## CSS classes

You can use .alt[shortcut] syntax to apply .big[some style!]

...or just <span class="alt">HTML</span> if you prefer.

---

# And more...

## 12-column grid layout

Use to the included **grid layout** classes to split content easily:
.col-6[
  ### Left column

  - I'm on the left
  - It's neat!
]
.col-6[
  ### Right column

  - I'm on the right
  - I love it!
]

## Learn the tricks

See the [wiki](https://github.com/gnab/remark/wiki) to learn more of what you can do with .alt[Remark.js]

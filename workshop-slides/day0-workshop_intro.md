---
marp: true
theme: gaia
class: invert
paginate: true
style: |
  .columns {
    display: grid;
    grid-template-columns: repeat(2, minmax(0, 1fr));
    gap: 1rem;
  }
header: "*PCB Design Workshop* :computer:"
---
<!-- _header: "" -->
# LEC PCB Design Workshop 2026

Learn to design a simple PCB end-to-end using KiCad! And if time and budget permits, we'll assemble and test the board YOU design!!

<Insert KiCad logo here>

**Presented by:** *Jake Monster*

---

<div class=columns>
<div>

## Prerequisites

* Some basic electronics knowledge (<u>\></u>1 yr. electrical or LEC)
* Laptop with KiCad and git or GH Desktop installed
* GitHub account

</div>
<div>

### Nice-to-haves

* Multimeter experience
* git experience
* Arduino or basic CS experience
* Your preferred note-taking system (lots to cover)

</div>
</div>
<!-- Add links to required programs/accounts -->

### *Let me know before the workshop starts if you are missing one or more of the listed items!!*

---

<div class=columns>
<div>

### What will be taught

* Basic digital design in KiCad
* Developing an MVP
(minimum viable product)
* Little bit of datasheets
* Schematic best practices
* Layout best practices
* Using soldering irons, multimeters, and oscilloscopes

</div>
<div>

### What will <u>NOT</u> be taught

* Basic electrical theory (Ohms law, parallel/series, etc.)
  * Component specifics
* Firmware development
  * FW will be provided
* SPICE simulation (CircuitJS will be used)

</div>
</div>

---

## Rough Schedule

* **Day 1** (hybrid, 3-4 hrs.): *Anatomy of a PCB*
  * What is a schematic, PCB, and KiCad?
  * Design patterns and PCB stackup
  * Intro to KiCad by creating a keychain light
* **Day 2** (hybrid, 3-4 hrs.): *Project Design*
  * Choose a project and (hopefully) mostly finish a design
* **Day 3** (in-person, 2-3 hrs.): *Assembly and Testing*
  * Solder your board and see it on the oscilloscope
<!-- _footer: "Specific dates will be posted later" -->
---

## Project Ideas

* Simple DC-DC converter (9v to 3.3v/5v step-down converter)
* Adj. brushed motor speed controller
* Adj. clock signal generator (square waves go brrrr)
* Light theramin (demo'd in LEC, prototype edition)
* Simple MCU development board* (DIY Arduino with smaller chips)
* Simple breakout board
* Binary dice* (D20 but electrical and only goes up to 16...)

*These are just suggestions... if you have another idea, let me know!*
<!-- _footer: "* - Would not recommend if not getting into firmware development" -->

---

## Workshop Repository

https://github.com/venomboss985/lec-pcb-workshop-2026

* This workshop can be followed along and submit projects via this repository
* Available files:
  * Workshop slides (raw and rendered)
  * Additional useful resources for PCB design
  * Demo projects (keychain LED + others)
  * Workshop submissions*
<!-- _footer: "* - Final submissions won't be pushed to main until after day 3" -->
---

## Project Support

> *No such thing as a stupid question, just stupid people who don't ask questions.*

* If you have a question, interrupt me at any point if I don't address it
* **Let me know ASAP if you:**
  * Get a different result from replicating something I do
  * git/GitHub isn't working (likely an SSH token thing)
  * Encounter weird KiCad bugs
* If remote, use the #:interrobang:-forum channel in LEC to ask questions about your project before the design review

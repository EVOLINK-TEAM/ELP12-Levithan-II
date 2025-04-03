<h1 align="center">ELP12-Levithan-II</h1>

<div style="display: flex; justify-content: flex-end; align-items: center;">
    <img src="images/evolink.png" alt="Logo" style="height: 2em;margin-right:1.5em">
    <span style="vertical-align:middle">ELP-12 FROM SIREN..</span>
</div>

## Overview

A real hifi player，It is true music ( ToT )

<p align="center">
 <img border="1px" width="80%" src="./images/main.jpg" alt="main.jpg">
</p>

<p align="center">
 <img border="1px" width="80%" src="./images/show1.jpg" alt="show1.jpg">
</p>

<p align="center">
 <img border="1px" width="80%" src="./images/show2.jpg" alt="show2.jpg">
</p>

<p align="center">
 <img border="1px" width="80%" src="./images/show3.jpg" alt="show3.jpg">
</p>

## Features

This project aims to adapt to different customization scenarios using highly customizable acoustic hardware modules.~~Trade expensive capacitors for better sound(笑~~

The core components can be divided into `Power Board`, `Digital Interface Board`, `DAC Board`, and `Amp Card`.

- Power Board

  This board is the largest board and the base board of the project, providing positive and negative power and digital power for other circuits, as well as providing a headphone jack. Power can be supplied to the circuit through two `16340` batteries

<p align="center">
 <img border="1px" width="80%" src="./images/power_pcb.png" alt="power_pcb">
</p>

- Digital Interface Board

  This board converts the signal of the playback device into the input signal of the DAC, such as (USB->IIS), which may require the use of a good crystal oscillator and a clean interface power supply to achieve the best performance

<p align="center">
 <img border="1px" width="80%" src="./images/di_pcb.png" alt="di_pcb">
</p>

- DAC Board

  This board is the soul of the project, because the tone generator is here, and from here on it's the realm of analog circuits.

<p align="center">
 <img border="1px" width="80%" src="./images/dac_pcb.png" alt="dac_pcb">
</p>

- Amp Card

  And then there's my favorite part, where the audio signal ends up on the board, passes through the Amp circuit, and is enough to drive headphones with up to 600r.

  In addition, some special circuits can be used to create different tones, which of course need to be achieved by the user himself.

  Therefore, I made this board into a hot-swappable design, so that users can change their needs at any time.

  I have made a total of two versions, no matter which version is good, I like the design of the upper and lower layers, the upper layer is the Amp layer, the lower layer is the impedance matching and buffer layer, so that the two double layers can achieve the effect of a four-layer board, and at the same time, it is easy to disassemble and assemble.

  <p align="center">
   <img border="1px" width="40%" src="./images/amp_amp_pcb.png" alt="amp_pcb">
   <img border="1px" width="40%" src="./images/amp_buffer_pcb.png" alt="buffer_pcb">
  </p>

  <p align="center">
   <img border="1px" width="40%" src="./images/real_amp_pcb1.jpg" alt="real_amp_pcb">
   <img border="1px" width="40%" src="./images/real_amp_pcb2.jpg" alt="real_buffer_pcb">
  </p>

Example of an overall assembly (without housing):

<p align="center">
 <img border="1px" width="80%" src="./images/real_pcb.jpg" alt="real_pcb.jpg">
</p>

## Whats New

It's clear that we've made significant improvements in size and integration.Unfortunately, it is not possible to plug and unplug the op amp directly.

Here is the actual circuit board of version 1.0:

<p align="center">
 <img border="1px" width="80%" src="./images/old_v1.0_img1.jpg" alt="old_v1.0_img1.jpg">
</p>

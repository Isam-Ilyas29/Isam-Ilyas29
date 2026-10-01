<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/header-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="assets/header-light.svg">
  <img alt="Isam Ilyas — Build it. Measure it. Understand it. C++, systems and computer architecture." src="assets/header-light.svg" width="100%">
</picture>

<p align="center">
  <strong>Electronic &amp; Information Engineering · Imperial College London</strong><br>
  <sub>Seeking Summer 2027 software engineering internships</sub>
</p>

<p align="center">
  <a href="#selected-work">Selected work</a> &nbsp; / &nbsp;
  <a href="#current-focus">Current focus</a> &nbsp; / &nbsp;
  <a href="#beyond-the-terminal">Beyond the terminal</a>
</p>

<p align="center">
  <a href="mailto:isam.ilyas24@imperial.ac.uk">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="assets/contact-email-dark.svg">
      <source media="(prefers-color-scheme: light)" srcset="assets/contact-email-light.svg">
      <img alt="Email" src="assets/contact-email-light.svg" width="126">
    </picture>
  </a>
  &nbsp;
  <a href="https://www.linkedin.com/in/isamilyas/">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="assets/contact-linkedin-dark.svg">
      <source media="(prefers-color-scheme: light)" srcset="assets/contact-linkedin-light.svg">
      <img alt="LinkedIn" src="assets/contact-linkedin-light.svg" width="146">
    </picture>
  </a>
</p>

---

I like understanding what sits underneath an abstraction: how a numerical expression becomes instructions, how a renderer turns matrices into pixels, and how software talks to hardware.

My projects span **C++ execution engines, graphics and embedded software**. I’m especially interested in where software design meets hardware behaviour.

## Selected work

<table>
<tr>
<td width="50%" valign="top">

<h3>01 / FastStreamCompute</h3>

<p><strong>Compiling maths down to the metal.</strong></p>

<p>A C++20 numerical execution engine that compiles expression graphs into custom register bytecode for SIMD-vectorised, chunked batch evaluation. Execution is optimised through cache-aligned memory layouts, graph rewrites, opcode fusion and persistent concurrent workers.</p>

<p><strong>Measured:</strong> Throughput of <strong>1.66 billion records/s</strong> across 6 workers; a <strong>7.9× execution speedup</strong> and an <strong>86% instruction reduction</strong>, verified using Linux perf and hardware performance counters.</p>

<p><sub>Workload-specific results; benchmark context and limitations are documented in the repository.</sub></p>

<p><code>C++20</code> <code>CMake</code> <code>Google Benchmark</code> <code>perf</code></p>

<p><a href="https://github.com/Isam-Ilyas29/FastStreamCompute"><strong>Explore the engine →</strong></a></p>

</td>
<td width="50%" valign="top">

<h3>02 / Game Engine</h3>

<p><strong>Controlling pixels. From vertex to viewport.</strong></p>

<p>A cross-platform C++/OpenGL engine with shader and texture loading, 3D camera controls, transformations, post-processing and a docked editor.</p>

<p>A 3D Snake demo brings together rendering, input and camera systems on Windows and Linux.</p>

<p><code>C++17</code> <code>OpenGL</code> <code>CMake</code></p>

<p><a href="https://github.com/Isam-Ilyas29/Game-Engine"><strong>Explore the engine →</strong></a> &nbsp; · &nbsp; <a href="https://github.com/Isam-Ilyas29/Game-Engine#demo-3d-snake">See the demo</a></p>

</td>
</tr>
<tr>
<td width="50%" valign="top">

<h3>03 / Game Boy Game</h3>

<p>A Game Boy game written in assembly, with tile and sprite mapping, VRAM banking, OAM sprite handling, DMA transfers, hardware timers and joypad input synchronised with VBlank interrupts.</p>

<p><code>Assembly</code></p>

<p><a href="https://github.com/Isam-Ilyas29/Gameboy-Game"><strong>Explore the game →</strong></a></p>

</td>
<td width="50%" valign="top">

<h3>04 / ST7735 Display Driver</h3>

<p>Display-driver work in C for STM32, covering SPI communication with an ST7735 LCD, display configuration and RGB565 colour.</p>

<p><code>C</code> <code>STM32</code> <code>SPI</code> <code>Hardware</code></p>

<p><a href="https://github.com/Isam-Ilyas29/ST7735-Drivers"><strong>Read the driver →</strong></a></p>

</td>
</tr>
</table>

## Current focus

<picture>
  <source media="(max-width: 640px) and (prefers-color-scheme: dark)" srcset="assets/focus-mobile-dark.svg">
  <source media="(max-width: 640px) and (prefers-color-scheme: light)" srcset="assets/focus-mobile-light.svg">
  <source media="(prefers-color-scheme: dark)" srcset="assets/focus-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="assets/focus-light.svg">
  <img alt="Investigating the cost of general programmability: how much execution overhead can I remove without hard-coding the computation?" src="assets/focus-light.svg" width="100%">
</picture>

## Beyond the terminal

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/hobby-triathlon-dark.svg">
    <source media="(prefers-color-scheme: light)" srcset="assets/hobby-triathlon-light.svg">
    <img alt="Triathlon" src="assets/hobby-triathlon-light.svg" width="160">
  </picture>
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/hobby-scuba-dark.svg">
    <source media="(prefers-color-scheme: light)" srcset="assets/hobby-scuba-light.svg">
    <img alt="Scuba diving" src="assets/hobby-scuba-light.svg" width="160">
  </picture>
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/hobby-cricket-dark.svg">
    <source media="(prefers-color-scheme: light)" srcset="assets/hobby-cricket-light.svg">
    <img alt="Cricket" src="assets/hobby-cricket-light.svg" width="160">
  </picture>
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/hobby-photography-dark.svg">
    <source media="(prefers-color-scheme: light)" srcset="assets/hobby-photography-light.svg">
    <img alt="Film photography" src="assets/hobby-photography-light.svg" width="160">
  </picture>
</p>

---

<p align="center">
  <sub>Build something interesting. Find out how it works. Make it better.</sub>
</p>

---
layout: slides
title: Introduction to Bonsai
permalink: /slides/intro/
---

<section data-markdown data-separator="^\n---\n$" data-separator-vertical="^\n--\n$">
<script type="text/template">

![Bonsai](../../assets/images/bonsai-lettering.svg)

### Introduction to Bonsai
[neurogears.org/esc-2025](https://neurogears.org/esc-2025)
<table style="width: 100%;">
  <tr>
    <th style="vertical-align: middle; width: 40%; height: 100px; padding-left: 180px">
      <img alt="NeuroGEARS" src="../../assets/images/neurogears.svg"/>
    </th>
    <th style="vertical-align: middle; width: 40%; height: 100px; padding-left: 80px; align: right">
      <img alt="ESC" src="../../assets/images/esc.png"/>
    </th>
  </tr>
</table>

---

### Outline

* What is Bonsai?
* Hardware & Software Ecosystem
  * Harp
  * Open-Ephys
  * Fiber photometry, etc
  * DeepLabCut, SLEAP
  * ...

---

<!-- .element: data-transition="default none" -->
#### What is Bonsai?
![Reactive Programming](../../assets/images/bonsai-algebra-1.svg)
<!-- .element: class="fragment" data-fragment-index="1" -->

--

<!-- .element: data-transition="none" -->
#### What is Bonsai?
![Reactive Programming](../../assets/images/bonsai-algebra-2.svg)

--

<!-- .element: data-transition="none" -->
#### What is Bonsai?
![Reactive Programming](../../assets/images/bonsai-algebra.svg)

---

#### What is Bonsai?

![Bonsai](../../assets/images/bonsai-core.svg)

---

<!-- .element: data-transition="default none" -->
![Workflow](../../assets/images/graycam.svg)
<!-- .element: style="display: inline-block; vertical-align: middle;" -->
![Marble diagram](../../assets/images/graycam-marble.svg)
<!-- .element: class="fragment" style="display: inline-block; vertical-align: middle;" -->

--

<!-- .element: data-transition="default none" -->
![Workflow](../../assets/images/graycam.svg)
<!-- .element: style="display: inline-block; vertical-align: middle;" -->
![Marble diagram](../../assets/images/graycam-marble-effects.svg)
<!-- .element: style="display: inline-block; vertical-align: middle;" -->

--

<!-- .element: data-transition="default none" -->
![Workflow](../../assets/images/graycam.svg)
<!-- .element: style="display: inline-block; vertical-align: middle;" -->
![Marble diagram](../../assets/images/grayscaletransform.svg)
<!-- .element: style="display: inline-block; vertical-align: middle;" -->

--

<!-- .element: data-transition="default none" -->
![Workflow](../../assets/images/framepicker-key.svg)
<!-- .element: style="display: inline-block; vertical-align: middle;" -->
![Marble diagram](../../assets/images/framepicker-marblecanvas.svg)
<!-- .element: style="display: inline-block; vertical-align: middle;" -->

--

<!-- .element: data-transition="none" -->
![Workflow](../../assets/images/framepicker-sample.svg)
<!-- .element: style="display: inline-block; vertical-align: middle;" -->
![Marble diagram](../../assets/images/grayscalesample.svg)
<!-- .element: style="display: inline-block; vertical-align: middle;" -->

--

<!-- .element: data-transition="none" -->
![Workflow](../../assets/images/framepicker-saveimage.svg)
<!-- .element: style="display: inline-block; vertical-align: middle;" -->
![Marble diagram](../../assets/images/saveimage.svg)
<!-- .element: style="display: inline-block; vertical-align: middle;" -->

--

<!-- .element: data-transition="none" -->
![Workflow](../../assets/images/framepicker-saveimage.svg)
<!-- .element: style="display: inline-block; vertical-align: middle;" -->
![Marble diagram](../../assets/images/saveimagesink.svg)
<!-- .element: style="display: inline-block; vertical-align: middle;" -->

---

![Bonsai workflow editor](../../assets/images/editor.jpg)

---

![Bonsai Ecosystem](../../assets/images/bonsai-ecosystem.svg)

</script>
</section>

<!-- Raw HTML for embedded iframe backgrounds -->
<section data-background="#000000">
    <section data-background-iframe="https://www.youtube.com/embed/wwU6TzUJxNU?controls=0&amp;enablejsapi=1&amp;autoplay=1&amp;loop=1&amp;playlist=wwU6TzUJxNU&amp;showinfo=0&amp;rel=0&amp;html5=1">
      <table style="height: 20%; margin-top: 65%; margin-left: -78px;">
        <tr><th>Gonçalo Lopes, Kampff Lab</th></tr>
      </table>
    </section>
    <section data-background-iframe="https://www.youtube.com/embed/qXqAXgXJPmo?controls=0&amp;enablejsapi=1&amp;autoplay=1&amp;showinfo=0&amp;rel=0&amp;html5=1">
      <table style="height: 20%; margin-top: 65%; margin-left: -78px;">
        <tr><th>Lorenza Calcaterra, Kampff Lab</th></tr>
      </table>
    </section>
    <section data-background-iframe="https://www.youtube.com/embed/umUuOIxoKEw?controls=0&amp;enablejsapi=1&amp;autoplay=1&amp;loop=1&amp;playlist=umUuOIxoKEw&amp;showinfo=0&amp;rel=0&amp;html5=1">
      <table style="height: 20%; margin-top: 65%; margin-left: -78px;">
        <tr><th>Joana Neto et al., Kampff Lab</th></tr>
      </table>
    </section>
    <section data-background-iframe="https://www.youtube.com/embed/mJDV07ptQFk?start=40&amp;controls=0&amp;enablejsapi=1&amp;autoplay=1&amp;showinfo=0&amp;rel=0&amp;html5=1">
      <table style="height: 20%; margin-top: 65%; margin-left: -78px;">
        <tr><th>George Dimitriadis, Kampff Lab</th></tr>
      </table>
    </section>
</section>

<section data-markdown data-separator="^\n---\n$" data-separator-vertical="^\n--\n$">
<script type="text/template">

#### Hardware synchronized acquisition & control
![Harp-Bonsai](../../assets/images/bonsai-harp.svg)

[harp-tech.org](https://harp-tech.org/)

</script>
</section>

<section>
  <h4>Next generation open ephys</h4>
  <img src="../../assets/images/nextgen-ephys.png" alt="ONI - Open Neuro Interface" width="500px" />
  <iframe src="https://www.youtube.com/embed/8xC404aTSUo?controls=0&amp;enablejsapi=1&amp;autoplay=1&amp;loop=1&amp;playlist=8xC404aTSUo&amp;showinfo=0&amp;rel=0&amp;html5=1" width="400px" height="300px"></iframe>
  <a href="https://open-ephys.github.io/onix-docs/">open-ephys.github.io/onix-docs</a>
  <p>Jon Newman et al. @ Open-Ephys</p>
</section>

<section>
  <h4>Interactive visual environments</h4>
  <img src="../../assets/images/bonsai-bonvision.svg" alt="BonVision" />
  <img src="https://bonvision.github.io/assets/Images/Demos/DemoAR_v3.gif" width="50%" alt="Augmented Reality in BonVision" />
  <a href="https://bonvision.github.io/">bonvision.github.io</a>
  <p>Saleem Lab and Solomon Lab</p>
</section>

<!-- Raw HTML for embedded iframe backgrounds -->
<section>
  <h4>Real-time markerless pose estimation</h4>
  <img src="../../assets/images/bonsai-dlc.svg" alt="Bonsai-DeepLabCut" />
  <iframe src="https://www.youtube.com/embed/0aachcS0CUY?controls=0&amp;enablejsapi=1&amp;autoplay=1&amp;loop=1&amp;playlist=0aachcS0CUY&amp;showinfo=0&amp;rel=0&amp;html5=1" width="500px" height="300px"></iframe>
  <a href="https://github.com/bonsai-rx/deeplabcut/">github.com/bonsai-rx/deeplabcut</a>
  <p>Mathis et al., Nat Neurosci, 2018</p>
</section>

<section>
  <h4>Multi-animal pose and identity tracking</h4>
  <img src="../../assets/images/bonsai-sleap.svg" alt="Bonsai-SLEAP" />
  <iframe src="https://www.youtube.com/embed/e3NDNKh_OoM?controls=0&amp;enablejsapi=1&amp;autoplay=1&amp;loop=1&amp;playlist=e3NDNKh_OoM&amp;showinfo=0&amp;rel=0&amp;html5=1" width="500px" height="300px"></iframe>
  <a href="https://bonsai-rx.org/sleap/">bonsai-rx.org/sleap</a>
  <p>Pereira et al., Nat Methods, 2022</p>
</section>

<section>
  <h4>Intelligent experimentation</h4>
  <img src="../../assets/images/bonsai-ml.svg" alt="Bonsai-ML" />
  <a href="https://bonsai-rx.org/machinelearning/">bonsai-rx.org/machinelearning</a>
</section>

<section data-markdown data-separator="^\n---\n$" data-separator-vertical="^\n--\n$">
<script type="text/template">

![Bonsai](../../assets/images/bonsai-lettering.svg)

### Questions?
[neurogears.org/esc-2025](https://neurogears.org/esc-2025)
<table style="width: 100%;">
  <tr>
    <th style="vertical-align: middle; width: 40%; height: 100px; padding-left: 180px">
      <img alt="NeuroGEARS" src="../../assets/images/neurogears.svg"/>
    </th>
    <th style="vertical-align: middle; width: 40%; height: 100px; padding-left: 80px; align: right">
      <img alt="ESC" src="../../assets/images/esc.png"/>
    </th>
  </tr>
</table>

</script>
</section>
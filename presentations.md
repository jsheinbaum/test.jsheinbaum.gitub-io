---
title: "Hello Shower"
author: "Julio"
output: rmdshower::shower_presentation
<script src="plugin/math/math.js"></script>
<script>
  Reveal.initialize({ plugins: [ RevealMath.KaTeX ] });
</script>
<section>
  <h2>The Lorenz Equations</h2>
  \[\begin{aligned}
  \dot{x} &amp; = \sigma(y-x) \\
  \dot{y} &amp; = \rho x - y - xz \\
  \dot{z} &amp; = -\beta z + xy
  \end{aligned} \]
</section>
---

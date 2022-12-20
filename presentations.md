---
title: "Hello"
author: "Julio"
layout: raw
---
Reveal.initialize({
  katex: {
    version: 'latest',
    delimiters: [
      {left: '$$', right: '$$', display: true},
      {left: '$', right: '$', display: false},
      {left: '\\(', right: '\\)', display: false},
      {left: '\\[', right: '\\]', display: true}
   ],
   ignoredTags: ['script', 'noscript', 'style', 'textarea', 'pre']
 },
 plugins: [ RevealMath.KaTeX ]
});

Reveal.initialize({
  katex: {
    local: 'node_modules/katex',
  },
  plugins: [ RevealMath.KaTeX ]
});


# The Equations

<section>
  <h2>The Lorenz Equations</h2>
  <section>
    
  <section>
  \[\begin{aligned}
  \dot{x} &amp; = \sigma(y-x) \\
  \dot{y} &amp; = \rho x - y - xz \\
  \dot{z} &amp; = -\beta z + xy
  \end{aligned} \]
   <section>

<section data-markdown>
  `$$ J(\theta_0,\theta_1) = \sum_{i=0} $$`
</section>

___  <!-- "___" Makes a basement slide -->

# Basement 1

Hey, you can still go down

```
test
```

___

# Basement 2

You're rock bottom!

--- <!-- "---" Makes the next slide -->

# Second slide

stuff

Note:
This will only display in the notes window.
---

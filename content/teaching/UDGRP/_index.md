---
title: "Geometric Group Theory"
draft: false
showDate: false
cardView: true
showSummary: false
groupbyYear: false
sharingLinks: [""]
showTableOfContents: false
herostyle: "background" # valid options: basic, big, background, thumbAndBackground
layoutBackgroundBlur: true # only used when heroStyle equals background or thumbAndBackground
layoutBackgroundHeaderSpace: false
showHero: true
showPagination: false
---
{{< katex >}} 

<html>
<head>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/KaTeX/0.7.1/katex.min.css">
    <script src="https://cdnjs.cloudflare.com/ajax/libs/KaTeX/0.7.1/katex.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/KaTeX/0.7.1/contrib/auto-render.min.js"></script>
</head>
<body>
    <script>
      renderMathInElement(
          document.body,
          {
              delimiters: [
                  {left: "$$", right: "$$", display: true},
                  {left: "\\[", right: "\\]", display: true},
                  {left: "$", right: "$", display: false},
                  {left: "\\(", right: "\\)", display: false}
              ]
          }
      );
    </script>
</body>
</html>

<a style= "font-family: 'Bebas'; color: white; font-size: 15pt">Welcome to the Undergraduate Directed Group Reading Program (UDGRP) 2024! This year, we will explore Geometric Group Theory (GGT). 

In the initial lectures, we’ll review basic group theory concepts and provide problem sets periodically. Please make a sincere effort to solve them, as this practice will prove invaluable in the long run. If you have any doubts, feel free to reach out to any of the instructors—we’re here to help!

To make things more engaging, we’ll introduce a "Chocolate Problem" at the end of each class. Anyone who provides a meaningful attempt—be it partial, intuitive, or without a rigorous proof—will be rewarded with chocolates! (Sadly, we can’t hand out Fields Medals, but hey, chocolates are a good start, right?)

Our goal with this approach is to encourage you to engage with the material actively. Mathematics is a discipline where simply knowing the theory isn’t enough—you must learn how to apply it effectively. And the best way to do so? Solve as many problems as possible!

You’ll find all the lecture notes and problem sets on this website. If you miss a lecture, don’t worry—we’ll keep everything updated here so you can catch up.



<center>
   <a style="font-family: 'Bebas'; font-variant: small-caps; color: white; font-size: 21pt"> Introductory Talk </a>
</center>

{{< timeline >}}

{{< timelineItem icon="" header="0. Introductory Talk" badge="10/19" subheader="Rinkiny Ghatak and Treanungkur Mal" >}}
   
   Rinkiny introduced the definition of a group with examples and discussed free groups. She examined the structure of Cayley graphs, particularly how they represent free groups, and concluded with the group presentation of the Lamplighter Group. <br><br>

   I demonstrated how complex group presentations, like the Lamplighter Group, can be understood using the analogy of street lamps. The intricate presentation reduces to switching finitely many lamps on an infinite street. I also briefly introduced group actions, as they will be central to our study.  
{{< /timelineItem >}}


{{< timelineItem icon="" header="1. Basics of Group Theory" badge="11/25" subheader="<b>Speaker</b>: Rinkiny Ghatak" >}}

     In this lecture, Rinkiny covered the basics of group theory, including:<br>
     - Definition of Group.<br>
     - Examples of Group \( (\mathbb{Z}, \mathbb{Z}/n\mathbb{Z}, \text{GL}_n(\mathbb{R}), \text{SL}_n(\mathbb{R}), S_n) \).<br>
     - Subgroups.<br>
     - Group Presentations (Generators and Relators).<br>
     - Structure-preserving maps in Groups (Homomorphism and Isomorphism).<br>
     - Normal Subgroups and Cosets.<br>
     - Kernel and Image of a Homomorphism.<br>
     - The 1st Isomorphism Theorem.<br><br>

     <b>Lecture Notes</b>: <a href="https://github.com/maltreanungkur/web/raw/main/documents/GGT_Lec1.pdf">Download</a><br>
     <b>Introductory Slides</b>: <a href="https://github.com/maltreanungkur/web/raw/main/documents/Intro.pdf">Download</a><br>
     <b>Problem Set</b>: <a href="https://raw.githubusercontent.com/maltreanungkur/web/main/documents/GGT_P1.pdf">Download</a><br>
     <b>Chocolate Problem's Solution</b> (by Nikhil Nagaria): <a href="https://raw.githubusercontent.com/maltreanungkur/web/main/documents/Nikhil.pdf">Download</a><br><br>

     <b>Correct Submissions to the Chocolate Problem</b> (Lexicographical Order):<br>
     Arkaprovo Das, Daibik Barik, Nikhil Nagaria, Payal Rajora, Ramdas Singh, Sai Prabhav, Sarvesh Soni, Shankha Suvra Dam.<br>

{{< /timelineItem >}}


{{< timelineItem icon="" header="2. Group Actions and Their Applications" badge="11/29" subheader="<b>Speaker</b>: Treanungkur Mal" >}}

     In this lecture, I have covered the idea of group action and solved some problems using group action, including:<br>
     - Recap of Previous Class.<br>
     - Idea of Quotienting Groups.<br>
     - Applications of the 1st Isomorphism Theorem.<br>
     - Motivation for Group Action.<br>
     - Definition of Group Action.<br>
     - Some Valid Group Actions.<br>
     - Definition of Orbits and Stabilizer.<br>
     - The Orbit Stabilizer Theorem.<br>
     - Cayley's Theorem (Only Statement).<br>
     - Some examples of group action \( \left( \mathrm{SO}(2, \mathbb{R}) \text{ acts on } \mathbb{R}^2 \right) \).<br><br>

     <b>Lecture Video</b>: <a href="https://drive.google.com/file/d/15HMkkSBmOjMMYW94HgiuHWbCY3PVhSSD/view?usp=sharing">View</a><br>
     <b>Lecture Notes</b>: <a href="https://github.com/maltreanungkur/web/raw/main/documents/GGT_Lec2.pdf">Download</a><br>
     <b>Problem Set</b>: <a href="https://raw.githubusercontent.com/maltreanungkur/web/main/documents/GGT_P2.pdf">Download</a><br>
     <b>Chocolate Problem's Solution</b> (by Sai Prabhav): <a href="https://raw.githubusercontent.com/maltreanungkur/web/main/documents/SaiP.pdf">Download</a><br><br>

     <b>Correct Submissions to the Chocolate Problem</b> (Lexicographical Order):<br>
     Arkaprovo Das, Daibik Barik, Nikhil Nagaria, Sai Prabhav, Sarvesh Soni.<br>

{{< /timelineItem >}}


{{< timelineItem icon="" header="3. Introduction to GGT" badge="12/6" subheader="<b>Speaker</b>: Treanungkur Mal" >}}

     In this lecture, I covered the following topics and proved some theorems including:<br>
     - Basic notions of graph theory.<br>
     - Generating sets of a group and group presentations.<br>
     - Cayley graphs with respect to generating sets.<br>
     - Definition of Free groups.<br>
     - Group Action on Trees \( \left(\mathbb{F}_2 \text{ acts on } \Gamma(G, S) \right) \).<br>
     - Review of group actions and the induced homomorphism.<br>
     - Types of group actions, focusing on isometric actions on metric spaces.<br>
     - Isometric and free group actions on \( \mathbb{R}^n \Rightarrow \) torsion-free.<br>
     - Brief Idea for the proof of Nielsen–Schreier Theorem.<br><br>

     <b>Lecture Video</b>: <a href="https://drive.google.com/file/d/1kk1QPkq3g1NJeBzjdx2nwxBRt253eypG/view?usp=sharing">View</a><br>
     <b>Lecture Notes</b>: <a href="https://github.com/maltreanungkur/web/raw/main/documents/GGT_Lec3.pdf">Download</a><br>
     <b>Problem Set</b>: <a href="https://raw.githubusercontent.com/maltreanungkur/web/main/documents/GGT_P3.pdf">Download</a><br>

{{< /timelineItem >}}


{{< timelineItem icon="" header="4. First Properties of I.H. and I.H for Quasi projective Varites" badge="09/02" subheader="Trishan Mondal" >}}
    Notes by me - <a href="./notes/talk5.pdf">Lecture 4</a>.<br>
      In this talk, we will discuss the homological properties of intersection homology like pushforward maps, excision and Mayer-Vietoris. We will compute the intersection homology of cones. We then discuss Whitney stratifications for complex quasi-projective varieties and the associated pseudomanifold structure on their underlying topological space. We will conclude with a discussion of Poincaré duality, Lefschetz hyperplane and hard Lefschetz theorems in the context of intersection homology.
{{< /timelineItem >}}

{{< timelineItem icon="" header="5. \(L^2\)- Cohomology and Intersection Cohomology." badge="16/02" subheader="Aaratrick Basu" >}}
    Notes by Aaratrick - <a href="./notes/lec-5.pdf">Lecture 5</a>.<br>
    We introduce \(L^2\)-cohomology of smooth manifolds with riemannian metric, which is closely related to de Rham cohomology. We will then discuss strong Hodge theorem and a conjecture of Cheeger about intersection cohomology and \(L^2\)-cohomology. In the case of complex projective varieties with simple singularities, we show that \(L^2\)-cohomology does coincide with its intersection cohomology. If time permits, we will discuss the relation between the \(L^2\)-cohomology of a locally symmetric space and the intersection cohomology of its Baily-Borel compactification.
{{< /timelineItem >}}

{{< timelineItem icon="" header="6. Sheaf theoretic Intersection homology" badge="24/02" subheader="Jishnu Biswas" >}}
    In this talk, we sheafify the construction of the intersection homology we have seen so far by showing that it can be computed as the homology group of a certain complex of sheaves. As a consequence, it is shown that intersection homology is a topological invariant of a pseudomanifold, i.e, it does not depend on the choice of a stratification. This is done using Deligne's construction which given any stratification associates to a complex of sheaves, a new complex of sheaves. This construction is then applied to the complex computing intersection homology for the canonical (coarsest) stratification to derive the independence of stratification.
{{< /timelineItem >}}

{{< timelineItem icon="" header="7. Continuation" badge="01/03" subheader="Jishnu Biswas,Trishan Mondal" >}}
In this talk we will first look into The Kähler package, then we will get back proving the fact Intersection homology sheaf is invariant of stratification.
{{< /timelineItem >}}

{{< timelineItem icon="" header="8. Perverse sheaves" badge="08/03" subheader="Animesh Renanse" >}}
 Notes by Animesh - <a href="./notes/lecture8.pdf">Lecture 5</a>.<br>
 Let X be an n-pseudomanifold. In the last two talks, we constructed the simplicial intersection complex of sheaves over X and showed that its hypercohomology is the intersection homology. Furthermore, it is completely characterized in the derived category by a list of axioms. Continuing with this, we will see that these axioms ensure that this complex is a perverse sheaf with a twist. We will see that the category of perverse sheaves enjoys special properties in the derived category; it is abelian and is closed under Verdier duality. Thinking of perverse sheaves as an enlargement of intersection homology with local coefficients, we will see that every perverse sheaf can be “approximated” by finitely many of them; that is, the category of perverse sheaves is artinian. We will end with some more remarks and examples from complex varieties.
{{< /timelineItem >}}

{{< timelineItem icon="" header="8. Nearby and Vanishing cycle" badge="15/03" subheader="Raushon toor nair" >}}
     We define nearby and vanishing cycles functors, associated with a function \(f: \mathbb{C}^n \to \mathbb{C}\), from the bounded derived category of constructible sheaves on \(\mathbb{C}^n\) to those on the special fiber of 0 of the function \(f\). We will then discuss the Beilinson-Bernstein-Deligne-Gabber decomposition theorem for intersection homology.
{{< /timelineItem >}}


{{< timelineItem icon="" header="9,10. Weil's conjecture for the singular case" badge="05/04, 12/04" subheader="Kannappan Sampath" >}}
     We will introduce Weil's zeta function of a smooth projective variety over finite fields and Weil's conjectures about them. We will then explain how one could deduce these conjectures from a reasonable cohomology theory; we will then explain that such a cohomology theory with coefficients in \(\mathbb{Q}_p\) that is functorial for morphisms between smooth projective varieties cannot exist. We will then mention that \(\ell\)-adic etale cohomology (with ell not equal to p) is a Weil-cohomology theory. We will end by computing the "naive" zeta function of some explicit examples of singular varieties.
{{< /timelineItem >}}


{{< /timeline >}}

<center>
   <a style= "font-family: 'Bebas'; font-variant: small-caps; color: white; font-size: 21pt"> References</a>
</center>

- <a style= "font-family: 'Bebas'; font-variant: small-caps; color: white; font-size: 14pt"> Main Text :</a> F. Kirwan, J. Woolf, *An introduction to intersection homology theory* [CRC Press, 2006] - [Pdf](./documents/Frances%20Kirwan,%20Jonathan%20Woolf.pdf)
- <a style= "font-family: 'Bebas'; font-variant: small-caps; color: white; font-size: 14pt"> Furthers :</a> 
  
     1. L. G. Maxim, Intersection Homology & Perverse Sheaves - [Pdf](./documents/Laurenţiu%20G.%20Maxim%20.pdf).
     2. M. Goresky, R. MacPherson, Stratified Morse theory - [Pdf](./documents/Stratified%20Morse%20Theory.pdf).
     3. A. Dimca, Sheaves in topology - [Pdf](./documents/(Universitext)%20Alexandru%20Dimca.pdf).
     4. A. Borel, Intersection cohomology - [Pdf](./documents/(Progress%20in%20Mathematics%2050)%20Armand%20Borel%20(auth.)%20.pdf).
     5. V. Pati. Notes on intersection homology - [Pdf](./documents/Intersection%20homology(pati).pdf).

<center>
   <a style= "font-family: 'Bebas'; font-variant: small-caps; color: white; font-size: 21pt">Other links</a>
</center>


- <a style= "font-family: 'Bebas'; color: white; font-size: 14pt">Web page :</a> of [Charanya Ravi](https://charanyaravi.github.io/Sem2-23-24/Sem2-23-24:IH:index.html) related to this seminar.
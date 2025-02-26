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


{{< timelineItem icon="" header="1. Basics of Group Theory" badge="11/25" subheader="Speaker: Rinkiny Ghatak" >}}

     In this lecture, Rinkiny covered the basics of group theory, including:<br>
     - Definition of Group.<br>
     - Examples of Group \( (\mathbb{Z}, \mathbb{Z}/n\mathbb{Z}, \text{GL}_n(\mathbb{R}), \text{SL}_n(\mathbb{R}), S_n) \).
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


{{< timelineItem icon="" header="2. Group Actions and Their Applications" badge="11/29" subheader="Speaker: Treanungkur Mal" >}}

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


{{< timelineItem icon="" header="3. Introduction to GGT" badge="12/6" subheader="Speaker: Treanungkur Mal" >}}

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


{{< timelineItem icon="" header="4. Quasi-Isometry in GGT" badge="12/12" subheader="Speaker: Rinkiny Ghatak" >}}

     In this lecture, Rinkiny covered the following topics:<br>
     - Recalled the idea of the proof of Nielsen–Schreier Theorem.<br>
     - Basic notions of metric spaces.<br>
     - Path Metric on Groups.<br>
     - Motivation and Definition of Quasi-Isometry.<br>
     - Some Basic Examples and Proposition related to Quasi-Isometry.<br>
     - Proof of \( \mathbb{R} \) and \( \mathbb{Z} \) being quasi-isometric.<br><br>

     <b>Lecture Video</b>: <a href="https://drive.google.com/file/d/1l94EGwxxLWOdbs-V2hoBAZ6g906iHypS/view?usp=sharing">View</a><br>
     <b>Lecture Notes</b>: <a href="https://github.com/maltreanungkur/web/raw/main/documents/GGT_Lec4.pdf">Download</a><br>
     <b>Problem Set</b>: <a href="https://raw.githubusercontent.com/maltreanungkur/web/main/documents/GGT_P4.pdf">Download</a><br>
{{< /timelineItem >}}

{{< timelineItem icon="" header="5. Problem Solving Session (PSS)" badge="12/13" subheader="Speaker: Treanungkur Mal" >}}

     In this lecture, I did some problem-solving on group actions and discussed some ideas frequently used:<br>
     - Identifying different quotient groups intuitively.<br>
     - Formalizing different quotienting ideas using Isomorphism Theorems.<br>
     - Quotienting on \( \mathbb{R}^2 \), while seeing it as a two-dimensional vector space.<br>
     - Some examples of proofs based on group actions like: Cayley's Theorem, Group Action on Automorphism Groups of Certain Cayley Graphs, etc.<br><br>

     <b>Lecture Video</b>: <a href="https://drive.google.com/file/d/1nkEFXV6pAxiCvuRYH6_eG4pTfTLnn5C7/view?usp=sharing">View</a><br>
     <b>Lecture Notes</b>: <a href="https://github.com/maltreanungkur/web/raw/main/documents/GGT_Lec5.pdf">Download</a><br>
     <b>Problem Set</b>: <a href="https://raw.githubusercontent.com/maltreanungkur/web/main/documents/GGT_P5.pdf">Download</a><br>
{{< /timelineItem >}}

{{< timelineItem icon="" header="6. Quasi-Isometry and Growth Functions" badge="12/16" subheader="Speaker: Rinkiny Ghatak" >}}

     In this lecture, Rinkiny covered the following topics:<br>
     - Defined QI(X) and proved that it forms the Quasi-isometry group.<br>
     - Proved quasi-isometry of groups with different generating sets and related results.<br>
     - Discussed relevant examples and additional properties.<br>
     - Established the definition, examples, and equivalence of growth functions.<br><br>

     <b>Lecture Video</b>: <a href="https://drive.google.com/file/d/1bCddzmznVKxXGA_iLL2bLxLrD_hDqzUr/view?usp=sharing">View</a><br>
     <b>Lecture Notes</b>: <a href="https://github.com/maltreanungkur/web/raw/main/documents/GGT_Lec6.pdf">Download</a><br>
     <b>Problem Set</b>: <a href="https://raw.githubusercontent.com/maltreanungkur/web/main/documents/GGT_P6.pdf">Download</a><br>
{{< /timelineItem >}}

{{< timelineItem icon="" header="7. Free Groups and the Nielsen–Schreier Theorem" badge="12/20" subheader="Speaker: Treanungkur Mal" >}}

     In this lecture, I covered the following topics:<br>
     - Group presentations, relators, and generators.<br>
     - Some discussion on the Andrew–Curtis Conjecture.<br>
     - Barycentric subdivision of Cayley graph of a group.<br>
     - Tiling the Cayley graph of a given group.<br>
     - Finding a "nice" tiling for \( \mathbb{F}_2 \) (also discussed how to handle the general case!).<br>
     - Proving the Nielsen–Schreier Theorem using group action on trees.<br><br>

     <b>Lecture Video</b>: <a href="https://drive.google.com/file/d/1YBqTe-ti4BcFMRfwXfJ3bmSPuVSqMRyn/view?usp=sharing">View</a><br>
     <b>Lecture Notes</b>: <a href="https://github.com/maltreanungkur/web/raw/main/documents/GGT_Lec7.pdf">Download</a><br>
     <b>Problem Set</b>: <a href="https://raw.githubusercontent.com/maltreanungkur/web/main/documents/GGT_P7.pdf">Download</a><br>
{{< /timelineItem >}}

{{< timelineItem icon="" header="8. Quasi-Isometric Embedding of Groups" badge="12/23" subheader="Speaker: Rinkiny Ghatak" >}}

     In this lecture, Rinkiny covered the following topics:<br>
     - Basics of growth functions.<br>
     - Quasi-isometric embedding of groups.<br>
     - Briefing on the end of UDGRP presentation topics.<br><br>

     <b>Lecture Video</b>: <a href="https://drive.google.com/file/d/1Da5TxMBAeMhojxqVU4fNGJHJHOYH-J9y/view?usp=sharing">View</a><br>
     <b>Lecture Notes</b>: <a href="https://github.com/maltreanungkur/web/raw/main/documents/GGT_Lec8.pdf">Download</a><br>
     <b>Problem Set</b>: <a href="https://raw.githubusercontent.com/maltreanungkur/web/main/documents/GGT_P8.pdf">Download</a><br>
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
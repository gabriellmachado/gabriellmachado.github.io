---
title: Animando background
date: 2017-01-02 21:37:00 Z
layout: post
---

<h4><b>Prepara o capacete que la vem mais pedrada</b></h4>
<h4>Então vamos começar a animar</h4>

<pre>
 body {
   background: linear-gradient(270deg, #ecd078, #d95b43, #c02942, #542437, #53777a);
   background-size: 1000% 1000%;
   -webkit-animation: AnimationName 30s ease infinite;
   -moz-animation: AnimationName 30s ease infinite;
   animation: AnimationName 30s ease infinite;
 }
 
 @-webkit-keyframes AnimationName {
   0% {
     background-position: 0% 50%
   }
   50% {
     background-position: 100% 50%
   }
   100% {
     background-position: 0% 50%
   }
 }
 
 @-moz-keyframes AnimationName {
   0% {
     background-position: 0% 50%
   }
   50% {
     background-position: 100% 50%
   }
   100% {
     background-position: 0% 50%
   }
 }
 
 @keyframes AnimationName {
   0% {
     background-position: 0% 50%
   }
   50% {
     background-position: 100% 50%
   }
   100% {
     background-position: 0% 50%
   }
 }
</pre>
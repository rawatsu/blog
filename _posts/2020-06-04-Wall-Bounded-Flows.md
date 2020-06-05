---
layout: post
title: Turbulence in wall bounded flows
categories: Turbulence Fluid-Dynamics Dynamical-system
usemathjax: true
---

Turbulence phenomenon is one of the most challenging research areas in fluid dynamics. Even after decades of dedicated investigation, it remains as evasive as ever.  It affects weather, climate change, irrigation systems, fuel consumption, construction of bridges, artificial heart, vacuum cleaners, washing machines, and rocket propulsion.  

Turbulence is often cited as 

> “the last great unsolved problem of classical physics.”

So what makes turbulence so complicated? Some of the complexity arises from the wide range of length and time scale of the [*coherent structures*](#near-wall-structures)  interacting with each other. Turbulence phenomenon becomes increasingly complex in the presence of a wall. Wall introduces new length scales and changes the nature of turbulence. Turbulence structures closest to the wall are smallest, and as we move away from the wall, they scale according to this distance. 

Resolving small scale turbulent structures demands very high mesh count or data points. That is why in industries, turbulence is generally modelled rather than resolved with *Reynolds-Average-Navier-Stokes equations* (**RANS**). New CFD practitioners are often confused about the mesh resolution they should choose especially close to the wall. It takes many years of practice and a lot of trails to get the mesh resolution correct.  Its often said that creating a good mesh is as much an art as a science. 

In this blog post and its successors, we will develop a physical understanding of near-wall turbulence and give an intuitive approach to resolve near-wall turbulence structures. 



## Near-Wall turbulence

&nbsp;

<img class="side_by_side" src="{{ site.baseurl}}/assets/Kline2.jpg" title="Kline near-wall experiment" width="250px" align="left" hspace="20" /><img class="side_by_side" src="{{ site.baseurl}}/assets/Kline2.jpg" title="Kline near-wall experiment" width="250px" margin-left="20px" />



<table>
  <thead>
    <tr>
      <th><img src="{{ site.baseurl}}/assets/Kline2.jpg" title="Kline near-wall experiment" style="width:200px" /></th>
      <th><img src="{{ site.baseurl}}/assets/Kline2.jpg" title="Kline near-wall experiment" style="width:200px"/></th>
    </tr>
  </thead>

</table>

<style>
  .side-by-side>img{
    width:200px;
    padding-right: 10px;
}
</style>



![]({{ site.baseurl}}/assets/Kline2.jpg){: width=200px style="float:left; padding:16px"}![]({{ site.baseurl}}/assets/Kline2.jpg){: width=200px style="float:left; padding:16px"}





&nbsp;


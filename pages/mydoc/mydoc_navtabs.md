---
title:  Navtabs
tags: [formatting]
keywords: navigation tabs, hide sections, tabbers, interface tabs
last_updated: Dec 11, 2023
summary: " "
sidebar: mydoc_sidebar
permalink: mydoc_navtabs.html
folder: mydoc
---



## Navtabs demo

The following is a demo of a navtab. 

<ul id="profileTabs" class="nav nav-tabs">
    <li class="active"><a class="noCrossRef" href="#profile" data-toggle="tab">AWS</a></li>
    <li><a class="noCrossRef" href="#about" data-toggle="tab">Azure</a></li>
    <li><a class="noCrossRef" href="#match" data-toggle="tab">GPC</a></li>
</ul>
  <div class="tab-content">
<div role="tabpanel" class="tab-pane active" id="profile" markdown="1">
Hello 

1.  Step 1
2.  Step 2. 
    * Step 2.1 
    * Step 2.2 

> Content.
</div>

<div role="tabpanel" class="tab-pane" id="about">
    <p>Insert content here.</p></div>

<div role="tabpanel" class="tab-pane" id="match">
    <p>Insert content here.</p>
</div>
</div>

#
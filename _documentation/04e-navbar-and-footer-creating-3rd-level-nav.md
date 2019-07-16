---
title: Creating 3rd level nav for your content
permalink: /documentation/navbar-and-footer/creating-3rd-level-nav/
third_nav_title: "Navbar and Footer"
---

> IMPORTANT: 3rd level navigations will only appear in the left-navigation.

To create a 3rd level navigation, create a new page and add the parameter **second_nav_title** in the main header of the page. 

The **second_nav_title** corresponds to the 2nd level navigation and the **title** will be the title of the page. 

In the example below, "Github Repository" tells isomer that this page belongs to the Github Repository **second-level navigation** while the page **title** is "Overview".

<pre>
---
<b>title: Overview</b>
permalink: /github-repository/overview/
breadcrumb: Github Repository - Overview
<b>second_nav_title: "Github Repository"</b>
---
</pre>

![3rd level navigation appearance](/images/resources/3rd-nav-appearance.png)

The file will following the naming convention of **[number][alphabet]-[filename].md**. For example:
* *1a-who-we-are.md*
* *1b-organisation-structure.md*
* *1c-contact-us.md*

The number will group the navigation together while the alphabet will determine the order of the pages.





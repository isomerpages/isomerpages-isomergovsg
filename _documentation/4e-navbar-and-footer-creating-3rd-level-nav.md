---
layout: leftnav-page-content
title: Creating 3rd level nav for your content
permalink: /navbar-and-footer/creating-3rd-level-nav/
breadcrumb: Navbar and Footer - Creating 3rd level nav
collection_name: documentation
second_nav_title: "Navbar and Footer"
---

> IMPORTANT: 3rd level navigation cannot be added to the header navigation. Instead the creation of 3rd level navigations will level on the left navigation of the 2nd level content
![3rd level navigation appearance](/images/resources/3rd-nav-appearance.png)

To create a 3rd level navigation, create a new page and add the parameter second_nav_title in the main header of the page. The second_nav_title corresponds to the 2nd level navigation and the title will be the title of the page. In the example below, "Github Repository" tells isomer this page belongs to the Github Repository navigation while the page title is "Overview"
<pre>
---
layout: leftnav-page-content
title: Overview
permalink: /github-repository/overview/
breadcrumb: Github Repository - Overview
collection_name: documentation
<b>second_nav_title: "Github Repository"</b>
---
</pre>
![3rd level navigation appearance](/images/resources/3rd-nav-appearance.png)


The creation of the page will follow the naming convention of <number><alphabet>-<filename>.md
Navigation items under the same group will share the same number. The order of the navigation follows the alphabetic order.


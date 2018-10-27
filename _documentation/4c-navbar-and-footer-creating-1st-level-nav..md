---
layout: leftnav-page-content
title: Creating 1st level nav to your navbar
permalink: /navbar-and-footer/creating-1st-level-nav/
breadcrumb: Navbar and Footer - Creating 1st level nav
collection_name: documentation
second_nav_title: "Navbar and Footer"
---
#### **Step-by-step guide to create 1st level nav on your navbar**
![Adding first level nav](/images/resources/adding-first-level-item-to-your-navigation-bar.gif)
> Note: Be very careful with the spacing in the navigation.yml file. Your website will break if the spacing are incorrect

* Select your "Staging" Branch
* In your repository, go to "_data" folder
* Edit navigation.yml file
* Copy the code snippet below into navigation.yml
* State the permalink of your target simple page under url. To create a simple page, refer [here](/webpage/creating-a-new-simple-page/){:target="_blank"} 
* Click on "Commit changes" button

```
# Sample code snippet for you to create a 1st level nav. Replace url with your simple page permalink

- title: Who We Are
  url: /who-we-are/
  
# Sample code snippet for you to create a 1st level nav linking to external websites

- title: Who We Are
  url: https://govtech.taleo.net/careersection/govtech_external/jobsearch.ftl
  external: true
```
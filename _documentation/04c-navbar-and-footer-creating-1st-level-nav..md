---
title: Creating 1st level nav for your navbar
permalink: /documentation/navbar-and-footer/creating-1st-level-nav/
third_nav_title: "Navbar and Footer"
---
#### **Step-by-step guide to create 1st level nav on your navbar**
![Adding first level nav](/images/resources/adding-first-level-item-to-your-navigation-bar.gif)
> Note: Be very careful with the spacing in the navigation.yml file. Your website will break if the spacing are incorrect

1. Select your "Staging" Branch
2. In your repository, go to "_data" folder
3. Edit navigation.yml file
4. Copy the code snippet below into navigation.yml
5. Change the url to your target page permalink
6. Click on "Commit changes" button

```
# Sample code snippet for you to create a 1st level nav. Replace url with your simple page permalink

- title: Who We Are
  url: /who-we-are/
  
# Sample code snippet for you to create a 1st level nav linking to external websites

- title: Who We Are
  url: https://govtech.taleo.net/careersection/govtech_external/jobsearch.ftl
  external: true
```

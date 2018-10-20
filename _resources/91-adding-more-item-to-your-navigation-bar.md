---
layout: leftnav-page-content
title: Adding first level item to your navigation bar
permalink: /adding-first-level-item-to-your-navigation-bar/
breadcrumb: Adding first level item to your navigation bar
collection_name: resources
---

#### **Step-by-step guide**
* Select your "Staging" Branch
* In your repository, go to "_data" folder
* Edit navigation.yml file
* Copy the code snippet below into the .yml file
* Click on "Commit changes" button

<font color="red"><b>* Be very careful with the spacing in the navigation.yml file. Your website will break if the spacing are incorrect</b></font>
```
# Code snippet for reference

# For link to within the website
- title: Students and Graduates
  url: /careers/students-and-graduates/

# For link to external website
- title: Apply Now
  url: https://govtech.taleo.net/careersection/govtech_external/jobsearch.ftl
  external: true
```

#### **Demo**
![Adding first level item to your navigation bar](/images/resources/adding-first-level-item-to-your-navigation-bar.gif)

---
layout: leftnav-page-content
title: Changing Content for your Navigation Bar
permalink: /changing-content-for-your-navigation-bar/
breadcrumb: Changing Content for your Navigation Bar
collection_name: resources
---

#### **Step-by-step guide**
* Select your "Staging" Branch
* In your repository, go to "_data" folder
* Edit navigation.yml file
* Change the content by amending the section below inside the file
* Click on "Commit changes" button

<font color="red"><b>* Be very careful with the spacing in the navigation.yml file. Your website will break if the spacing are incorrect</b></font>
```

- title: Who We Are
  url: /who-we-are/
- title: Digital Gov Transformation
  url: /digital-government-transformation/
  sub-links:
  - title: Overview
    url: /digital-government-transformation/
  - title: Digital Government Blueprint
    url: /digital-government-blueprint/
- title: Contact Us
  url: /contact-us/
```

#### **Demo**
![Changing Text for your Navigation Bar](/images/resources/changing-content-for-your-navigation-bar.gif)

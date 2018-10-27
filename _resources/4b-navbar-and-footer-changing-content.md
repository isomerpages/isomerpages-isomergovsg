---
layout: leftnav-page-content
title: Changing text for your navbar
permalink: /navbar-and-footer/changing-content/
breadcrumb: Navbar and Footer - Changing text
collection_name: resources
second_nav_title: "Navbar and Footer"
---
#### **Step-by-step guide to change text for your navbar**
![Changing text for your navbar](/images/resources/changing-content-for-your-navigation-bar.gif)
> Note: Be very careful with the spacing in the navigation.yml file. Your website will break if the spacing are incorrect

* Select your "Staging" Branch
* In your repository, go to "_data" folder
* Edit navigation.yml file
* Change the content by amending the section below inside navigation.yml
* Click on "Commit changes" button

```
# Sample navigation.yml file section for reference

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

---
layout: leftnav-page-content
title: Changing key highlight in your homepage
permalink: /homepage/changing-key-highlight/
breadcrumb: Homepage - Changing key highlight
collection_name: documentation
second_nav_title: "Homepage"
---
#### **Step-by-step guide to change key highlight in your homepage**
![Changing favicon of your homepage](/images/resources/changing-content-of-your-homepage.gif)
> Note: Be very careful with the spacing in the homepage.yml file. Your website will break if the spacing are incorrect

* Select your "Staging" Branch
* In your repository, go to "_data" folder
* Edit homepage.yml file
* Change your key highlight content, sequence by amending the section below inside homepage.yml
* Click on "Commit changes" button

```
# Sample homepage.yml file section for reference

# Key Highlights
# Setting [external: true] will open the url in a new window
key-highlights:
  - title: STRATEGIC NATIONAL PROJECTS
    url: /media/media-releases/strategic-national-projects-to-build-a-smart-nation
    external: true
  - title: DIGITAL GOVERNMENT BLUEPRINT
    description: To create a Government that is “Digital to the Core, and Serves with Heart
    url: /digital-government-blueprint/

```

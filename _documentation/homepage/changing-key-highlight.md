---
title: Changing key highlight
permalink: /documentation/homepage/changing-key-highlight/
third_nav_title: "Homepage"
---
#### **Step-by-step guide to change key highlight in your homepage**
![Changing favicon of your homepage](/images/resources/changing-content-of-your-homepage.gif)
> Note: Be very careful with the spacing in the homepage.yml file. Your website will break if the spacing are incorrect

1. Select your "Staging" Branch
2. In your repository, go to "_data" folder
3. Edit homepage.yml file
4. Change your key highlight content, sequence by amending the section below inside homepage.yml
5. Click on "Commit changes" button

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

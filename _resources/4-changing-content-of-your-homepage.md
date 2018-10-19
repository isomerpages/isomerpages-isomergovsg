---
layout: leftnav-page-content
title: Changing Content of Your Homepage 
permalink: /changing-content-of-your-homepage/
breadcrumb: Changing Content of Your Homepage 
collection_name: resources
---

### **Step-by-step guide to change the text, logo, image for your homepage**
1. Select your "Staging" Branch
2. In your repository, go to "_data" folder
3. Edit homepage.yml file
4. Change the text, logo, image by amending the section shown below
5. Click on "Commit changes" button

***WARNING: BE VERY CAREFUL WITH THE SPACING IN THE YML FILE. YOUR WEBSITE WILL BREAK IF THE SPACING ARE INCORRECT***

```
# code block
# Agency logo
agency-logo: /images/isomer-logo.svg

# Hero Banner
hero-title: Bioethics Advisory Committee Singapore
hero-subtitle: Examining ethical, legal, and social issues in human biomedical research
hero-banner: /images/Background_Logo.png

#Call to Action Button
button:
  - text: Learn More
    url: /who-we-are/overview/
    
key-highlights:
  - title: What We Do
    description: More information here
    url: /who-we-are/what-we-do/
  - title: Reports
    description: More information here
    url: /publications/reports/
  - title: Consultation Papers
    description: More information here
    url: /publications/consultation-papers/
  - title: Current Projects
    description: More information here
    url: /activities/current-projects

resources-title: Publications
resources-subtitle: Be in the know
resources-more-button: More Publications
resources-more-button-url: publications/

```

![Changing Content of Your Homepage](/images/resources/changing-content-of-your-homepage.gif)

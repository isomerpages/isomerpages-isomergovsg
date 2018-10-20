---
layout: leftnav-page-content
title: Changing text, url, logo or image for your homepage 
permalink: /changing-text-url-logo-image-for-your-homepage/
breadcrumb: Changing text, url, logo or image for your homepage 
collection_name: resources
---

#### **Step-by-step guide**
* Select your "Staging" Branch
* In your repository, go to "_data" folder
* Edit homepage.yml file
* Change the text, logo, image by amending the section below inside the file
* Click on "Commit changes" button

<font color="red"><b>* Be very careful with the spacing in the homepage.yml file. Your website will break if the spacing are incorrect</b></font>
```
# Sample homepage.yml file section for reference

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

#### **Demo**
![Changing Content of Your Homepage](/images/resources/changing-content-of-your-homepage.gif)

---
layout: leftnav-page-content
title: Changing Content for your Homepage 
permalink: /changing-content-for-your-homepage/
breadcrumb: Changing Content for your Homepage 
collection_name: resources
---
#### **Homepage**
Each Isomer website has a Homepage

![Homepage](/images/resources/homepage.PNG)

Homepage template can be configured as follow:
- The call to action can either be configured as a button, drop-down option
- Navigation bar item content is limited by the amount of spaces in the section
- For key features, we recommend keeping it within 3 to 4 options

---

#### **Step-by-step guide to change content for your Homepage**
![Changing Content of Your Homepage](/images/resources/changing-content-of-your-homepage.gif)

* Select your "Staging" Branch
* In your repository, go to "_data" folder
* Edit homepage.yml file
* Change the text, logo, image by amending the section below inside homepage.yml
* Click on "Commit changes" button

###### **Note: Be very careful with the spacing in the homepage.yml file. Your website will break if the spacing are incorrect**

```
# Sample homepage.yml file section for reference

# Favicon
favicon: /images/favicon-govtech.ico

# Agency logo
agency-logo: /images/govtech.gif

# Hero Banner
hero-title: Empowering our nation through technology
hero-subtitle: From transforming the delivery of Government Digital Services to building Smart Nation Infrastructure
hero-banner: /images/banner_GovTech.png

#Call to Action Button
button:
  - text: Learn More
    url: /who-we-are/our-role/

# Key Highlights
key-highlights:
  - title: STRATEGIC NATIONAL PROJECTS
    description: Singapore's five Smart Nation Strategic National Project
    url: /media/media-releases/strategic-national-projects-to-build-a-smart-nation
    external: true
  - title: DIGITAL GOVERNMENT BLUEPRINT
    description: To create a Government that is “Digital to the Core, and Serves with Heart
    url: /digital-government-blueprint/
  - title: GET INVOLVED
    description: Engagement and co-creation with citizens and businesses
    url: /get-involved/
  - title: SMART NATION <br> SCHOLARSHIP
    description: Unleash your passion and potential with us
    url: /careers/students-and-graduates/
    external: true

# Programmes Section
# To edit the programme details, go to programmes.yml
programmes-title: Products and Services
programmes-subtitle: Co-creating for better value
programmes-description: Using technology to make an impact, inspire change.
programmes-more-button: More Products and Services
programmes-more-button-url: /products-and-services/

# Resources Section
resources-title: Media
resources-subtitle: Be in the know
resources-more-button: More Media
resources-more-button-url: /media/

# Careers Section
# To edit the careers details, go to careers-stories.yml
careers-title: Careers
careers-subtitle: Be part of the digital transformation
careers-description: We harness the transformative power of technology to deliver user-centric services for Singapore and Singaporeans.
careers-more-button: Explore Opportunities
careers-more-button-url: /careers/why-govtech/
```



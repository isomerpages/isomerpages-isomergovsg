---
layout: leftnav-page-content
title: Changing colors for your website
permalink: /changing-colors-for-your-website/
breadcrumb: Changing colors for your website
collection_name: resources
---

#### **Website Colors**

Each Isomer website has two main colors, a primary color and a secondary color.

![Image showing where the primary and secondary colors show up](/images/resources/website_colors.PNG)

The **primary** color is displayed in the following elements:
* the notifications banner in the homepage
* the hero banner button in the homepage
* font colors for headers
* underlined and highlighted text colors

The **secondary** color is displayed in the following elements:
* the key highlights buttons in the homepage
* the page banner in the inner website pages (all except the homepage)

---

#### **Step-by-step guide to change color for your website**

![GIF of How to Change the Colors for Your Website](/images/resources/website-color-change.gif)

1. Select your "Staging" Branch in the repository's main page
2. Go into the "misc" folder
3. Edit the custom.scss file
4. Change the color of your website by amending the section below inside the file
5. Click on "Commit changes" button to save

<br> 
```
# Sample custom.scss file section for reference

// Website brand colors
$primary: #6031b6;
$secondary: #4372d6;
$secondary-hover: darken(#4372d6, 20%);
```

##### Note: If you are picking a new primary or secondary color for your Isomer website, please ensure that the color fulfills the minimum color contrast ratio of 4.5 for accessibility. If you have any questions regarding this, please reach out to us via Slack or email us at <admin@isomer.gov.sg>

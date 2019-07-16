---
title: Changing share icon
permalink: /documentation/homepage/changing-share-icon/
third_nav_title: "Homepage"
---
#### **Step-by-step guide to change your share icon in your site**
![Changing favicon of your homepage](/images/resources/changing-content-of-your-homepage.gif)
> Note: Be very careful with the spacing in the homepage.yml file. Your website will break if the spacing are incorrect

Before you start, make sure your share icon is in `png` format and its size is **exactly** 600px by 600px as per [Facebook's requirement](https://developers.facebook.com/docs/sharing/best-practices#images). Upload this share icon into the `/images/` folder, giving it a name such as `share-logo.png`.

1. Select your "Staging" Branch
2. In your repository, go to "_data" folder
3. Edit homepage.yml file
4. Change your share icon by adding or amending the section below inside homepage.yml
5. Click on "Commit changes" button

```yaml
# Sample homepage.yml file section for reference

# Image to appear on all pages when shared via WhatsApp, Facebook, etc
shareicon: /images/share-logo.png

```

---
title: Creating 2nd level nav for your navbar
permalink: /documentation/navbar-and-footer/creating-2nd-level-nav/
third_nav_title: "Navbar and Footer"
---
> IMPORTANT: For simplicity sake, the guide assumes the creation of the 2nd level nav of "WHO WE ARE" item.
Once you have a sense of how it is done, you may change "WHO WE ARE" into your preferred header name. If you have any questions regarding this, please reach out to us via Slack or email us at admin@isomer.gov.sg

#### **Part 1: Step-by-step guide to create a collection for your 2nd level nav**
![Adding collection](/images/resources/adding-second-level-item-to-your-navigation-bar-part-1.gif)
> Note: Be very careful with the spacing in the _config.yml file. Your website will break if the spacing are incorrect

1. Select your "Staging" Branch
3. In your repository root directory, find _config.yml file
3. Edit _config.yml file
4. Copy the code snippet below into _config.yml to create a new collection
5. Click on "Commit changes" button

```
# Sample code snippet for you to create a collection
# Replace who-we-are with your own 2nd level nav header collection name
# NEVER USE SPACE TO DEFINE THE COLLECTION NAME

collections:
    who-we-are:
    output: true
```
---


#### **Part 2: Step-by-step guide to create a navbar folder for your 2nd level nav**
![Adding 2nd nav folder](/images/resources/adding-second-level-item-to-your-navigation-bar-part-2.gif)
> Note: You will notice that the folder name goes by the naming convention of _collection name which we define in part 1. This is by design how the website works

1. Select your "Staging" Branch
2. In your repository root directory, click on “Create new file” button
3. Under the “Name your file…” section, create the directory by specifying _who-we-are/ignore.md
4. Click on "Commit changes" button

---


#### **Part 3: Step-by-step guide to create a left nav page for your 2nd level nav**
1. Select your "Staging" Branch
2. Create a new left nav page by stating using collection "who-we-are" which we define in part 1
3. [Click here](/webpage/creating-a-new-left-nav-page/){:target="_blank"} on the instructions on how to create a new left nav page

---


#### **Part 4: Step-by-step guide to create a 2nd level nav**
![Adding 2nd level nav](/images/resources/adding-second-level-item-to-your-navigation-bar-part-4.gif)
> Note: Be very careful with the spacing in the navigation.yml file. Your website will break if the spacing are incorrect

1. Select your "Staging" Branch
2. In your repository, go to "_data" folder
3. Edit navigation.yml file
4. Copy the code snippet below into navigation.yml to create a new 2nd level nav
5. Click on "Commit changes" button

```
# Sample code snippet for you to create a 2nd level nav

- title: Who We Are
  url: /who-we-are/
  sub-links:
  - title: My team
    url: /my-team/
```

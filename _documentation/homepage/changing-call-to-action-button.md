---
title: Changing call to action button
permalink: /documentation/homepage/changing-call-to-action-button/
third_nav_title: "Homepage"
---
#### **Step-by-step guide to change call to action button in your homepage**
![Changing call to action button of your homepage](/images/resources/changing-content-of-your-homepage.gif)
> Note: Be very careful with the spacing in the homepage.yml file. Your website will break if the spacing are incorrect

1. Select your "Staging" Branch
2. In your repository, go to "_data" folder
3. Edit homepage.yml file
4. Change your call to action content by amending the section below inside homepage.yml
5. Click on "Commit changes" button

```
# Sample homepage.yml file section for reference

# Call to Action Button
button:
  - text: Learn More
    url: /who-we-are/our-role/

# Call to Action Dropdown
i-want-to:
  - title: apply hotel licence
    url: /application-guidelines/application-for-licence/
  - title: apply for exemption
    url: /application-guidelines/application_for_exemption/
  - title: cancel hotel licence
    url: /application-guidelines/cancellation-of-licence/
  - title: change hotel-keeper
    url: /application-guidelines/change-of-hotel-keeper/
  - title: change hotel name
    url: /application-guidelines/change-of-hotel-name/
  - title: renew hotel licence
    url: /application-guidelines/renew-hotel-licence/

```

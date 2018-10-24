---
layout: leftnav-page-content
title: Managing your contact page
permalink: /managing-your-contact-page/
breadcrumb: Managing your contact page
collection_name: resources
---

#### **Contact Us page**
Each Isomer website has Contact Us page.
![Changing Content of Your Homepage](/images/resources/contact-us.PNG)

Contact Us page consist of 2 sections. You are not allowed to change the title for Contact Us page.
- Title
- Content


---

#### **Step-by-step guide to change content for your contact us page**
![Changing Content of Your Homepage](/images/resources/changing-content-of-your-contact-us-page.gif)
> Note: Be very careful with the spacing in the contact-us.yml file. Your website will break if the spacing are incorrect

* Select your "Staging" Branch
* In your repository, go to "_data" folder
* Edit contact-us.yml file
* Change the content by amending the section below inside contact-us.yml
* Click on "Commit changes" button

```
# Sample contact-us.yml file section for reference

locations:
  # HQ Address [REQUIRED]
  - title: 10 Pasir Panjang Road
    address: "#10-01 Mapletree Business City<br>Singapore 117438"
    find-directions: find-directions: https://www.google.com.sg/maps/place/Government+Technology+Agency+of+Singapore/
  # Operating Hours [OPTIONAL]
    operating-hours:
      - days: Mon - Thu
        time: 8.30am - 6.00pm
      - days: Fri
        time: 8.30am - 5.30pm
        description: Closed on Weekends and Public Holidays

# Contact Us
# For line: If you have an email, put "(email)" after the actual email
column:
  - title: General Enquiries & Feedback
    content:
    - line: +65 6211 2100
    - line: info@tech.gov.sg (email)
  - title: Mainline
    content:
    - line: +65 6211 0888
  - title: Quality Service Manager
    content:
    - line: +65 1800 211 0777
    - line: qsm@tech.gov.sg (email)
  - title: Whistleblowing Line
    content:
    - line: 1800-WHISTLE (1800 944 7853)
    - line: whistleblow@tech.gov.sg (email)
  - title: Fax
    content:
    - line: +65 6211 2222
```
---
layout: leftnav-page-content
title: Changing Content of Your Contact Us Page
permalink: /changing-content-of-your-contact-us-page/
breadcrumb: Changing Content of Your Contact Us Page
collection_name: resources
---

#### **Step-by-step guide**
1. Select your "Staging" Branch
2. In your repository, go to "_data" folder
3. Edit contact-us.yml file
4. Change the content by amending the section below inside the file
5. Click on "Commit changes" button

<font color="red"><b>*BE VERY CAREFUL WITH THE SPACING IN THE YML FILE. YOUR WEBSITE WILL BREAK IF THE SPACING ARE INCORRECT</b></font>
```
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

#### **Demo**
![Changing Content of Your Homepage](/images/resources/changing-content-of-your-contact-us-page.gif)

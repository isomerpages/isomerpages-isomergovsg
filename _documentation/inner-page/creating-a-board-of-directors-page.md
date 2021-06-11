---
title: Creating a Board of Directors page
permalink: /documentation/inner-page/creating-board-of-directors-page/
third_nav_title: "Inner Page"
---
#### **Step-by-step guide to creating a Board of Directors page**

1\. Create a new board-of-directors.yml under your site's /_data/ folder

2\. Copy the following code into your file:

```
  # Board of Directors
  - name: Person A
    title: Title A
    organisation: Organisation A
    image-url: /images/board-of-directors/Person_A.jpg
  - name: Person B
    title: Title B
    organisation: Organisation B
    image-url: /images/board-of-directors/Person_B.jpg
```
   
   The content on the page is controlled by the board-of-directors.yml. Add more people by duplicating the name, title, organisation and image-url fields.
   
3\. Create a board-of-directors.md file under your site's /pages/ folders. 

4\. Copy the following code into your file

```
---
layout: board-of-directors
permalink: /board-of-directors/
breadcrumb: Board of Directors
title: Board of Directors
---
```


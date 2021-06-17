---
title: Creating a new downloadable post
permalink: /documentation/resources/creating-a-new-downloadable-post/
third_nav_title: "Resources"
---
#### **Step-by-step guide to creating a new downloadable post**
![Create a new downloadable post](/images/resources/creating-a-new-downloadable-post.gif)
> Note: Do not put spaces in the filename of your .md file. Always replace the spaces with dash (-)

1. Select your "Staging" Branch
2. Go to media folder in your repo and then the respective folder
3. Go to _post folder
4. Click on “Create new file” button
5. Copy and paste the header code snippet below into your file
6. Fill in title, date, permalink according to your need. We recommend to make reference from your other existing post
7. Save the file in the format of YYYY-MM-DD-filename.md. THIS IS VERY IMPORTANT OTHERWISE IT WILL NOT WORK!
8. Click on "Commit new file" button

```
# Sample code snippet for downloadable post
---
layout: post
title:  Fill in your own title description
date:   Fill in your own date in YYYY-MM-DD format, example 2018-12-31
file_url: Fill in your file link for download
---
```

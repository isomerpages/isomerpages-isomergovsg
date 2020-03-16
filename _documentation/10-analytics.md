---
title: Analytics
permalink: /documentation/analytics/
---
### You've gotten your site up, now what?

You may have questions like these:
- How many people visit my website?
- Which pages on my website are the most popular?
- What content do my visitors like the most?

To give you a better understanding of how your visitors are viewing your site, you need to set up analytics on your site.
Here are analytics tools you could use on your isomer sites. 

#### 1. WOGAA
WOGAA is a whole of government analytics platform. You can start signing up for it [here](https://wogaa.sg/login). 
Go to **Manage Service** and click on **Add Service** button on the top right hand corner to get started.
![Manage Services](/images/wogaa-manage-services.png)
![Add Service](/images/wogaa-add-service.png)

Once you've registered your service, please write in to WOGAA's Support at [wog.aa.support@ncs.com.sg](mailto:wog.aa.support@ncs.com.sg) for verification that data is being captured on WOGAA's end. Do make sure that you've registered the www version of your domain and include the following details in your email:
- Service Name
- Service URL
- Environment (staging/production)

#### Setting up Sentiments

Sentiments is a tool for you to quickly gather feedback about your site from your visitors.

To set up sentiments, go to **Manage Services** on your WOGAA portal and select **Manage Sentiments**. Follow the step-by-step guide on the portal, you should be able to set it up with a quick toggle of a button.
![Manage Sentiments](/images/manage-sentiments.png)
![Toggle Sentiments](/images/toggle-sentiments.png)

If you have any questions regarding WOGAA, you may write to the WOGAA team at [wogaa@tech.gov.sg](mailto:wogaa@tech.gov.sg)

#### 2. Google Anlaytics
Google Analytics is an free analytics tools provided by Google. You can go [here](https://accounts.google.com/) to sign up using your google account.

Next, follow the steps below to configure Google Analytics on your site:
1. Go to your admin page, and under **Tracking Info**, select **Tracking Code**
![tracking code](/images/select-tracking-code.png)

2. Copy the **Tracking ID** on your Google Analytics
![tracking ID](/images/tracking-id.png)

3. Paste it on your **config.yml** file in your repository. You should create a field `google_analytics` if the file does not have this.
![isomer ga](/images/isomer-ga.png)


#### 3. Facebook Pixel
The Facebook Pixel collects data that helps you track conversions from Facebook ads, optimize ads, build targeted audiences for future ads, and remarket to people who have already taken some kind of action on your website.

You can refer to their instructions [here](https://www.facebook.com/business/help/952192354843755?id=1205376682832142)

You should not copy the code block that is provided by Facebook, but instead copy the Facebook Pixel ID that is provided and paste it within the config.yml file in the following format:

```yml
facebook-pixel: <Your Facebook Pixel code>
```

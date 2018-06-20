---
title: chapter1
menutitle: chapter1
position: 1
display: sidemenu
parent: introduction
subparent: 
parameters:
  - name:
    content:
content_markdown: |-

---
<a class="editor-link" href="{{site.github}}chapter1.md">Edit on Github</a>

**Campaign By Subscription Base**

**A. Adding Mail Subscribe Portlet**
  
1. Create a page where you want to add the portlet
2. Add the MailSubscribe Portlet
3. Once the portlet is added, click the prefrences icon, select **Configuration**.
  
            a. Select the Campaign you have created for this subscription based campaign
            b. First Name and Last Name should be tick, click Save.
            
     
**Note**: In case you want to add the subscription portlet in the footer of your site, give the campaign ID to the developer, they will set up the portlet for you. 

**Tip**:  To get the campaign ID, go to the campaign listing, hover to the campaign title, at the bottom of the page you will see a gray bar, with the campaign id, in the sample below 202 is the campaign id.


**B. Setting up Single Campaign**

1. Go to create campaign page. 
2. You will be directed to create campaign screen.
3. Add **Campaign Name, Campaign Type** (select **Subscription Based Scheduling**) and select **Category**.
4. Click Add EDM
  
            a. Add the Name for your EDM
            b. Select the email template you want to send out
            c. From the Recurrence select Once Time
            d. For Wait at Least select from the following:
                    1. Minute
                    2. Hours
                    3. Days
                    4. Week
                    5. Months
                    
**Note**: this waiting time is based on the time the person subscribed to your campaign. Example if you set the waiting time to 5 minutes, the person will receive the campaign after 5 minutes of their subscription, same goes with hours, days, weeks and month. If you set the waiting time into 1 week, the subscriber will receive the campaign after one week of subscription.
  
5. Click **Save** after. You will be redirected to the campaign listing page, the campaign you have created is at the bottom.
  
  
**C. Setting up Multiple Campaign**

To set up multiple campaign follow the first steps when you create a single edm. The second step will be as follows:


1. Click **Add EDM**

          a. Add the Name for your **2nd EDM**
          b. Select the email template you want to send. (**Note** -  this will be the second email)
          c. From the Recurrence select Once Time
          d. For Wait at Least select from the following:
                  a. Minute
                  b. Hours
                  c. Days
                  d. Week
                  e. Months
     
     
**Note:** this waiting time is based after you receive the first campaign. Example you set the timing of your 2nd edm to 2 hours. So 2 hours after you received the 1st email you will receive the 2nd email. 

                  

          





            





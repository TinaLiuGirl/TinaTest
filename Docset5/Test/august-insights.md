---
title: August 2018 Docs Insights
description: Share monthly docs analysis insights
keywords: PillarReview, BI, Docs, Insights
---

# August 2018 Data Insights
In this document, we will share Commerce + Ecosystems APEX Pillar Review KPIs, top line stats as well as insights for docs site health and growth. 

## Commerce + Ecosystems APEX FY19 KPIs - August
In FY19, we will start tracking traffic across all technical sites within APEX starting in Q1, and look into technical sites' potential influence on Azure Trial Activiations, Conversions and Churn in Q2. **12 APEX owned technical sites** combined reached **54M deduped unique visitors across sites**. 

|KPI|Definition|
|---|----------|
|**Unique Visitors**|Number of unique visitors to the site|
|**Active Visitors**|Number of unique visitors having page views to the site on two different days|
|**Visits**|Number of page view sessions to the site|
|**Page Views**|Number of page views to the site|
|**Free Trial Referrals**|Number of Azure Free Trial clicks from the site|


|Tech Sites (MoM Stats)       |Unique Visitors|Active Visitors |Visits         |Page Views      |Free Trial Referrals     |
|-----------------------------|---------------|----------------|---------------|----------------|-------------------------|
|docs.microsoft.com           |38.11M (+27.5%)|7.88M (+17.4%)  |85.22M (+23.7%)|165.02M (+17.2%)|15,468 (+0.4%)  |
|channel9.msdn.com            |1.40M (-19.1%) |129K (-16.5%)   |1.92M (-18.2%) |3.35M (-25.2%)  |3,529 (+71.73%) |
|msdn.microsoft.com           |4.73M (-14.6%) |1.68M (-20.2%)  |12.68M (-24.3%)|24.26M (-25.5%) |    
|technet.microsoft.com        |2.04M (-13.4%) |396K (-15.1%)   |3.28M (-15.9%) |5M (-19.9%)     | 
|social.msdn.microsoft.com    |6.93M (+3.7%)  |1.92M (+5%)     |15.08M (+5.7%) |20.7M (+4.7%)   |
|social.technet.microsoft.com |12.7M (+7.5%)  |2.3M (+8.4%)    |22.02M (+8.3%) |30.51M (+7.9%)  |
|blogs.msdn.microsoft.com     |4.21M (-3.4%)  |838K (-2.3%)    |6.82M (-2%)    |8.87M (-1.4%)   |
|blogs.technet.microsoft.com  |3.64M (-9.9%)  |717K (-9.1%)    |6.21M (-10.1%) |8.28M (-9.8%)   |
|code.msdn.microsoft.com      |423K (+8.7%)   |62K (+12.5%)    |596K (+9.6%)   |968K (+7.7%)    |
|microsoft.com/handsonlabs    |103K (-13.4%)  |11K (-2.2%)     |163K (-11.5%)  |557K (-18.2%)   |
|docs.azure.cn                |26K (-9.2%)    |3.8K (+5.5%)    |54K (-0.8%)    |142K (+2.9%)    |
|gallery.technet.microsoft.com|897K (+1.4%)   |141K (0.9%)     |1.32M (+0.9%)  |2.1M (+1.2%)    |

> [!Note]
> Free Trials clicks for docs.microsoft.com only include clicks from universal header. Channel 9 launched Azure Free Trials from video pages since March 16, 2018.

## Docs Reach 

### Unique Visitors and Page Views
Docs Unique Visitors and Page Views in August grew significantly by 27.5% and 17.2%, respectively, from July. The uplift is primarily driven by .Net migration to docs, an IIS article visited by 7 million users from India: https://docs.microsoft.com/en-us/iis/troubleshoot/using-failed-request-tracing/troubleshooting-failed-requests-using-tracing-in-iis, and traffic increase from Office content. The visits to the IIS article are mostly direct traffic, spread across many cities in India, we will continue monitoring this article in the coming month. 

![august-insights-docs-MoM-UVs-PVs](august-insights-docs-MoM-UVs-PVs.png)

### Docs Topics
The numbers of topics on docs increased about 5 times from Jan to August. In August, about 19% of topics have been viewed by users. 


![august-insights-docs-MoM-Topics](august-insights-docs-MoM-Topics.png)


### Active, Engaged, Dedicated Users
|Measurements  |Category  |Proposed Definition  |
|---------|---------|---------|
|Valid page view    |    PV     |When a visitor stays on a Docs page >=5 second or to have at least 1 click      |
|Active user   |      User   |Within the current month, a visitor has at least one valid page view         |
|Engaged user    |    User     |Within the current month, a visitor has seen “valid page views” on 2 different days      |
|Dedicated user    |     User    |Within the current month, a visitor has seen “valid page views” on 5 different days.         |

We continue observe stablized user pattern in August, 74% of users (28 million) are active users with at least 1 valid page view, 17% of users (6.5 million) visited docs site multiple days and 4% users (1.6 million) visited docs site 5 or more days.  

![august-insights-active-engaged-dedicated-users](august-insights-active-engaged-dedicated-users.png)

### Page Views by Referrer Type
In August, Direct page view traffic from Docs had the most increase from 26M to 41M, about 24.5% of total Docs traffic, this is due to the direct traffic to the above mentioned IIS trouble shooting article. Organic search accounts for 37.3% of page view referrers: 91.3% of organic search traffic came from Google, and 5.6% from Bing. 34.5% of page view referrers came from Microsoft sites, where docs site contributed to 86% of Microsoft traffic. 
![august-insights-pvs-by-referrertype](august-insights-pvs-by-referrertype.png)

### Popular Top Level Nodes
.Net, SQL, Azure are 3 leading top level nodes, with 23M, 19M and 18M page views, respectively. IIS jumped to top 4th with 14M page views, more than doubled it's July's 6M page view - this is due to traffic from India on a particular trouble shooting article: https://docs.microsoft.com/en-us/iis/troubleshoot/using-failed-request-tracing/troubleshooting-failed-requests-using-tracing-in-iis

![august-insights-pvs-by-top-level-node](august-insights-pvs-by-top-level-node.png)

### Traffic by Topic Type and Continent
Top contributing Topic Type by page views including 'article', 'conceptual'. 
- 'article' topic type contributed to 37% of total pageviews
- 'conceptual' topic type contributed to 30% of total pageviews
- Reference type contribited to 8% of total pageviews 

Back in March and May, we have seen increased traffic to 404 broken links. Teams have been working to address the issue and made some progress since June, here is [August 404s report based on kusto query](https://microsoft.sharepoint.com/:x:/r/teams/CE_CSI/_layouts/15/Doc.aspx?sourcedoc=%7B9cf828c7-03a0-4597-b745-4b1872aead3e%7D&action=default&uid=%7B9CF828C7-03A0-4597-B745-4B1872AEAD3E%7D&ListItemId=67031&ListId=%7BB6933FC8-6E7E-4E20-86D6-0C963B60B552%7D&odsp=1&env=prodbubble/)


![august-404s](august-404s.png)

Asian countries saw continued page view increase in August, about 45% of total visitors traffic, 10 percentage points higher than June. Within Asian countries, India had big jump in unique visitors, 9.4 million (2.8 times higher than July), this is also due to the same article mentioned above: https://docs.microsoft.com/en-us/iis/troubleshoot/using-failed-request-tracing/troubleshooting-failed-requests-using-tracing-in-iis, spreading across the second half of August.

![august-insights-uvs-by-country-and-topictype](august-insights-uvs-by-country-and-topictype.png)

Reference: 
[Docs PowerBI](https://msit.powerbi.com/groups/me/dashboards/91bb4b60-d7b2-42d6-b815-d0c566528a71)

## CSAT

In August, **262K unique visitors** submitted **307K** content ratings, with **62% CSAT**. By TopicType,
* Interactive tutorials has highest CSAT - 84%
* language-reference - 67%
* conceptual - 63%
* managed-reference - 62%
* article - 59% 
* reference 52%

## Free Trials
**15K** free trial clicks from docs header in August, similar to July.
* 25% of total clicks came from 'conceptual'
* 22% of clicks came from 'article' 
* 27% of clicks from 'landing-page' and 'hub-page' combined
* 11% from 'quickstart'

![august-insights-free-account-clicks-by-topictype](august-insights-free-account-clicks-by-topictype.png)

## Triple Crown  

>[!Note]
>5 Triple crown modules are back into interactive tutorial mode for preparing new triple crown release for Ignite. Triple crown insights for July and August will be merged into interactive tutorial section.

## Hands-on Lab

Hands-on Lab preview launched at //BUILD. This feature is to integrate Hands-on lab into Docs so that customers can launch hands-on labs through Docs tutorials.

### Reach 

In August, 9 labs turorials have seen **1,097 unique visitors**. Among 1,097 unique visitors, we have **977 active visitors, 108 engaged visitors, and 13 dedicated visitors**. 


### Engagement

In August, 5 hands-on labs had 544 visitors launched 57 times hands-on labs. **10.5% lab launch rate** is a little bit higher than the one(10.1%) in July. 

![August Insights Hands On Lab Visitor Funnel](Image/august-insights-hands-on-lab-visitor-funnel.png)

**Overall Labs completions rate is 8.5%**, decreased by 12% compared with the number in July. 53% users left after browsering the introduction page, which is a little worse than 49% in July. 
 
![August Insight Hands On Lab Completion Funnel](Image/august-insight-hands-on-lab-completion-funnel.png)

**Get the most out of your web app with a Progressive Web App (PWA)** has the most hands-on lab **launch click times: 18**. 


### CSAT

No vote in Hands-on lab in August, so no CSAT this month
For more information, check out [Hands-On Lab Report](https://msit.powerbi.com/groups/me/reports/57f01a81-846f-42e7-a10e-d86b9929c152/ReportSection)

## API Documentation (Reference)

<!--![](icons/up.png)-->
<!--![](icons/down.png)-->
<!-- ![](icons/upred.png) -->
<!-- ![](icons/downgreen.png) -->

### Area Traffic Overview

12 millpion page view traffic across 7 reference areas for all locales in August, +46% vs July, driven by .Net migration.
![august-reference-MoM-PVs](august-reference-MoM-PVs.png)

The table below shows an overview of the traffic that was directed to reference content in the month of August vs July, along with the number of unique users. This data is not segmented by source, but is rather an aggregation.

| Area | Page Views (July) | Page Views (August) | Unique Users (July) | Unique Users (August) |
|:------|:------|:------|:------|:------|
| .NET       | **3,065,107** | ![](icons/up.png) **6,486,498** (_+111.62%_) | **793,462**    | ![](icons/up.png) **1,759,971** (_+121.80%_) |
| PowerShell | **3,972,148** | ![](icons/up.png) **4,233,508** (_+6.57%_)  | **1,194,165**  | ![](icons/up.png) **1,235,427** (_+3.45%_)   |
| CLI        | **335,518**   | ![](icons/up.png) **365,984** (_+9.08%_)     | **94,717**     | ![](icons/up.png) **99,488** (_+5.03%_)      |
| REST       | **816,804**   | ![](icons/up.png) **849,430** (_+3.99%_)     | **157,338**    | ![](icons/up.png) **161,223** (_+2.46%_)     |
| Python     | **67,349**    | ![](icons/down.png) **65,056** (_-3.4%_)     | **8,383**      | ![](icons/down.png) **8,337** (_-0.54%_)     |
| JavaScript | **47,153**    | ![](icons/up.png) **61,517** (_+30.46%_)     | **11,166**     | ![](icons/up.png) **14,303** (_+28.09%_)     |
| Java       | **35,427**    | ![](icons/down.png) **31,539** (_-10.97%_)   | **11,377**     | ![](icons/down.png) **11,301** (_-0.66%_)    |

Most of the additional .NET traffic is driven by the migration of API content from MSDN to docs.microsoft.com.

### API Browser Searches

When it comes to API discovery, we expect the API Browser experiences to be at the forefront, quickly providing the relevant API results. The breakdown below outlines the search volume for each of the platforms for which we have an API Browser.

| API Browser Instance | Searches (July) | Searches (August) | Meaningful Searches (July) | Meaningful Searches (August) | Meaningless Searches (July) | Meaningless Searches (August) |
|:------|:------|:------|:------|:------|:------|:------|
| .NET       | **226,040** | ![](icons/up.png) **260,523** (_+15.25%_) | **89,794** | ![](icons/up.png) **101,158** (_+12.65%_) | **136,262** | ![](icons/upred.png) **159,375** (_+16.96%_)   |
| REST       | **6,358**   | ![](icons/down.png) **5,275** (_-17.03%_) | **2,534**  | ![](icons/down.png) **2,231** (_-11.95%_) | **3,824**   | ![](icons/downgreen.png) **3,044** (_-20.39%_) |
| JavaScript | **1,307**   | ![](icons/up.png) **2,266** (_+73.37%_)   | **572**    | ![](icons/up.png) **880** (_+53.84%_)     | **735**     | ![](icons/upred.png) **1,386** (_+88.57%_)     |
| Python     | **2,807**   | ![](icons/up.png) **2,811** (_+0.14%_)    | **1,178**  | ![](icons/up.png) **1,239** (_+5.17%_)    | **1,629**   | ![](icons/downgreen.png) **1,572** (_-3.49%_)  |
| PowerShell | **114,041** | ![](icons/up.png) **130,525** (_+14.45%_) | **33,028** | ![](icons/up.png) **36,879** (_+11.65%_)  | **81,007**  | ![](icons/upred.png) **93,655** (_+15.61%_)    |

For the purposes of this table, we define:

* **Searches** - number of searches executed within the API Browser.
* **Meaningful Searches** - number of searches that resulted in the user making a click on one of the results (higher is better).
* **Meaningless Searches** - number of searches that resulted in the user not making a click after searching (higher is worse).

Additionally, here is a snapshot of **searches that produce results** vs. **searches with no results**:

| API Browser Instance | Searches with Results (July) | Searches with Results (August) | Searches without Results (July) | Searches without Results (August) |
|:------|:------|:------|:------|:------|
| .NET       | **174,560** | ![](icons/up.png) **200,469** (_+14.84%_) | **51,480** | ![](icons/upred.png) **60,054** (_+16.65%_)  |
| REST       | **5,738**   | ![](icons/down.png) **4,874** (_-15.05%_) | **620**    | ![](icons/downgreen.png) **401** (_-35.32%_) |
| JavaScript | **896**     | ![](icons/up.png) **1,555** (_+73.54%_)   | **411**    | ![](icons/upred.png) **711** (_+72.99%_)     |
| Python     | **2,214**   | ![](icons/down.png) **2,195** (_-0.85%_)  | **593**    | ![](icons/upred.png) **616** (_+3.87%_)      |
| PowerShell | **64,467**  | ![](icons/up.png) **75,926** (_+17.77%_)  | **49,574** | ![](icons/upred.png) **54,599** (_+10.13%_)  |

### REST Try-It Overview

We define metrics:

* **Views on Azure REST API reference with Try-It enabled** - User viewed the page of Azure REST API reference with Try-It enabled.
* **Try-It** - User clicked the "Try It" button.
* **Login Prompt** - The "Sign In" button showed up in the REST Try-It area.
* **Login** - User clicked the "Sign In" button.
* **Authorized** - User successfully signed in for using REST API Try-It function.
* **Run** - User clicked the "Run" button.
* **Success** - The HTTP status code returned 2XX which indicates that the client’s request was accepted successfully.
* **Try-It Success Rate** - Unique visitors of "Success" / Unique visitors of "Try-It" which indicates how many from the visitors who clicked the Try-It button eventually got the REST API run successfully.

|Metrics|July|August|
|---|---|---|
|Views on Azure REST API reference with Try-It enabled| 115,984 Page Views <br> 35,100 Unique Visitors | ![](icons/up.png) **130,173** (+12.2%) Page Views <br> ![](icons/up.png) **39,298** (+12.0%) Unique Visitors |
|Try-It | 13,598 Clicks <br> 4,332 Unique Visitors | ![](icons/up.png) **15,233** (+12.0%) Clicks <br> ![](icons/up.png) **4,905** (+13.2%) Unique Visitors |
|Login Prompt (_data since 7/26_) |922 Times <br> 745 Unique Visitors | **6,357** Times <br> **4,637** Unique Visitors |
|Login (_data since 7/26_) |663 Times <br> 569 Unique Visitors | **4,778** Times <br> **3,704** Unique Visitors |
|Authorized (_data since 7/26_) |571 Times <br> 513 Unique Visitors | **4,100** Times <br> **3,393** Unique Visitors |
|Run | 19,533 Clicks <br> 2,485 Unique Visitors | ![](icons/up.png) **21,765** (+11.4%) Clicks <br> ![](icons/up.png) **2,880** (+15.9%) Unique Visitors |
|Success| 8,305 Success Responses <br> 1,646 Unique Visitors | ![](icons/up.png) **10,230** (+23.2%) Success Responses <br> ![](icons/up.png) **1,971** (+19.7%) Unique Visitors |
|Try-It Success Rate <br> (Unique Visitors of Success/Unique Visitors of Try-It)|38.0%| ![](icons/up.png) **40.2%**|

In August, the usage of REST Try-It increased by overall 12%. Starting from end of June, we are able to collect the responses returned from the REST API run. According to the response codes analysis, we observed that more users ran the Try-It API successfully in August. Also, the "Try-It to Success Rate" is 40.2% in August, higher than July's 38%. For the metrics "Login Prompt", "Login", and "Login Authorized", the login behaviors just started to be logged since 7/26 which causes the huge difference.

### Cloud Shell Try-it Overview

The table below is an overview of Cloud Shell feature usage for Azure CLI and Azure PowerShell from the steps of "Try-it" click, "Log-in" button click and finally authorized in Azure Cloud Shell.

| Cloud Shell<br>Try-it | Login-Prompt<br/>-July | Login<br/> -July | Authorized<br/>-July | Login-Prompt<br/>-August | Login<br/>-August | Authorized<br/>-August |
|-------------------|-------|-------|------|------|--------|--------|
| Azure CLI         |  4,169 |  2,466 | 2,164 | ![](icons/up.png)**6,845** <br/>(+64.19%) |![](icons/up.png)**3,906**<br/> (+58.4%)|![](icons/up.png)**3,334**<br/>(+50.1%)|
| Azure PowerShell  |    2,673 | 1,477  |  1,281  | ![](icons/up.png) **4,758** <br/> (+78%) |  ![](icons/up.png)**2,687** <br/>(+81.9%) | ![](icons/up.png) **2,367** <br/> (+84.8%)|

In August, the usage of Cloud Shell Try-it increased by overall 69.6%. There were 10 days data missing for Cloud Shell Try-it in July, and we integrate the new Cloud Shell rendering experience. We observed more than 60% users increased use Try-it feature in both Azure CLI and Azure PowerShell, also the authorization rate for Azure PowerShell is 49.7%, higher than July's 47.9%.

### PowerShell OverView 
By end of August, we have 961 PowerShell Modules having views, 41 live monikers. 

The following chart shows the # of releases or updates for PowerShell reference, using build as indicator. 

![august-PowerShell-Builds-MoM](august-PowerShell-Builds-MoM.png)


PowerShell PageView traffic since Jan 2018:


![august-PowerShell-PVs-MoM](august-PowerShell-PVs-MoM.png)

## Interactive Tutorials

There are a total of **42** interactive tutorials with 623 live pages. 

### Reach

In August, all interactive tutorials have

* **476K** Page Views, 10% MoM increase
* **217K** Unique Visitors, 14.7% MoM increase

![August Insights Interactive Tutorial Pv Bymonth](Image/august-insights-interactive-tutorial-pv-bymonth.png)

* **196K** Active Visitors
* **28K** Engaged Visitors
* **2k**  Dedicated Visitors

![August Insights Interactive Tutorial User Funnel Bymonth](Image/august-insights-interactive-tutorial-user-funnel-bymonth.png)

Top 5 tutorials that got most page views and visitors in August are:

|Tutorial|Page Views in August|Visitors in August|
|---|---|---|
|power-bi/guided-learning/gettingstarted|96,321|61,426|
|power-bi/guided-learning/gettingdata|58,484|33,071|
|powerapps/guided-learning/get-started|33,950|24,212|
|power-bi/guided-learning/modeling|32,744|20,301|
|power-bi/guided-learning/visualizations|28,789|16,481|


### Engagement

In August, there have **47.1K** visitors (from the 217K visitors) completed at least one tutorial. The complete rate is **21.6%**. Compared with July, the complete rate is stable

In July, there have **42.2K** visitors (from the 192K visitors) completed at least one tutorial. The complete rate is **22%**. 

![August Insights Interactive Tutorial Funnel](Image/august-insights-interactive-tutorial-funnel.png)

|Engagement Stage|August Visitors|August Conversion Rate|July Visitors|July Conversion Rate|
|---|---|---|---|---|
|Visitors|217.4K|100%|192.2K|100%|
|Visitors >= 1 step|187.7K|86%|168.5K|88%|
|Visitors >= 50% steps|104.6K|48%|94.4K|49%|
|Visitors completed|47.1K|21.6%|42.2K|22%|

![August Insights Interactive Tutorial Completed](Image/august-insights-interactive-tutorial-completed.png)

Top 3 tutorials that got **most completed visitors** in August are:

Tutorial|Completed Visitors|Visitors|Complete Rate|
|---|---|---|---|
|power-bi/guided-learning/gettingstarted|19,561|61,426|32%|
|power-bi/guided-learning/gettingdata|8,091|33,071|24%|
|power-bi/guided-learning/modeling|5,738|20,301|28%|

Top 3 tutorials that had **highest complete rate** in August are:

Tutorial|Completed Visitors|Visitors|Complete Rate|
|---|---|---|---|
|dotnet/csharp/quick-starts/branches-and-loops|3,117|6,003|52%|
|flow/guided-learning/administer-flows|588|1,215|48%|
|dotnet/csharp/quick-starts/interpolated-strings|2,494|5,455|46%|


### CSAT

August CSAT of interactive tutorials content is **84.31%**, which is higher than Docs overall CSAT 61%.

![August Insights Interactive Tutorial Csat](Image/august-insights-interactive-tutorial-csat.png)

Top 5 tutorials that got most helpful votes in August are:

|TutorialName|CSAT|Helpful Votes|
|---|---|---|
|power-bi/guided-learning/gettingstarted|84%|27,881|
|power-bi/guided-learning/gettingdata|84%|13,149|
|dotnet/csharp/quick-starts/numbers-in-csharp|84%|7,042|
|power-bi/guided-learning/modeling|81%|6,053|
|powerapps/guided-learning/get-started|77%|7,230|

## Site Search

**Metrics Definition**:
* Searches - number of searches executed in site search
* Meaningful Searches - number of searches that resulted in the user making a click on one of the results (higher is better). On the contrary, `Meaningless Searches` means the number of searches that resulted in the user not making a click after searching (higher is worse). `Meaningless Searches` number can be calculated by `Searches` number minus `Meaningful Searches` number. The "Meaningless Searches" number is not provided explictly in the table below.
* Successful Searches - number of searches that resulted in the user making click on one of the results and making a `relevant page view` at the result page. The `relevant page view` means:
    * User spends >= 1 min on a conceptual or reference content page
    * User clicks >=1 click from a hub or landing page

|Metrics|July|August|
|---|---|---|
|Searches|818,348|![](icons/down.png) **815,960** (_-0.3%_)|
|Meaningful Searches|443,726|![](icons/down.png) **435,665** (_-1.8%_)|
|Successful Searches|177,446|![](icons/down.png) **173,598** (_-2.2%_)|
|Searches from TOC filter|160,608|![](icons/up.png) **211,049** (_+31.4%_)|

The number of site search actions in August slightly decreased comparing to what of July. From August's searches, 25.9% came from the search links in the TOC area, the number and ratio are both higher than what of July.

## Community

### Twitter

The docs.microsoft.com team owns the [@docsmsft Twitter account](https://twitter.com/docsmsft). The following represent metrics tracked for the account (and can be found [in the dashboard](https://lens.msftcloudes.com/v2/#/dashboard/@docsmsft%20Twitter%20Impact?temp=0&newDashFromMenu=false&_g=(ws:ffa4898d-2494-499a-84e7-512b9ad63c14))):

| Metric | July | August |
|:-----|:------|:----|
| Generated Page Views     | **8,970**  | ![](icons/down.png) **5,870** (_-34.55%_) |
| Acquired Unique Visitors | **5,595**  | ![](icons/down.png) **3,368** (_-39.80%_) |
| Acquired Followers       | **952**    | ![](icons/down.png) **521** (_-45.27%_)   |
| Likes                    | **4,398**  | ![](icons/down.png) **3,087** (_-29.80%_) |
| Retweets                 | **2,091**  | ![](icons/down.png) **1,469** (_-29.74%_) |

August ended up being a slower month in terms of content promotion, and the numbers above reflect that.

### GitHub Issues

In August, traffic on feedback section:

* **248k** unique visitors, 15% MOM increase
* **315k** pageview, 18% MoM increase.  
* **30%(74k/248k)** unique visitors click documentation feedback, and **11%(27k/248k)** unique visitor clicked product feedback button. 

The following chart displays user click behavior distribution on feedback section.

![August Github Issue User Click Behavior](Image/august-github-issue-user-click-behavior.png)

In August, **2,748 unique visitor submitted 3,267 issues**.

![August Github Issue Monthly Trend](Image/august-github-issue-monthly-trend.png)


In August, 51 repos enabled issues. Azure-docs, aspnet, and dotnet are most active issue channel. They received 1,988 GitHub Issues with 7,617 comments submitted from Docs. The following are the detail for 10 major product/service enabled issue channels

Repo|TotalIssue|TotalComments|TotalClosedIssue|TotalUniqueUserPostIssues|Anwser Rate|
|---|----------|-------------|----------------|-------------------------|-----------|
|MicrosoftDocs/azure-docs|1,358|6,050|898|960|66%|
|dotnet/docs|358|741|154|278|43%|
|aspnet/Docs|272|826|144|190|53%|
|MicrosoftDocs/vsts-docs|161|300|57|148|35%|
|Azure/azure-cli|150|533|55|124|37%|
|SharePoint/sp-dev-docs|140|394|30|107|21%|
|MicrosoftDocs/xamarin-docs|110|207|107|77|97%|
|MicrosoftDocs/visualstudio-docs|103|193|28|85|27%|
|MicrosoftDocs/windowsserverdocs|100|178|29|83|29%|
|MicrosoftDocs/windows-itpro-docs|90|239|42|80|47%|


For more information, check out [GitHub Issues Report](https://msit.powerbi.com/groups/me/reports/439bd937-f78a-4f1e-9f9f-4bf0d35365f6/ReportSection0d6349d59155f917a4d0?ctid=72f988bf-86f1-41af-91ab-2d7cd011db47)

### Community Pull Requests (PRs)
From Jan 2017 to August 2018, **2,533** community members submitted **11,800** pull requests to docs, with **87% acceptance rate**.

In August, **419** community members submitted **1,197** docs PRs. **980 pull requests got accepted** in August with **82% acceptance rate**, 7% (86) of pull requests are rejected, and rest are in 'open' state waiting for triage.

![August Insights Community Prs Accepted](august-insights-community-prs-accepted.PNG)

### LiveFyre Comments
With the launch of GitHub Issues, LiveFyre comments continue to decrease over time. 

![August Insights Community Livefyre Posts](Image/august-insights-community-livefyre-posts.png)

### Docs Site Feedback

In August, Docs site feedback has great performance: 
* **83** New issues 
* **83** closed issues. 30 issues closed as resolved. 
* **Answer rate by the end of August: 75.6%**, slightly increase compared with July. 

![August Feedback Monthly Summary](Image/august-feedback-monthly-summary.png)

|Label|New Issues|Open Issues|Closed Issues|YTD Open Issues|YTD Closed Issues|
|-----|----------|-----------|-------------|---------------|-----------------|
|content|35|14|35|48|175|
|bug|14|4|13|18|51|
|new-feature|1|1|1|12|17|
|enhancement|18|12|22|78|94|
|loc|4|3|2|5|7|

## Channel 9

_More data at https://aka.ms/c9reporting_

|Metrics|July|August|August vs July|
|---|---|---|---|
|Video Views (Site+YouTube)|516,729|**1,170,936**|![](icons/up.png) +126.6%|
|Watch Time (minutes) (Site+YouTube)|4,548,488|**9,391,566**|![](icons/up.png) +106.5%|
|Average Watch Time (minutes) per Video View (Site+YouTube)|8.80|**8.02**|![](icons/down.png) -8.9%|
|Site Page Views|4,495,821|**3,371,637**|![](icons/down.png) -25.0%|
|Downloads|37,750|**36,331**|![](icons/down.png) -3.8%|
|Azure Free Trial Clicks|2,055|**3,529**|![](icons/up.png) +71.7%|
|YouTube Likes|2,192|**3,464**|![](icons/up.png) +58.0%|
|YouTube Shares|2,175|**3,685**|![](icons/up.png) +69.4%|
|YouTube Net New Subscribers|1,066|**2,876**|![](icons/up.png) +169.8%|
|Comments (Site+YouTube)|520|**544**|![](icons/up.png) +4.6%|

There had a huge increase of video views in August comparing to what in July. The main driver is that the EPZ show has its paid media desk org to prompt episodes [EPZ 1807](https://www.youtube.com/watch?v=BuV9Ntszwb8) and [EPZ 1808](https://www.youtube.com/watch?v=9YdY8_dbeTI), and that made lots of video views at Microsoft Developer YouTube channel.

Top 5 videos by video views:

1. [JAMF integration with Microsoft 365 - Endpoint Zone 1808](https://www.youtube.com/watch?v=9YdY8_dbeTI) - 260,377
2. [EBF onboarder for Microsoft Intune - Endpoint Zone 1807](https://www.youtube.com/watch?v=BuV9Ntszwb8) - 248,717
3. [How To Set Up Multi-Factor for Your Account](https://channel9.msdn.com/posts/multi-factor-account-setup) - 11,368
4. [What's New in TypeScript?](https://channel9.msdn.com/events/build/2016/b881) - 7,618
5. [Introducing Visual Studio Live Share](https://channel9.msdn.com/events/connect/2017/t254) - 6,053

## Contacts
* Mei Liang (APEX)
* Jian Dong (APEX)
* Presley Yuan (APEX)
* Den Delimarschi (APEX)
* Jessie Huang (APEX)
* Edison Dai (APEX)
* Ekaterina Lazhintseva (CGA)
* Tim Wong (CGA)
* Gordan Kuvac (CGA)

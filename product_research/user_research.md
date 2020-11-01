Table of Contents
---
- [Purpose](#purpose)
- [Overview of people interviewed](#overview-of-people-interviewed)
- [User Research](#user-reserach)
- [Report](#report)
- [Prototype](#prototype)
- [Appendix](#appendix )

## Purpose
The purpose of this research is to ensure that people in the industry will actually use our product. During our user profile study, we bundled up all our users' pains and created a solution that could account for them. This research ensures that our prototype does in fact fit to their standards. The user profile research can be found in the appendix.

## Overview of people interviewed
* Cathal
    * Senior Manager - Data Science @ RBC
    * Has a background in cybersecurity
    * Familiar with key metrics
    * Major customer to our product
* Demetre
    * Software Developer @ FormaAI
    * Familiar with data visualization tools

## User Research
During our user research we asked our users to perform these specific tasks regarding our figma prototype:

Rob Moss' account was recently detected as a threat and had his account frozen, can you give me some insight as to what might have led to Rob being flagged as a threat?
Locate list of all contained threats.
Locate the key metrics then identify the total number of insider threats occurred and the number of contained threats.
Who was flagged as a threat just before Rob Moss?

The reason we chose these specific tasks is to allow the user to navigate throughout various important features that our prototype will provide. These include: displaying key insider threat metrics, navigation, user and user event timelines, as well as displaying flagged users.

After performing the tasks, we then asked the users to fill out a [survey](https://forms.gle/deeQj9E3tfbP1JBy8) based on their user experience for our prototype. In this survey we asked them questions regarding improvement, aesthetics, troubles, as well as specific questions that we had. After they completed the survey we discussed any questions or comments they had regarding the prototype. This allowed the users to process their thoughts during the survey and then talk to us about their overall experience.

Throughout this process, we also asked users to share their screen so that we can watch them as they perform their tasks and take notes if needed. 

The video/survey interviews and raw notes can be found in the appendix for each user.

## Report
### Session Overviews
Our first UX research interview was with Cathal. Overall we found this session to be moderately efficient, with some challenges arising and improvement recommendations. Starting on the main dashboard, the interviewee was confused about the visuals. These visuals are mainly a placeholder for future features which makes this confusion understandable. 

Our first observation was that the interviewee tried clicking on the dashboard components to view more information rather than go to links through our ‘hamburger’ style menu dropdown. We have since added some additional links within those components to make viewing related pages easier. For our first task of locating threat information on Rob Moss, this interviewee had some difficulty locating our intended target page. The targeted information can currently be found by going to the users page, and clicking on the timeline for Rob Moss. However, our interviewee was insistent on looking for this information within the threats page and did not consider looking in the users page. We noticed the interviewee became frustrated after not being able to complete task 1 in the timely manner. This provides good insight as to where we should add links to relevant pages such that we can reduce navigation time and improve user retention rates. 

Another major concern this interviewee had was the labels. They did not instantly know what the metrics on the dashboard (MTTR, MTTD) were acronyms for. They recommend having the full metric name available. To solve this issue we will consider adding info modals with additional information on these components. Another labeling issue the interviewee had was the menu page headers. They would like a more descriptive page header as opposed to just “threats” or “timeline”. Both of these points will be taken into consideration to create better labels and enable a smoother experience.

Our second UX research interview was with Demetre. This interviewee was able to very quickly complete all 4 tasks with very minimal difficulty. The only point to notice was that he checked multiple pages before finding the information for tasks 1 and 4. This could just be due to being a first time user, however we think this could also be improved similar to the above by improving our labeling. 


### General Feedback Summary
In this section we will summarize any general recommendations and feedback from our interviewees.

Potential Improvements

* Ability to view the timeline information at different levels (day, week, month, etc.)
* Offer different viewing methods on the timeline, for example bundled events in 1 hour time intervals
* Add tiered alerts on the dashboard (critical, important, warning, etc.)
* Improve navigation within the application. Add additional links to more easily find data and pages. 
* Extend current table data sorting methods (by user, date, threat type, etc.)
* User wants more options to view ‘power users’ that would have a long timeline (this related back to bundled events on the timeline)
* Potentially merge the user and threats page, or find a better way partition and display the information.
* fer a light and dark mode
* Insider accessibility such as colour blindness when choosing our colour schemes. 

## Prototype
Click [here](https://www.figma.com/proto/OwXj6Ij7pyiuH3K3YK4NyS/Cyberity-Prototype?node-id=109%3A53159&scaling=min-zoom) to view our complete prototype on Figma.

## Appendix

1. [User profile interviews](./data/user_profile_interviews.pdf)
2. Cathal User Research
    1. [Video Interview](https://utoronto.zoom.us/rec/share/a32A6IY2qVHLaKjjYpxD4RsqpI5f-huRwCPajzow2h9qYHqiFqbITlhRk3CQBKtS.6v-0pMG3g8d5SUIq)
    2. [Raw Notes](./data/user_research_cathal_rawnotes.txt)
    3. [Survey Interview](./data/user_research_cathal.pdf)
3. Demetre User Research
    1. [Video Interview](https://utoronto.zoom.us/rec/share/LwsuE5Dy_iAjw0urVDOuYtfEqeMMLEKSfxl8aFTxRpJhG-N9EASEgQjH_YqhS365.bMnWrnjcYKCpBodg)
    2. [Raw Notes](./data/user_research_demetre_rawnotes.txt)
    3. [Survey Interview](./data/user_research_demetre.pdf)

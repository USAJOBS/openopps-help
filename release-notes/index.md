---
layout: default
redirect_from: /what-is-new/
permalink: release-notes/
section: release-notes
category: release-notes
title: What's new with Open Opportunities
---

## Changes made March 31, 2023
### Sitewide

* Completed updates to Node.js and moment.js.
* Completed research on back-end code for adding ranking tables.
* Revised the text on the modals that display when approving an internship from the sitewide administrators manage internship table.

### Internships

* Changed the text **Publish** to **Approve** that displays when a sitewide or community administrator views the **internship detail** page. 
* Added the ability for internship creators to include a **Sub-agency** or **Program office**.
* Updated the following sections to display the **Sub-agency** or **Program office**:
  * Internship detail page
  * Internship creation review page
  * Internship search card
  * Internship application right rail

* Added the ability for internship creators to include a language requirement for internships.
* Updated the following pages to display language requirements:
  * Internship detail page
  * Internship creation review page

* Added a description of the language skill level to help creators select the correct proficiency level during the internship creation process.
* Added a modal that displays when a creator or co-owner deletes a required language during the internship creation process.
* Added a modal that displays when a creator or co-owner clicks **Delete** on the internship detail page that’s in draft status.
* Updated the **internship search card** to display:
  * The number of applicants who have applied.
  * The applicant cap number of an internship.

* Updated the **internship creation review** page to display co-owners.

### Bug fixes

* Fixed an issue with validation text displaying when a co-owner uses the Add co-owner text field to add themselves to an internship.

## Changes made March 17, 2023
### Sitewide 

* Completed research on backend changes to support Azure KeyVault.
* Updated the **Submitted** table on the sitewide administrators **Manage internships** page to rename the column heading from **Publish** to **Approve**. 

### Internships 

* Updated the cycle field to auto-populate when duplicating an internship.
* Updated the **community dropdown field** to auto-populate when creating an internship from the **Community Profile** page.
* Added validation to prohibit internships in the same cycle from having the same title.
* Added an **overseas checkbox and text field** to display when creating an internship.
* Updated the internship detail page to display overseas locations.
* Made several changes to the **Internship application step 1** page:
  * Updated the **Statement of interest** text and added markdown to the text field.
  * Updated the **internship location** option to default as virtual.
  * Added a co-owner selection search field. 

### Communities 

* Updated the **Submitted** table on the community administrator’s **Manage internship** page to change the name **Agency** to **Organization** in the **Sort by** feature. 

### Bug fixes 

* Fixed incorrect text of “No tasks” that was displaying on the **Manage internship** table when there are no internships.
* Fixed the UAT banner so it will display on the community’s page of the Open Opportunities UAT site.   

## Changes made March 3, 2023 
### Sitewide 

* Redesigned these banners to use the slim banner design:
  * Update your profile
  * Get recommended opportunities based on your profile
  * When an administrator is editing another user's opportunity.
  * When an administrator is viewing another user's profile. 

* Updated the test banners on the test and user acceptance test site.
* Removed auto hyphens from syllable and line breaks in various locations across the site.
* Updated the initializer templates to have compatibility with Elastic 8.x.
* Updated the landing page to prevent perpetual API calls.
* Revised the top contributor infographic on the **Sitewide administrator’s dashboard** to separate the internship data from opportunity data.
* Completed research on adding a calendar of events to the site.
* Revised the look and feel of the **Privacy settings** section for federal and contract users.
* Added an **X** icon for removing badges on individual badges.
* Added a slim banner that displays when an administrator is editing another user's internship.
* Updated the federal employment text that is displayed on the **Create a profile to join** page.
* Updated the email address to be a link on the **Account settings** page.  

### Networking 

* Updated the search bar on the **Networking** page.
* Updated the **No results** text that displays on the **Networking search** page.   

### Opportunities 

* Updated the search bar on the **Opportunities search** page.
* Added functionality so co-owners can remove themselves from an opportunity.
* Updated the **Step 1 opportunity creation** page:
  * Changed the card fill color when selecting how many people are needed for an opportunity.
  * Changed the card fill color when selecting the type of commitment for the opportunity.
  * Revised the card shapes to have rounded edges.
  * Stacked the radio buttons for the specific questions.
  * Updated the field sizes to match.  

* Reduced the text length on the **Opportunity search banner**.
* Updated the color of the modal that displays when publishing an opportunity.
* Updated the **No results** text that displays on the **Opportunity search** page.  

### Internships 

* Revised the formatting of the internship **Completed on date**.
* Reduced the text length on the **Internship search banner**.
* Updated the **No results** text that is displays on the **Internship search** page.  

### Communities 

* Removed the user’s agency name that displays in the members section of a closed community.
* Updated the **Communities** page search bar.
* Updated the **Community search** page search bar for both opportunities and internships.
* Updated the **Community discussion** page search bar.
* Moved the **Custom survey links** section to the communication drawer on the **Community settings** page.  

### Bug fixes 

* Fixed the test site banner so it displays on the communities’ page of the test site.
* Fixed the opportunity and internship application resumes so they download as the correct file type. 

## Changes made February 17, 2023
### Sitewide

* Completed research for the future contact us page.
* Replaced several success banners with a smaller “snack bar” design that displays when a user:
  * Creates a draft opportunity or internship.
  * Withdraws an internship application.
  * Cancels an internship.
  * Sends an opportunity invite email.
  * Deletes multiple messages on the **Messages** page.
  * Saves a story.

* Redesigned the **Stay informed banner** that displays on the sitewide **Events** page to a slim banner.
* Updated the color of the **Edit** button that displays in the **Saved searches** section.
* Removed the **Select all** option from the filters on the **Networking** page.

### Opportunities

* Removed the **Select all** option from the filters on the **Opportunity** search page. 
*	Removed unnecessary text that displays when there are no search results on the **Opportunity search** page.
* Updated the **Opportunity creation** and **Edit step 1** page to use date picker fields.
* Updated the **User profile** page to use date picker fields in the **Manage applicants** section.
* Added more contrast to the text color on the networking ad on the **Opportunity search** page.

### Internships

* Updated the format of the **Completed on** date.

### Communities

* Changed the background color of the **Communities** page to use gray for more contrast.

### Bug fixes
Fixed the following issues:

* Several 508 compliance issues.
* On the **User’s profile** page so multiple organization levels do not display the same data.  
* The **Networking** callout so it’s no longer misaligned.
* Stopping special characters from displaying in the subject line of an email.
* On several pages so the **Sign out** link will not display next to the **Administrator** heading.
* The **Join community** and **Leave community** buttons to update correctly when a user joins or leaves a community.
* On the **User profile** page, fixed the **+ Add badge** button to not overlap with the **Remove** text in the badges section.
* On the **User profile** page, fixed the text in the **About** section and **Skills** section, so it does not extend out of those sections and off the page.
* Removed special characters from the **Save** button on the **You have unsaved changes** modal.
* On the **Featured story card**, fixed the quotations to not overlap with the story content.

## Changes made February 3, 2023
### Sitewide

* Replaced the success banners with a smaller “snack bar” design that displays when a user: 

  * Saves a search.
  * Withdraws an opportunity or internship application.
  * Selects or does not select an applicant.
  * Adds an endorsement.
  * Joins a community.
  * Adds a post to a community discussion.
  * Saves changes on the community settings page.
  * Creates a new community.
  * Creates a new community story.
  * Creates a sitewide event.
  * Deletes a message using the trash can icon found in the message card.
  * Updates their privacy and email settings.
  * Makes changes to the user profile page.
  * Adds or removes a badge from a user’s profile.
  * Creates or edits a community cycle.
  * Submits or updates an internship application.
  * Submits or updates a detail or lateral opportunity application.

### Opportunities

* Updated the **opportunity search** page layout so the filters section top aligns with the search results section. 

### Internships

* Updated the **internship search** page layout so the filters section top aligns with the search results. 

### Bug fixes

* Fixed an issue on the **Add story** page to prevent the user moving back one page if they click their ‘Enter’ key in a text field. 
* Fixed an issue so validation text will display when adding a sub-organization on the **Step 1** page of the opportunity creation process.

## Changes made January 20, 2023
### Sitewide

* Updated the date and time format in the **Administration** section including:
  * Manage Opportunities page 
  * Manage Internships page 

### Opportunities

* Updated the date and time format in the **federal and contract user dashboards**, including:
  * Recommended Opportunities tab
  * Step 4 Opportunity creation review page

### Internships

* Updated the date and time format in the **student user dashboard**, including: 
  * Recommended internships tab
  * Saved searches section. 
  * Step 4 Internship creation review page. 

### Communities

* Created a customized **certificate of completion** for internships in the **VSFS student community**. 
* Added a link to the community profile page in the **Community updated** success banner. 

### Bug fixes

* Fixed an issue with the **Add**, **Edit** and **Cycles** page, so when a user clicks Enter in a text field, they do not navigate away from the page. 
* Fixed an issue with the opportunity cards on the **Opportunity search page**, so the community’s name does not overlap the agency name.


## Changes made January 6, 2023
### Sitewide

* Synced the Open Opportunities occupational series data table with the USAJOBS data table. 
* Updated the date and time format across the site: 
  * Home page
  * Profile page
  * Networking page
  * Opportunity and internship cards
  * Opportunity and internship detail page
  * Messages page
  * Community profile and discussion pages
  * Sitewide, agency and community administration pages
  * Manage users page
  * Manage opportunities and internships page
  * Featured event card

* Increased the standard line height for text to 1.54 across the site including: 
  * Main CSS
  * Profile page
  * Demographics section
  * About me page
  * Edit profile page
  * Skills page (student users)
  * Skills and mentorships page (federal and contract users)
  * Sitewide, agency and community administration dashboard pages
  * Homepage including the **What’s new** tab and **Post your next project** banner (for federal and contract users)
  * Internship search page including the banner section and internship card 
  * Opportunity search page, including the banner section and opportunity card 
  * Community card, including **Who we are**
  * Community profile page and these sections:
    * Who we are
    * What we do
    * Who can join
    * Key resources 
  * Community discussion page, including the intro text and ground rules in the left rail and the community discussion card title
  * Community internship search page, including the banner
  * Community story page, including the main story text

* Removed oxford commas from the placeholder text in the **Manage Users search bar**.

### Opportunities

* Updated the tracker UI that displays during the opportunity creation process. The tracker helps to navigate through the steps of the creation process. 
* Updated the apply pages for **Detail** and **Lateral opportunities**:
  * Removed the resume upload process content from the right rail.
  * Added resume cards. 
  * Added a modal that displays when a user uploads a resume. 

* Removed oxford commas from the tracker UI on the opportunity creation pages.

### Internships

* Updated the notification emails that we send when an internship has been inactive for 90 or 120 days.
* Removed oxford commas from the tracker UI on the internship creation pages and the right rail of the **Add language** page. 


### Communities

* Added a **My communities** tab to the community page. 
* Updated the community filters to display on the community page when a user is signed out. 
* Moved the **Federal communities** filter to display before the **Student communities** filter on the communities page. 
* Updated the community cards to display **Joined** if a user is a community member. 
* Created a **Community communication** drawer. 
* Added a toggle to display a community logo in emails sent by a community.  
* Enabled community administrators to view a users email address if they are a member of the community. 
* Removed all oxford commas from the the community page and community profile page. 

### Bug fixes
Fixed the following issues:

* Fixed skills engine so it will update when a user creates an opportunity. 
* Removed hyphenation on the Open Opportunities landing page when viewed using Safari. 
* Removed overlapping of the event time and date on the event card. 
* Fixed community administrators so they can view an applicants profile using the applicant tables. 
* Prevented in-progress internships from displaying on the recommended internships page. 

[December 2022](dec-2022)  
[November 2022](nov-2022)  
[October 2022](oct-2022)  
[September 2022](sep-2022)  
[August 2022](aug-2022)  
[July 2022](jul-2022)  
[June 2022](jun-2022)  
[May 2022](may-2022)  
[April 2022](apr-2022)  
[March 2022](mar-2022)  
[February 2022](feb-04-2022)  
[January 21, 2022](jan-21-2022)  
[January 7, 2022](jan-07-2022)  
[December 10, 2021](dec-10-2021)  
[November 26, 2021](nov-26-2021)  
[November 12, 2021](nov-12-2021)  
[October 29, 2021](oct-29-2021)  
[October 15, 2021](oct-15-2021)  
[October 1, 2021](oct-01-2021)  
[September 17, 2021](sep-17-2021)   
[September 3, 2021](sep-03-2021)  
[August 20, 2021](aug-20-2021)  
[August 6, 2021](aug-06-2021)  
[July 23, 2021](jul-23-2021)  
[July 9, 2021](jul-09-2021)  
[June 25, 2021](jun-25-2021)  
[June 11, 2021](jun-11-2021)  
[May 28, 2021](may-28-2021)  
[May 14, 2021](may-14-2021)  
[Aoril 30, 2021](apr-30-2021)  
[April 19, 2021](apr-19-2021)  
[March 19, 2021](mar-19-2021)  
[February 5, 2021](feb-05-2021)  
[January 22, 2021](jan-22-2021)  
[December 11, 2020](dec-11-2020)  
[October 30, 2020](oct-30-2020)  
[October 16, 2020](oct-16-2020)  
[October 2, 2020](oct-02-2020)  
[September 18, 2020](sep-18-2020)  
[September 4, 2020](sep-04-2020)  
[August 21, 2020](aug-21-2020)  
[August 7, 2020](aug-07-2020)  
[June 12, 2020](jun-12-2020)  
[May 29, 2020](may-29-2020)  
[May 15, 2020](may-15-2020)  
[May 1, 2020](may-01-2020)  
[April 17, 2020](apr-17-2020)  
[March 31, 2020](mar-31-2020)  
[March 23, 2020](mar-23-2020)  
[March 6, 2020](mar-06-2020)  
[February 21, 2020](feb-21-2020)  
[February 7, 2020](feb-07-2020/)  
[January 27, 2020](jan-27-2020/)  
[January 13, 2020](jan-13-2020/)  
[December 30, 2019](dec-30-2019/)  
[December 2, 2019](dec-02-2019/)  
[November 4, 2019](nov-04-2019/)  
[October 21, 2019](oct-21-2019/)  
[October 7, 2019](oct-07-2019/)  
[July 15, 2019](jul-15-2019/)  
[June 19, 2019](june-19-2019/)  
[January 11, 2019](jan-11-2019/)  
[November 16, 2018](nov-16-2018/)  
[June 29, 2018](june-29-2018/)  
[May 18, 2018](may-18-2018/)  
[March 9, 2018](mar-09-2018/)

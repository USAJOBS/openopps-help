---
layout: default
redirect_from: /what-is-new/
permalink: release-notes/
section: release-notes
category: release-notes
title: What's new with Open Opportunities
---

## Changes made May 12, 2023
### Sitewide

* Updated a backend table to keep a record of when a creator clicks the **Confirm applicant selection** button for auditing purposes.
* Added the ability for sitewide administrators to view and use the action buttons on the applicant tables of an internship and on the **Application view** page of an applicant.
* Added an **information icon (i)** with alt-text on the **Demographics** page to describe specific selections.

### Communities

* Updated the **Search applicants table** for student cyclical communities, to include a new column called **Application submitted date** and added the ability to sort by this date.
* Updated the **Manage users table** for student communities with the following:
  * Added a column with the login.gov email address of community members.
  * Added a sort by for sorting by the login.gov email address of users in alpha order.
  * Revised the placeholder text of the search bar and enabled searching by login.gov email address.Created an internship ranking toggle for student cyclical communities.

### Internships

* Changed the **Update application** button to **Update draft application** if the user has started an application but not submitted it yet.
* Added functionality to not display the **Update draft application** button when a user has reached the application limit for a cycle.
* Added functionality to not display the **Apply** button when an internship has a status of **Approved**.
* Created an **Auto-fill** option for internship applicants to import data used on a previous internship application.
* Added the following to the **Internship application step 4 review** page:

  * A field to capture the Expected graduation date.
  * A field to capture the Degree or level attained.
  * A checkbox for confirming acknowledgement of the rules and requirements of applying.
  * Text informing the applicant when there are no languages to display and a link to the Add a language page.\

* Added an **internship ranking table** to the **student dashboard** page.
* Added text below the internship ranking table to display the number of applications that a user can submit in the internship cycle.
* Added functionality to display a **Search for open internships** button instead of the **Apply** button when an applicant reaches the application limit. The revised button takes the applicant to the **Internship search** page.
* Updated the internship applicant cap and count to display on the internship detail page when a user is signed out.
* Updated the internship right rail section to display text informing the user when they have reached the application limit for a cycle.
* Added functionality to the **References** section to not display the **Phone** or **Email** headings when that information is not provided.
* Updated the **Participated table** on the **student dashboard** page to add a column for **Application submitted date**.
* Added the **Expected graduation date** and **Degree or level attained** to the **Application view** page.
* Added functionality to automatically move an applicant to the **Rejected table** when they decline an internship offer.
* Updated the **Selected applicants table** and the **Application view** page to display **Applicant has accepted** when an applicant accepts an internship offer.

### Bug fixes

•	Fixed an issue so the cycle selection dropdown will now display when editing an internship.

## Changes made April 28, 2023
### Communities

* Created a toggle to turn off and on the two-year validation text for the **Expected graduation date fields** on the **Internship application step 2** page.
* Updated the **Manage users table** to remove federal and contract members of a student community if they do not provide a federal email address.
* Updated and organized the downloadable .csv links on the **student community dashboard** page.
* Created an education report (.csv) for student cyclical communities.
* Added an **Application limit toggle** to the **community setting page** to limit the number of applications a student can submit in a student community cycle.

### Internships

* Updated the **Step 3 application** page to include text fields for adding skills.
* Created an **Approved** status for internships that have been approved but are not yet open.
* Updated the **student profile** page so users can sort the education.
* Changed the button text on the **Confirm approval** modal to **Approve** instead of “Publish”.
* Updated the **What happens next?** page to move the demographics text from the main section to the right rail.
* Revised the design of the success banner that displays when a student applies to an internship. The banner now uses the slim design.
* Updated the **student application process** with the following:
  * Added the internship creator and co-owner names to the right rail informational text section.
  * Added required languages and proficiency levels to the right rail informational text section.
  * Added the student’s education details to the **step 4 review** page.

* Updated the **internship detail** page to display a **max application warning** when a student has reached the application limit of a cycle.  

### Bug fixes

* Fixed an issue on the **Step 1 internship creation** page, so if user hits the "Enter" key on any free form text field, they do not go to the **Add a language** page.
* Fixed several 508 issues.

## Changes made April 14, 2023 
### Sitewide 

* Updated the data and title of the **TopContributors_FY23_created.csv** file that is on the sitewide administrator dashboard page.
* Completed **Azure KeyVault additions and code changes**.
* Updated the federal employment statement on the **Edit profile** page. 

### Opportunities 

* Added a **Reimbursable** search filter to the **opportunities search** page. 

### Internships 

* Removed the blue **What happens next?** section that displays when a creator creates a cyclical internship.
* Removed the **Internships** section from the **student profile** page.
* Added an **Education** section to the **student profile** page.
* Added an **Expected graduation date** field and a **Degree or level attained** dropdown to the **Step 2 internship application** page.
* Updated the **Add a reference** page found during the **internship application process** to allow for an email address or phone number, but not both. 

### Bug fixes 

* Fixed an issue where community administrators could not see the red “X” icon used for deleting internships from the **Manage internships** tab. 

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

[February 2023](feb-2023)  
[January 2023](jan-2023)  
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

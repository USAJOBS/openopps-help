---
layout: default
redirect_from: /what-is-new/
permalink: release-notes/
section: release-notes
category: release-notes
title: What's new with Open Opportunities
---

## Changes made November 14, 2022
### Sitewide

* Redesigned the **Open Opportunities home page**.
  * Created six new sections highlighting:
    * A purpose statement
    * A value statement
    * An opportunity definition
    * Stories 
    * Create an Opportunity or Internship section
    * Events

* Created a CMS section so sitewide administrators can make updates to the home page.  
* Added **Skills engine match tracking** to a backend audit table. 

### Internships

* Updated **Step 1 of the internship creation** page – for the **Do you want to post this to a specific community?**, it now defaults to Yes.

### Communities

* Removed the min-height and max-height for banner images that display on the **Community profile** and **Community discussion** pages.  

### Bug fixes

* Fixed the message count to display correctly when deleting messages on the **Messaging** page. 
* Fixed the sub navigation menu to display when a user refreshes the **Messaging** page after deleting all messages on the page. 
* Fixed an issue so internship owners and co-owners no longer receive applicant selection emails for internships created in different cycles. 


## Changes made October 31, 2022
### Sitewide

* Updated the **Messaging page** to display the message count as (XXX) next to the **Select all** checkbox. 
* Removed the messages count from the **Mark as read** and **Delete messages** buttons. 

### Internships

* Updated **Skills matching** for student internships:
  * Created an API to interface with the skills engine and the **Skills and About** section in a student profile.
  * Created an API that checks for skills in a student profile when a student signs into Open Opportunities.
  * Created an audit table capturing API calls for internships. 
  * Created a **Recommend internships** tab that will display matching internships for student applicants based on the skills in their profiles.  
  * Added **Good**, **Better** and **Best** skills match indicators to the internship search cards and **Internship search** page. 
  * Updated the **Sort by** on the **Internship search** page to include a **Profile match** option.
  * Added **Profile match** search filters of **Good**, **Better** and **Best** to the **Internship search** page. 

### Bug fixes

* Fixed an issue where student internship applicants were showing as selected in the student_community_internships.csv report when they withdrew from an internship.  


## Changes made October 17, 2022
### Sitewide

* Updated the **Messaging page**: 
  * Added a message count next to the **All messages** text.
  * Updated the page layout.
  * Added the ability to select individual message cards using a checkbox. 
  * Added the ability to delete multiple messages at once. 
  * Added the ability to mark multiple messages as read at once.
  * Added a modal that displays when a user deletes multiple messages. 

* Updated the timing of the email sent to sitewide administrators when an internship is created—now it will only be sent when an internship is created outside of a community. 

### Internships

* Added text to the **Internship view page** showing applicants how many days they have left to accept or decline an internship. 
* Updated the co-owner view of the Opportunity detail page to display the right rail. 
* Updated the internship applicant table for creators to rename **Matching skills** to **Skills**.

### Communities

* Created a new email to send to community administrators when a new internship is created in their community. 

### Bug fixes

* Fixed several 508 compliance issues. 
* Fixed an issue so the search box on the **Networking page** no longer shows job series codes and descriptions in the autocomplete dropdown. 


## Changes made September 30, 2022
### Internships

* Updated the internship card on the search page to:
  * Add the community name. 
  * Add a fade to the text of the card.  

* Added the ability for co-owners to remove themselves from an internship. 
* Removed the action buttons from the **Selected**, **Rejected** and **Applicants** tables when an internship status is **Canceled**. 
* Removed the action buttons from the applicant view page of an internship when an internship status is **Canceled**. 
* Revised the link on the “selected for an internship” email to students to make them sign in before going to the internship page. 
* Created reminder emails that will go to students one day and four days before the seven day **accept or decline period** closes. 
* Updated the co-owners view of an internship to display the right rail.
* Added an **Undo** remove button to the right rail of the applicant view page. This button will only display when a student has been removed from an internship.  

### Opportunities

* Updated the co-owners view of an opportunity to display the right rail.

### Communities

* Added a customizable signature line to emails sent from a community. 

### Bug fixes

* Fixed an issue where validation text would display when the **Apply by** date was updated on an internship. 
* Fixed an issue where an applicants accept or decline status carried over into a new community cycle.  
 

## Changes made September 16, 2022   
### Sitewide

* Updated the **Sign out** page to include the link Search for internships and to automatically redirect to the landing page after 60 seconds, if no action is taken.
* Updated backend notifications to check for internship inactivity at the 90 and 120 day mark from last change.  

### Sitewide administration

* Made the following changes to the **Manage internship** page for sitewide administrators: 
  * Removed the **Not open** radio button. 
  * Moved the **In review** radio button to be between the **Open** and **In progress** radio buttons. 

### Internships

* Created two new notification emails that will go to internship creators when: 
  * An internship has been inactive for 120 days.
  * An internship has been inactive for 90 days. 

* Added the ability for creators and co-owners to remove an applicant from an internship. 
* Added a **Removed** table on the **Internship page** that shows applicants who have been removed from an internship. 
* Added a modal that displays when a creator removes an applicant from an internship. 
* Removed the ability to click on a creators icon and name when viewing the internship page as a student. 
* Created an application status of **Complete** that will display on the student dashboard when they complete an internship. 
* Added a **Search by** section to the student dashboard.

### Communities

* Updated the **Community settings** page to include a toggle for removing the actions buttons from the **Selected**, **Rejected** and **Applicants** table while an internship is in progress. 
* Disabled the **Mark internship complete** button when an internship, created in a cycle, has not passed the last date of the internship dates. 
* Added a column of **Cycle_name** to the student_community_internship download file.
* Added a **Sort by** to the manage cycles page. 
* Updated the **Community settings** page to move the **Applicant cap** toggle to the **Apply process drawer**. 
* Updated the **Community profile** page of student communities to include a **Create internship**. 

### Bug fixes

* Fixed an issue where sitewide administrators could not remove a user from a community using the account settings page. 
* Fixed an issue that was not allowing creators to add or remove co-owners from an internship. 

## Changes made September 2, 2022   
### Sitewide

* Added date picker fields to the Create a report modal.  

### Sitewide administration

* Updated the **Manage internships** table to include a radio button for Approved.
* Added new filters to the **Filter by** feature within the **Manage users** table:
  * Students
  * Federal
  * Contractor

### Opportunities

* Updated the **Show endorsements** on your profile modal to default to **Yes**. 

### Internships

* Added a daily countdown to the Waiting on a response text that creators and co-owners see after submitting an internship offer. 
* Updated the **Internship Creation Review Step 4** to reorder the text in the blue details section.

### Communities

* Updated the **Applicants** column on the **manage_internship.csv** to show the number of applicants who fully submitted an application. 
* Added three new statuses to the community dashboard page for cyclical communities:
  * In review
  * In progress
  * Canceled

* Updated the **Search applications** page, in student communities, to include pagination.
* Updated the layout of the community discussion page banner. 
* Updated the layout of the student community internship search page banner. 
* Updated the text of the **Approve all** modal displayed in student communities. 
* Added success banners when creating or editing a cycle in a cyclical student community. 
* Updated the community dropdown for sitewide and community admins to show the active communities first. 

### Bug fixes
Fixed the following issues:

* The community heading would still display on the internship creation review page when no community was selected. 
* The community filter pill could not be removed from the internship search page once selected. 
* Special characters were being displayed in the “student_community_internships.csv”. 
* The estimated start and end dates of the internship detail page was not matching the estimated start and end dates of the internship apply pages. 
* The application due dates on the “student_community_internships.csv” were not correct.  
* An internship created in a cyclical community would move to a status of “Open” before first date of the application dates had passed. 
* The applicant cap validation text would display on the internship creation step 1 page when the applicant cap was toggled off. 
* The spacing on the applicant tables found on the internship detail page. 
* An issue where it was possible to have two communities with the same community name. 

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

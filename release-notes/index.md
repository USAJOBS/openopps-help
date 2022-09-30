---
layout: default
redirect_from: /what-is-new/
permalink: release-notes/
section: release-notes
category: release-notes
title: What's new with Open Opportunities
---

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

## Changes made August 19, 2022
### Internships

* Updated the student application page to display their university and major and minor. Internship creators can now see this information when viewing an application. 
* Updated the applicant view of the internship page to include the following:
  * Text that says “You have declined this internship offer” when the applicant has declined the internship.
  * Text that says “You have accepted another internship offer” when the applicant has accepted a different internship.

* Updated the Internship creator view of the **Rejected applicants** table to include “This applicant has accepted another internship offer” when the applicant has accepted a different internship.
* Removed the **Action** column on the **Selected**, **Rejected** and **Applicants** table when an internship has a status of complete. 
* Removed the **Action** buttons on the **internship application page** when the internship has a status of complete. 
* Added a **Mark task complete** button to the **application view page**. 

### Communities

* Added the ability for student community administrators to see the owners section of an internship. 
* Updated the status of internships with an applicant cap to:
  * Automatically move to **Reviewing applicants** when the applicant limit is reached. 
  * Automatically move back to **Open** if an applicant withdraws their application after the applicant limit is reached. 

### Bug fixes

Fixed the following:

* Several 508 issues. 
* The **Unselect** button to be the correct color in the **Selected applicants** table. 
* Removed the **Action** column from the **Selected applicants** table when signed in as a sitewide administrator.
* A timing issue so internships that are **Open** continue to display in the search page after 8 PM EST. 
* The validation text that displays when updating the **Apply end date** of a student community cycle. 
* The application due date on the:
  * **Internship card** and the **internship page** so they match. 
  * **Participated** table of student’s dashboard and the **internship page** so they match.  
  * **Saved internships** table of student’s dashboard and the **internship page** so they match.  
  * **Internship share link** email and the **internship page** so they match. 

* The help link next to the internship status section to send users to the correct page. 


## Changes made August 5, 2022
### Internships

* Updated student application statuses to display their status after applicant selection.  
* Created the following emails that will be sent to:
  * Student applicants telling them they have seven days to accept or decline an internship.
  * Internship owners and co-owners when a student has accepted an internship.
  * Internship owners and co-owners when a student has accepted a different internship than the one they have ownership of.
  * Internship owners and co-owners that a student has declined their internship. 

* Updated the email sent to internship applicants after they apply to display “We received your application…”. We removed the text “In the next few days” and “Keep checking the site as we frequently add new internships”.
* Added student application statuses of **Offer declined** and **Offer accepted** to display on the student dashboard. 
* Updated the **Participated table** on student dashboard to include a sort by **Application last updated**.

### Communities

* Created a .csv file and download link containing data related to community interactions for a cyclical student community. 
* Updated the title of the manage users .csv file found in student communities to “student_community_users”.  
* Created a .csv for student community members who “applied to, but were not selected for” student internships.    

### Bug fixes

Fixed the following issues

* skills were not displaying on a student’s internship application. 
* A download link was not displaying on the manage users page for community administrators. 
* A coding issue that caused a debug error when an internship creator selected the Complete applicant selection button. 

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

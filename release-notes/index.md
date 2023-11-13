---
layout: default
redirect_from: /what-is-new/
permalink: release-notes/
section: release-notes
category: release-notes
title: What's new with Open Opportunities
---

## Changes made November 13, 2023
### Sitewide

* Removed Skills Engine matching elements and all text referencing Skills Engine.

### Opportunities

* Added a comment section to the right rail of the **Opportunity detail** page.  Administrators, creators and co-owners of an opportunity can use the comment section.
* Added the ability to edit or delete comments.
* Added a snack bar notification that displays when a user deletes a comment from the opportunity.

### Internships

* Added a comment section to the right rail of the **Internship detail** page.  Administrators, creators and co-owners of an internship can use the comment section.
* Added the ability to edit or delete a comment.
* Added a snack bar notification that displays when a user deletes a comment from the internship.  

## Changes made October 27, 2023
 
### Sitewide enhancements

Added the following:

* A trim function to the name fields of the Open Opportunities welcome page.
* A **Contact us** page so users can submit information to the help desk.
* A snack bar that displays when a user successfully submits the **Contact us** form.
* A **Contact us** link in the footer.

* Updated the following tables to pull updated data from USAJOBS:

  * Pay plan table
  * Country table
  * Country subdivision table

### Opportunities

* Continued work on the right rail re-design of opportunities. This redesign has not been released yet.
* Updated the **profile pages of federal users** to include an ad for the **Federal Mentoring community**.

### Internships

* Update the right rail of the **What happens next?** page to include an ad for the **Virtual Student Federal Service community**, when a user submits an application for an internship.
* Updated the **Applicants table** to display the student application status as **Not selected** when the internship has a status of **In-progress**.

### Communities

* Made the following updates to the students_selected.csv file, used by community administrators of student cyclical communities:
  * Removed the **student_name** column.
  * Added a **student_first_name** column.
  * Added a **student_middle_name** column.
  * Added a **student_last_name** column.
  * Added a **student_profile_id** column.

* Made the following updates to the rejected_applicants.csv file that is used by community administrators of student cyclical communities:
  * Removed the **student_name** column.
  * Added a **student_first_name** column.
  * Added a **student_middle_name** column.
  * Added a **student_last_name** column.
  * Added a **student_profile_id** column.

* Updated the **community_internships.csv** to add the applicant profile id to the **selected_applicants column**. This file is used by community administrators of student cyclical communities.
* Updated the **Education.csv** to add an applicant’s internship task id to the **No_internships_selected_for column**. This file is used by community administrators of student cyclical communities.

## Changes made October 13, 2023
### Opportunities

* Continued work on redesigning the right rail section of the opportunity detail page. This redesign has not been released yet.

### Internships

* Updated the cycle dropdown to display the original internship cycle when a sitewide or community administrator edits a cyclical internship.
* Created an automatic process that will withdraw all student applicants from an internship when the internship is canceled.

## Changes made September 29, 2023
 
### Internships

* Updated a student’s application status to **Not selected** when:
  * A sitewide administrator removes an applicant from an internship when the internship is **In progress** and the applicant is in the **Selected applicants table**.
  * A sitewide administrator removes an applicant from an internship when the internship is **Completed**.

* Updated a student’s application status to **Completed** when:
  * An applicant is in the **Selected applicants table**, has been marked task complete, and the internship is **Complete**.  

* Updated a student’s application status to Not complete when:
  * An applicant is in the **Selected applicants table**, has not been marked task complete, and the internship is **Complete**.

* Updated a student’s application status to **Not selected** when:
  * An applicant is in the **Rejected applicants** or **Applicants table** and the internship is **Complete**.

### Community

* Added the following data points to the community administrators **Education.csv** file:
  * Middle name
  * Expected graduate date

* Revised the messaging that displays on the **Step 1 internship creation** page when there are no cycles available to “This community has no available cycles.”.
* Disabled the internship tracker when editing an internship in a community that does not have an available cycle.
* Updated the community administrators **Selected_applicants.csv** file:
  * Revised the download link text to **Selected_applicants.csv**.
  * Removed the **Withdrawn** column.
  * Removed the **# of internships the applicant has applied to** column.
  * Removed applicants who have withdrawn from an internship.

* Updated the community administrators Rejected_applciants.csv file:
  * Removed the **Withdrawn** column.
  * Removed the **# of internships the applicant has applied to** column.
  * Removed applicants who have withdrawn from an internship.
  * Updated the file name to **Rejected applicants**.

* Updated the **Manage internships** page of a cyclical community
  * Changed the cycle dropdown to default to the most recently created + active cycle.
  * Added text to the cycle selection dropdown to indicate which cycles are active and inactive.

* Updated the **community administrators search application table** to display an applicant’s current application status. 

### Bugs

* Removed an extra space between a student’s first name and last name on the community administrators **Selected_applicants.csv** report.
* Fixed the **accept/decline text** that displays on an applicant’s application detail page so it shows the correct text if they are not selected for an internship.

## Changes made September 15, 2023 
### Opportunities

* Created a feature toggle for the upcoming redesign of opportunities.

### Internships

* Added a modal that displays when a user tries to apply to an internship twice from different browser windows.

### Bugs

* Fixed an issue so the **Related communities** section no longer disappears when a community administrator updates it.
* Fixed the co-owner search feature when adding a co-owner to an opportunity – users now appear in the search.
* Fixed the **Actions** column to display correctly in the **Selected applicants** table.
* Fixed a broken toggle for displaying a community logo in the community banner.
* Fixed an issue so students can no longer apply to multiple internships.

## Changes made September 1, 2023
### Sitewide

* Added the following actions for Sitewide administrators to update internships when are **In progress** or **Complete**:
  * Remove an intern from an internship.
  * Select an intern that was previously rejected.
  * Select an intern that was not previously selected or rejected.
  * Updated all sitewide toggles from a .svg image to HTML.  
 
### Bugs

* Fixed an issue so the community administrators **Manage internships.csv** does not time out.
* Fixed an issue where users were not able to view their internship applications in the **Your internships** table on the dashboard.
* Fixed the **Help Center** link so it does not go to the wrong page.
* Fixed an incorrect validation message on the **Step 1 opportunity creation** page when a user provides an estimated completion date in the past.
* Fixed an issue where the duration of a community would show as a number instead of text when signed in as a community administrator.

## Changes made August 18, 2023
### Sitewide

* Disabled all user accounts that are inactive.
* Removed the **Back** link from the **opportunity and internship detail** pages when a user goes there from a hyperlink.
* Added a **Completion date** column to the **Manage internships .csv** download for sitewide administrators.
* Added a **Back** link to the **Demographics** page when a user goes there from the **What happens next?** page. 

### Agency

* Added a **Manage internships** page to the **agency administrator’s dashboard** page.
* Added the following tables to the **Manage internships** page for agency administrators:
  * In progress
  * Draft
  * Submitted
  * Open
  * In review
  * Approved
  * Completed
  * Canceled

### Community

* Added a **Completion date** column to the **Manage internships .csv** download for student communities.

### Internships

* Updated internships to automatically move to a **Canceled** status if the estimated end date of the internship has passed and the internship does not have any selected applicants.

### Networking

* Added a **Community filter** to the right rail of the **Networking** page.

## Changes made August 4, 2023
### Sitewide

* Updated the primary navigation and secondary navigation menu bars.
* Updated the banners that display when a sitewide administrator is viewing another user’s profile to view the type of user the profile belongs to.
* Removed opportunity data from the sitewide administrator **Manage internships.csv**.

### Communities

* Updated the **cycle selection** dropdown on the **Community dashboard** so it defaults to the most recently created active cycle.
* Updated the search bar on the **Search applications** page for cyclical communities to persist when no search results display.
* Updated the **Add member to community** modal to include searching by a user’s email address.

### Opportunities

* Updated the color and text of the following status icons:
  * Applied
  * Not assigned
  * Assigned
  * Submitted
  * Not open
  * Draft
  * Open
  * In progress
  * Completed
  * Reviewing applicants

* Added markdown functionality to the **Statement of interest** field on the **Opportunity application** page for lateral and detail opportunities.
* Changed the **Opportunity renewal** success banner to a display as a snack bar.

### Internships

* Updated the color and text of the following status icons:
  * Application started
  * Withdrawn
  * Submitted
  * Not open
  * Draft
  * Open
  * In progress
  * Completed
  * Reviewing applicants

* Updated the design of the success banner that displays when a creator completes an internship.
* Added modals that display when an internship applicant’s resume or transcript is not downloadable.

### Bugs

* Fixed an issue with the **postal code** field on the **Profile edit** and **Create a profile to join** pages so the system recognizes valid postal codes.
* Fixed an issue with the tooltip for the **Selected_students.csv** so it displays in the correct location on the **Community dashboard** page.

[July 2023](jul-2023)  
[June 2023](jun-2023)  
[May 2023](may-2023)  
[April 2023](apr-2023)  
[March 2023](mar-2023)  
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

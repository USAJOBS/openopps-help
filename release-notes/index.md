---
layout: default
redirect_from: /what-is-new/
permalink: release-notes/
section: release-notes
category: release-notes
title: What's new with Open Opportunities
---

## Changes made June 7th, 2024
### Communities
*	Created a function to restrict access to community profile page URL for users with community profile page toggle set to "Off".
*	Moved email signature block from community configuration to community communication drawer.
*	Moved the "Certificate of completion" toggle and elements to the Community communication drawer.
### Opportunities
* Updated error messages related to "Apply by date" on step 1 create page.
* Removed the "Relevance" option from the "Sort by" dropdown list on the opportunities search page.
* Created a "View application" link on the right rail of the profile page.
* Removed the help link and icon above the progress bar on the right rail of the opportunity detail page.
* Updated "Cancel this opportunity" modal text.
* Created a success snack bar when user leaves a community to acknowledgment of successful action taken.
### Internships
*	Created a backend elastic search that moves students to the available students page when the cycle end date is met.
*	Created email notification to creators and co-owners when an internship moves from "Open" to "Reviewing applicants" status.
*	Updated the text color and removed bookmark icon for applicants moved to rejected table with no internship offer.
*	Created an autofill function to the agency dropdown on the step 1 internship creation page based on user’s profile.
*	Updated the sub-agency or office field to be required when a user selects "Department of State" on the internship step 1 creation page. 
*	Updated text on the cancel internship modal.
*	Created function to hide certificate of completion if a student has been removed from an internship that has status of "Completed".
*	Created function for community managers to duplicate an internship created in their community.
*	Updated text in the informative drawer displayed above the "Selected applicants" table.
*	Updated "Removed Applicants" table title to sentence case.
*	Updated "Student accepted another internship" email with associated internship title.
*	Created a function to automatically delete draft internships after 1 year of being in a draft status.
*	Updated the Internship dashboard to include commas to numbers that displays over 3 digits.
*	Created an "Apply by date in the past" banner to prevent admins from publishing an internship that has an apply by date in the past.
*	Created validation function to prevent internship creators from duplicating internship title within the same cycle.
*	Updated error messages related to "Apply by date" on step 1 create page.
*	Removed "Relevance" option from the "Sort by" dropdown list on the internship search page.
*	Added a "Cycle" column to the created table on the user’s dashboard page.
### Bugs
* Fixed an issue where cycle validation message was not displayed when there are no active cycles.







## Changes made May 24th, 2024
### Communities 
* Updated the following reports with new columns: 
  * "Community_internships_[cycle name]" .csv download with "creator_id and  "co_owner" columns.
  * "Search applications" page .csv download with "creator_id" and "co_owner_id" columns.
  * "Student_community_users" .csv download with “user_id column".
  * "Not_selected_applicants" .csv download with " "Student_profile_id" and "Removed_reason" columns.
* Updated the community_internships_VSFS [cycle] .csv “Location” column to include overseas location and display as virtual.
* Created a student cyclical non-member .csv report to account for users that are not members of the VSFS community but have created, co-owned, or applied to an internship within the VSFS community.
* Created a "Non-member" section on the student community dashboard to display non-member metrics.
* Created a "Non-member (.csv)" download link for student cyclical communities. 
### Internships
* Updated text color of applicant’s name to gray when they declined or accepted another internship offer.
* Created the following discussion/comment functionality within the internship detail page:
  * A discussion section. 
  * A comment view within the discussion section.
  * The ability to reply to a comment.
  * The ability to edit a comment.
  * The ability for users to delete their own comments and sitewide administrators to delete all comments.
* Created a warning modal that displays when a user attempts to delete a comment.
* Created an eamil notification that is sent to creators and co-owners of an internship when a comment is posted.
### Bugs
* Fixed an issue where users were unable to update an internship with no active cycles to advance past step 1 of the create/edit page.
* Fixed an issue where the validation error line for the cycle field is not displayed when the field is left blank and user attempts to advance past step 1 of create internship page.
* Fixed an issue where an error occured when a discussion is posted in a community.


## Changes made May 10th, 2024
### Technical

* Removed duplicate internship applications from a backend data table.

### Internships

* Created an informative banner to notify internship owners and co-owners that a student did not apply to an internship when selecting a student via the available students page. 
* Added an "Agreement form" column to the following locations:
  * The student dashboard page.
  * The created table of the federal and and contract users dashboard page. 
* Created an agreement form download link in the selected applicants table.
* Created an agreement form download modal for selecting an agreement form by internship participant.
* Created an agreement form page for viewing and downloading the internship agreement form.
* Upated the view link and icon in the tables of the internship detail page.
* Updated the "Removed intern from this internship" section to display for community administrators.

### Sitewide
* Updated the "Budget and Performance" footer link to "Reports and publications".
* Updated the "Privacy policy" footer link to display in a smaller font size.
* Updated the "Terms and conditions" footer link to display in a smaller font size.

### Bugs
* Fixed an issue where users were able to access the community profile page of a community when the profile page was toggled "Off" on the community settings page.
* Fixed an issue where the internship completion certificate was not displayed correctly. 
  

 
## Changes made April 26, 2024
### Communities

* Updated the elastic search functionality to populate the **Available students** page. The search will look for students who are not actively participating in an internship for a given cycle.
* Updated the **Available students** page:
  * Created a keyword search.
  * Added filters for bookmark, education selection and language.
  * Created view count and pagination to determine the number of applicants for a given cycle.
  * Created a no search results page to display when there are no results.
  * Added a **Sort by** option to sort the students by **Name** or **Major** in alphabetical order. 

## Changes made April 12, 2024
### Communities

* Created a new **Available students** page. The page includes:
  * a dropdown to select the student cycle.
  * a list of each student that is available and their details.

* Added **Available students** to the secondary navigation.
* Created a new **application review** page that displays a student’s information in the right rail and their most recently submitted application to an internship.
  * This page also includes the ability to bookmark the student, and ability to select the student for an internship.  

* Created a snack bar that displays when a creator selects an internship applicant from the application review page.
* Updated the search feature to add and remove internship applicants from the **Available students** page.

### Internships

* Changed the time zone for the **Apply by date** field on the internship creation step 1 page from EST to ET.  

### Opportunities

* Changed the time zone for the **Apply by date** field on the opportunity creation step 1 page from EST to ET.  

### Bugs

* Fixed an issue where all selected applicants would move to the rejected applicants table when an applicant was selected from the applicants table of an internship.
* Fixed the **Reviewed** label so the color changes to gray as needed on the internship detail page.
* Fixed an issue preventing an overseas location from displaying properly in the selected, rejected, or applicants tables on the internship detail page.
* Fixed the **One-day remaining until offer expiration** email so it is sent on the correct day.
* Fixed a display issue so the community name does not overlap the agency name on the opportunity search cards.
* Fixed an issue so an applicant does not show as declining an internship offer when they are selected after being removed.

## Changes made March 29, 2024
### Communities

* Added a banner that displays on the **Internship detail** page to let creators and co-owners know when an internship does not have confirmed applicants.
* Added a banner that displays on **Internship detail** page to let creators and co-owners know when an internship does have confirmed applicants.
* Added functionality that disables the **Actions** in the **Applicants** table during the **seven day accept and decline period** for creators and co-owners who confirmed their applicant selections.
* Added functionality that will move applicants who have accepted a different internship offer in the same cycle to the **Rejected applicants** table.
* Removed the **Remove from this internship** text from the application review page when an applicant has accepted a different internship offer in the same cycle.
* Created an **Available students** page.
* Added a **Find available students** button to the **Applicants** table of the internship detail page.
* Added an **Available students** secondary navigation menu item.
* Added a **Select cycle** dropdown to the **Available students** page.

## Bugs

* Fixed the **Actions** on the **Applicants** table so they do not display during the **seven day accept and decline offer period**.
* Fixed the opportunity creation date field validation so it displays properly.
* Fixed the primary navigation so it displays correctly on the landing page when a user signs out of the site.
* Fixed an issue where the back button would display on the application review page.

## Changes made March 15, 2024
### Communities

* Updated two emails that are sent to applicants when they are selected or not selected for an internship that is created in a student cyclical community and the **Accept and decline** toggle is set to **On**.
* Updated the **back** link on the **Acceptance agreement** page so users can go back to the internship detail page.
* Made a change that will disable the **action item icons** within the **Applicant** table of an internship during the applicants’ **seven day accept and decline period** if a creator or co-owner has not previously confirmed their applicant selections.
* Created an email that is sent to internship owners and co-owners six days before the internships’ **application due date**.
* Created an email that is sent to internship owners and co-owners when an internships status moves to **In progress**.
* Updated the trigger and content of the email that is sent to owners and co-owners when an applicant they have selected has accepted a different internship offer.
* Added text **Applicant has accepted another internship** to the **Applicants** table when an internship applicant has accepted another internship.

 ### Bugs

* Fixed an issue on the internship detail page to remove the text **Applicant did not respond to your internship offer** that displayed when a creator or co-owner moves an applicant to the **Rejected applicants** table.
* Fixed an issue so users can't submit multiple applications to the same internship.
* Fixed the **No, customize my answers** button so it takes the user to the **step 1 internship application** page.
* Fixed the display of the community logo so it properly displays on the internship detail page to student users or when signed out.

## Changes made March 1, 2024
### Communities

* Created an email that is sent to selected internship applicants when a creator or co-owner selects the applicant while the internship is **In-progress**.
* Added a new process that moves an applicant who does not accept an internship offer within the 7 day offer period to the **Rejected applicants** table of that internship.
* Updated the **Edit cycles** page to disable the **date fields** if the previous dates are in the past.
* Updated the **internship agreement page** to include different language when a creator or co-owner confirms applicants that haven’t been confirmed before.
* Created an **internship agreement page** that displays when a creator or co-owner selects an applicant for an internship that is **In-progress**.
* Added a rule to disable the **Actions** column of the internship detail page during the 7 day accept and decline offer period.
* Added a rule to hide the **Confirm applicant selection** button so it does not display during the 7 day accept and decline offer period when an internship has no confirmed applicants.
* Removed the **Withdraw my application** link from the internship detail page when an internship is in the **Reviewing applicants** status.
* Updated the text of the **Evaluating and selecting applicants** section to include the internship agreement process.

### Bugs

* Fixed an issue with the **sitewide administrators manage internships.csv** file so internships that are **Approved** do not show as **Open**.

## Changes made February 16, 2024
### Communities

Made several updates to support the VSFS community:

* Created a new page for the VSFS agreement—the page displays when a creator or co-owner confirms who they want to select for an internship.
* Created a new page for the VSFS agreement—the page displays when an applicant is selected from the **Applicants** table of an **In progress** internship.
* Added a success message that displays when a creator or co-owner has confirmed their applicant selections.
* Added the internship details to the **applicant confirmation acceptance agreement** page.
* Created an automatic run-book process that moves an internship from **Reviewing applicants** to **In progress** based on the **application review end date** of an internship cycle.
* Created an **Acceptance agreement** toggle that controls the display of the **Acceptance agreement** page when a community requires an agreement.

### Bugs

* Fixed an issue with the **community administrators manage internships.csv** so that approved internships display as **Approved** instead of **Open**.
* Fixed an issue with the **Cycle** dropdown on the **Create internship step 1** page to not show inactive cycles when duplicating an internship.

## Changes made February 2, 2024
### Opportunities

* Continued work on the right rail re-design of opportunities. 

### Communities

* Updated the **community administrator dashboard** to display all active cycles regardless of fiscal year for student cyclical communities.
* Added an **Application review dates** column to the manage cycles page for student cyclical communities. 
* Added **Application review start date and end date** to the create and edit cycles pages. 
* Updated the validation on the **Date range of internship** field to not allow dates that come before the **Application review date**. 
* Changed the link label **Rejected_applicants (.csv)** to **Not_selected_applicants (.csv)**. 
* Updated the file name of the **Rejected_applicants (.csv)** to **Not_selected_applicants_[cycle name]**.
* Updated the file name **Selected_applicants (.csv)** to **Selected_applicants_[cycle name]**.
* Added several columns to the community administrators **Search applications.csv** to display the following information:
  
  * Applicant’s university
  * Applicant’s profile id
  * ID of the internship the applicant applied to
  * Internship creator’s name
  * Internship co-owner’s name
  * Agency of the internship
  * Sub-agency of the internship
  * Location of the internship 

[January 2024](jan-2024)  
[December 2023](dec-2023)  
[November 2023](nov-2023)  
[October 2023](oct-2023)  
[September 2023](sep-2023)  
[August 2023](aug-2023)  
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

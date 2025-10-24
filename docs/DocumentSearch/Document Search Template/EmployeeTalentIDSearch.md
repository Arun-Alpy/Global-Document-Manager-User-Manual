---
layout: default
title: Employee TalentID Search 
parent: Document Search Templates
grand_parent: Document Search

nav_order: 1
---
### Employee TalentID Search
The Employee TalentID Search feature allows users to search for documents in the repository based on a specific TalentID.

Steps to Perform Employee TalentID Search:
- Log in to the system and navigate to the Browse page. Refer to the [User Login](https://pages.github.ibm.com/Global-EJS/GEJS-Australia-EDM-User-Manual/docs/UserLogin.html) section for login information.
- Click the hamburger icon to expand the menu and select Search.
- Expand the All Searches or Recent Searches section and select Employee TalentID Search.
![image](assets/images/est1.png)

**Search Criteria:**
The following fields are available in the search criteria section:

   |Property to Search For |Operator |Mandatory|Dropdown (ChoiceList) |Property Length |
   :--- | :--- | :---| :---| :---|
   |TalentID|Equals|Yes||10|
   |DocumentType|Equals, Include Any|Yes||10|
   |Capture Date|Equals||||
   |Capture Source|Equals|||12|
   
   |![image](assets/images/est2.png)|
   
1. Mandatory Fields:
    - Mandatory fields should not be empty. If a mandatory field is empty, the Search button will be disabled.
    - Include Any Document Types Options are available for selecting multiple document types.
    ![image](assets/images/est3.png)

2. Operators:

    |Name of the Property |Operator Name |Property Type|
    :--- | :--- | :---|
    |TalentID|Equals|String|
    |DocumentType|Equals, Includes Any|String|
    |Capture Date|Equals|Date|
    |Capture Source|Equals|String|
    
    ![image](assets/images/est4.png)

3. Search Button:
    - After filling all the mandatory fields, click on the Search button.
    - The search results section will be loaded with documents based on the values entered by the user.
    ![image](assets/images/est5.png)

**Search Results:**
- Users can view all the information about the document in the Search Results page.
- Refer to the [Search Results](https://pages.github.ibm.com/Global-EJS/GEJS-Australia-EDM-User-Manual/docs/DocumentSearch/CommonFunctionalities/SearchResults.html) section for the list of document properties that will be visible to the user on the search results section.
- If you wish to download the document properties and values, use the [Export Properties Report](https://pages.github.ibm.com/Global-EJS/GEJS-Australia-EDM-User-Manual/docs/Actions/Export.html) feature.

By using the Employee TalentID Search feature, users can quickly and easily find documents related to a specific employee based on their TalentID, making it easier to manage and track documents within the system. 
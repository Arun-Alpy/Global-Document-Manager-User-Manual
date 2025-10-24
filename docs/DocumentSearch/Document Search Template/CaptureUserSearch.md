---
layout: default
title: Capture User Search
parent: Document Search Templates
grand_parent: Document Search

nav_order: 5
---
### Capture User Search
The Capture User Search feature allows users to search for documents based on the user who manually uploaded the document.

**Steps to Perform Capture User Search:**

Log in to the system and navigate to the Browse page. Refer to the [User Login](https://pages.github.ibm.com/Global-EJS/GEJS-Australia-EDM-User-Manual/docs/UserLogin.html) section for login information. Click the hamburger icon to expand the menu and select Search. Expand the All Searches or Recent Searches section and select Capture User Search.

**Search Criteria:**

The following fields are available in the search criteria section:

   |Property to Search For |Operator |Mandatory|Dropdown (ChoiceList) |Property Length |
   --- | --- | ---|
   |DocumentType|Equals|Yes||50|
   |Capture User|Equals|Yes||250|
   |TalentID|Equals|||10|
   |Capture Date|Equals||||
   |Capture Source|Equals|||12|

   ![image](assets/images/cus1.png)

1. Mandatory Fields:
    - Mandatory fields should not be empty. If a mandatory field is empty, the Search button will be disabled.
    ![image](assets/images/cus2.png)

2. Operators:
    - String properties (e.g., Capture User, Capture Source, TalentID, DocumentType) have an Equals operator.
    - Date properties (e.g., Capture Date) have Equals operator.
    ![image](assets/images/cus3.png)

3. Search Button:
    - After filling all the mandatory fields, click on the Search button.
    - The search results section will be loaded with documents based on the values entered by the user.
    ![image](assets/images/cus4.png)

**Search Results:**
- Users can view all the information on the document in the Search Results page.
- Refer to the Search Results section for the list of document properties that will be visible to the user on the search results section.
- If you wish to download the document properties and values, use the [Export Properties Report](https://pages.github.ibm.com/Global-EJS/GEJS-Australia-EDM-User-Manual/docs/Actions/Export.html) Report feature.

By using the Capture User [Search Results](https://pages.github.ibm.com/Global-EJS/GEJS-Australia-EDM-User-Manual/docs/DocumentSearch/CommonFunctionalities/SearchResults.html), users can quickly and easily find documents based on the user who uploaded them, making it easier to manage and track documents within the system.
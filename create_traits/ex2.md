## Exercise 2.1 - Create a Segment

Go to [Experience Cloud UI](https://experiencecloud.adobe.com) and log in with the credentials provided to you. 

Click on "Sign In with an Adobe ID" and log in using email address and password.

![Data Ingestion](./images/login.png)

You are now in the Experience Cloud Welcome screen. Go to the upper right corner and click on the icon with the 9 little bubbles.

![Data Ingestion](./images/welcome.png)

From all the Experience Cloud solutions choose Audience Manager. You will be redirected to AAM.

![Data Ingestion](./images/aam-icon.png)

Let's create a new segment. Click the "Audience Data" button in the upper bar and choose "Segments" from the dropdown menu.

![Data Ingestion](./images/segment1.png)

Click at the "Add New" button.

![Data Ingestion](./images/segment2.png)

For creating the new segment, provide the following details


| Name              | Description     | Data Source  |
| ----------------- |:-------------:| :-----------------:|
| La Boutique - Home         | User visiting Home page          | Online Clickstream Data Source         |


![Data Ingestion](./images/segment3.png)

Don't worry about the other areas, keep the default settings for now. 
Each segment must be stored in the folder taxonomy which can be found at the right side of the segment details. Look for folder "Bootcamp" and create a subfolder within you companies folder by clicking at the "+" button. 

![Data Ingestion](./images/segment4.png)

Name the subfolder: company_segments, replacing company with the name of your organization.

![Data Ingestion](./images/segment5.png)

Choose your new folder to store your segment.

If you wish to learn more about taxonomy, [click](https://marketing.adobe.com/resources/help/en_US/aam/c_common_taxonomy_about.html)  here.

Now we need to assign a trait (could also be multiple traits) to our new segment. 
Go to "Traits" and open the this section by clicking on the arrow.

![Data Ingestion](./images/segment6.png)

Click on "Browse All Traits" to choose traits for building the segment.

**Repeat this for evar2 & evar3 with the following components:**

| Key              | Operator     | Value |
| ----------------- |:-------------:| :-----------------:|
|c_evar2 | CONTAINS        |chrome       |

| Key              | Operator     | Value |
| ----------------- |:-------------:| :-----------------:|
|c_evar3 | CONTAINS        |cart|


### [Next Exercise 2.2 - Create a Segment](./ex2.md)
#### [Go back to Exercise 2 overview](./README.md)
#### [Go back to General Overview](../README.md)



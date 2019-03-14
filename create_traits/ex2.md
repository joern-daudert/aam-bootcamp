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

Complete Basic Information by giving the segment a name, description, data source and folder location. 

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
Go to "Traits" and open this section by clicking on the arrow.

![Data Ingestion](./images/segment6.png)

Search for the trait by name, or use the Advanced Search modul by clicking "Browse All Traits".

In this pop-up window, first look for your traits in the taxonomy folders in the left navigation panel. 
Click into your folder and the associated traits will be listed in the main window. 

Select your trait "La Boutique - Home" and click "Add Selected Traits to Segment".

![Data Ingestion](./images/segment7.png)

Your trait has now been assigned to the segment. For now, we will only assign one trait per segment. Later we will also add multiple segments to combine them via bolean operators. Go ahead and save the segment by clicking the button below.

![Data Ingestion](./images/segment8.png)

After creating the "La Boutique - Home" segment, go ahead and repeat the same steps to create a segment for each of the other two traits as well. 

Segment: Google Chrome visitors

| Name              | Description     | Data Source  |
| ----------------- |:-------------:| :-----------------:|
| Google Chrome visitors         | User visiting from chrome browser          | Online Clickstream Data Source         |

Segment: Page Visitor - Cart

| Name              | Description     | Data Source  |
| ----------------- |:-------------:| :-----------------:|
| Page Visitor - Cart         | User visiting Cart page          | Online Clickstream Data Source         |

You have now created the 3 basics segments. Next, let's create a segment combining multiple traits by setting bolean operators.

Click on "Add New" in Segment Builder and provide the following details to create the segment. Remember to store your segment in your taxonomy folder.

| Name              | Description     | Data Source  |
| ----------------- |:-------------:| :-----------------:|
| High Interest users         | High Interest users         | Online Clickstream Data Source         |

![Data Ingestion](./images/segment9.png)

In this audience we only want users who have shown high interest by reaching the cart page. Let's assume this audience is going to be used for onsite personalisation and some of the testing content cannot be displayed properly in a Chrome browser. Hence, we need to exclude all Google Chrome users from this audience. 

Go to the Traits section and click at the "Browse All Traits" button.
In the folder taxonomy browse your folder to find your traits. Select the following traits

Page Visitor - Cart
Google Chrome visitors

Go and click "Add Selected Traits to Segment".

![Data Ingestion](./images/segment10.png)



Mouse-over trait "La Boutique - Home" and move to the left side to the icon looking like 6 bubbles. Click to move the trait below to the end:

![Data Ingestion](./images/segment11.png)

![Data Ingestion](./images/segment12.png)


### [Next Exercise 2.2 - Create a Segment](./ex2.md)
#### [Go back to Exercise 2 overview](./README.md)
#### [Go back to General Overview](../README.md)



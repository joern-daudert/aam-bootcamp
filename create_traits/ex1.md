## Exercise 2.1 - Create a Trait and define your taxonomy

Go to [Experience Cloud UI](https://experiencecloud.adobe.com) and log in with the credentials provided to you. 

Click on "Sign In with an Adobe ID" and log in using email address and password.

![Data Ingestion](./images/login.png)

You are now in the Experience Cloud Welcome screen. Go to the upper right corner and click on the icon with the 9 little bubbles.

![Data Ingestion](./images/welcome.png)

From all the Experience Cloud solutions choose Audience Manager. You will be redirected to AAM.

![Data Ingestion](./images/aam-icon.png)

Let's create a new trait. Click the "Audience Data" button in the upper bar and choose "Traits" from the dropdown menu.

![Data Ingestion](./images/traits1.png)

Click at the "Add New" button and choose "Rule-Based" from the dropdown. 

![Data Ingestion](./images/traits2.png)

For creating the new trait, provide the following details

Name: La Boutique - Home
Description: User visiting Home page
Data Source: Online Clickstream Data Source
Event Type: Site Visitor

![Data Ingestion](./images/traits3.png)

Each Trait must be stored in the folder taxonomy which can be found at the right side of the Trait details. Look for folder "Bootcamp" and create a subfolder within you companies folder by clicking at the "+" button. 

![Data Ingestion](./images/traits4.png)

Name the subfolder: company_traits, replacing company with the name of your organization.

![Data Ingestion](./images/traits5.1.png)

Choose your new folder to store your trait.

If you wish to learn more about taxonomy, [click] (https://marketing.adobe.com/resources/help/en_US/aam/c_common_taxonomy_about.html)  here.

Go to "Trait Expression" and open the this area by clicking on the arrow.

Now you need to fill in the key:value pairs to define your trait.

Key: c_evar1 
Operator: == 
Value: la boutique home

![Data Ingestion](./images/traits5.2.png)





![Data Ingestion](./images/createdataset.png)

We're going to create a new dataset based on a schema, the Profile-schema, so we need to select the option to create the dataset based on a schema.

![Data Ingestion](./images/datasetschema.png)

![Data Ingestion](./images/datasetschemadtl.png)

We'll upload CRM Data. CRM Data is always linked to a customer's profile, and as such, we need to select the Profile-schema here.

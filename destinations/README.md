## Exercise 2: Build Traits & Segments
In this exercise, the goal is to define traits in AAM and assign them to a Segment.

### Learning Objectives

- Learn how to create a trait based on key:value pairs
- Learn the web UI of Adobe Audience Manager (Trait and Segment Builder)
- Understand the importance of a self-manageable taxonomy
- Learn how to build a segment based on boolean operators (AND/OR/NOT)
- Learn how to activate a segment to a destination (targeting platform)

### Lab Resources

- Experience Cloud UI: [https://experiencecloud.adobe.com/](https://experiencecloud.adobe.com/)

### Lab Tasks

- Creating traits and segments
- Activating a segment to a destination

### Story: Using the Data Ingestion UI

In Exercise 1 you have completed the neccessary steps to start collecting online behavioral data via Adobe Analytics which is being server-side-forwarded into Adobe Audience Manager. Now we've got raw data (key:value pairs such as evar1:pageName) flowing into the Data Management Platform. In AAM such raw data is called a **Signal**. The goal is to have users qualify for a segment, so we need to take the raw data flowing into the DMP and bring it into a format which the DMP can read. This format or attribute is called a **Trait**. Traits are built from signals based on the key:value pairs. This means, if a user visits the website and an event is being tracked, the key:value pair qualifies the user for the trait in Audience Manager. A **Segment** can be built by having one trait or by combining multiple traits (representing different data sources such as 1st, 2nd and 3rd party data). Using boolean operators (AND/OR/NOT) helps building an actionable segments which can be pushed to a destination (targeting platform such as DSP) to create personalized experiences.

Here is an overview of the data structure in AAM:

![Data Ingestion](./images/traits.png)

Click here to learn more about [Traits](https://marketing.adobe.com/resources/help/en_US/aam/c_tb_rules.html) and [Segments](https://marketing.adobe.com/resources/help/en_US/aam/c_segment_builder.html).


### [Excercise 2.1 - Create Traits and define your taxonomy](./ex1.md)

### [Excercise 2.2 - Create a Segment](./ex2.md)



[Go Back to All Modules](/../../)




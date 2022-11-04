##### Skilljar-data-connector

# Product Description & Purpose

Skilljar is the world’s leading Customer Education software. Innovative companies such as Tableau, Verizon, Zenefits, U-Haul, and hundreds more rely on Skilljar to onboard, engage, and retain their customers at scale.

Pull in courses and their linked lessons from your Skilljar instance into Yext. Now you can extend the reach of your Skilljar data even further to power Yext search experiences. In order to install this app, you will need a Skilljar account and a Yext account.

This app creates the following custom connectors:

- skilljar\_courseConnector
- skilljar\_lessonConnector

This app creates the following custom entity types that correlate to each connector:		

- skilljar\_course
- skilljar\_lesson

This app creates the following custom fields:

- skilljar\_courseCategory
- skilljar\_courseLessons
- skilljar\_lessonCount
- skilljar\_lessonsList
- skilljar\_parentCourse

# Requirements

To use this template you will need to have the following before you install:

- A Skilljar account
- Your Skilljar API Key

#### Follow the step-by-step instructions below to install the Skilljar Course Connector app.

# How to Install

If you are an existing Yext customer, you can install the Skilljar Connector here <https://www.yext.com/s/me/apps/74048>

If you are not an existing customer, but interested in learning more, try out a free trial here for a production account, or sign up for Hitchhikers and get started with a sandbox account, here <https://hitchhikers.yext.com/>. 

### To install the Skilljar Connector:

1. Log in to your Yext account
2. Navigate to the **Apps > Directory** tab in the platform (or use the link provided above).
3. Search for the Skilljar Connector app and click **Install**.
4. Accept the following changes to your account by clicking **Next** and authorize Yext APIs.
5. Provide your Skilljar API Key and Domain.
6. Run the Skilljar Lesson Connector BEFORE you run the Skilljar Courses Connector. Make sure that the Lesson Connector has fully completed running before you run the Courses Connector.

After running both connectors, you can see all of your newly created Course and Lesson entities in the **Knowledge Graph** tab in the platform!

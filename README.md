<h1 align="center" style="border-bottom: none;">:rocket: IBM Digital Tech Tutorial: Watson Assistant Search Skill</h1>
<h3 align="center">In this hands-on tutorial you will create a new IBM Watson Assistant and Discovery Service on the IBM Cloud and deploy your solution</h3>


## Prerequisites

1. Sign up for an [IBM Cloud account](https://cloud.ibm.com/registration).
2. Fill in the required information and press the „Create Account“ button.
3. After you submit your registration, you will receive an e-mail from the IBM Cloud team with details about your account. In this e-mail, you will need to click the link provided to confirm your registration.
4. Now you should be able to login to your new IBM Cloud account ;-)

## Configuring the Watson Assistant and Discovery service on the IBM Cloud

<h4>1) Create a Watson Assistant Service</h4>
After the login you will see your IBM Cloud Dashboard. In the upper menu bar click Catalog. In the Catalog section, click on the AI category, then select Watson Assistant. On the next page select the Lite Plan - or the Plus Trial, Standard or Plus Plan for further deployment options - and you can also choose a region, where you would like to deploy your service as well as a service name. Click "Create".

![Catalog Watson Assistant](readme_images/catalog-watson-assistant.png)

Repeat this process to create a Watson Discovery Lite instance, which you will also find in the catalog under AI.

## How the Search Skill and Discovery Work

You can add a search skill to your assistant to prevent the assistant from having to say things like, `I'm sorry. I can't help you with that`. Instead, the assistant can query existing company documents or data - like a webpage - to see whether any useful information can be found and shared with the customer. Therefore, the search skill searches for information from a data collection that you create by using the Discovery service. Discovery is a service that crawls, converts, and normalizes your unstructured data. The product applies data analysis and cognitive intuition to enrich your data such that you can more easily find and retrieve meaningful information from it later. Typically, the type of data collection you add to Discovery and access from your assistant contains information that is owned by your company. This proprietary information can include FAQs, sales collateral, technical manuals, or papers written by subject matter experts.

The following diagram illustrates how user input is processed when both a dialog skill and a search skill are added to an assistant.

![Catalog Watson Assistant](readme_images/search-skill-diagram.png)


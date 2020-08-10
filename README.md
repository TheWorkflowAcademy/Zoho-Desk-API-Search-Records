# Zoho Desk API Search Records
Uses the Zoho Desk API to search records. As way of example, we will get a Contact's most recent ticket based on email in Desk and add a link to it in the CRM Contact record.

## Introduction
### Search Zoho Desk via API
With the Zoho Desk API, you are able to retrieve records based on a search term. You can search across all modules or specifically in the following:
* Tickets
* Accounts
* Contacts
* Articles
* Tasks
* Calls
* Events
* Products
* Activities

By way of using a relevant business use case in our script, we will be retrieving all of a CRM Contact's Tickets in Zoho Desk and adding a link to the most recently opened ticket. Please consult the Zoho Desk API Reference for more information on the specific endpoint for each search module.

## Configuration
Before you use this script you should be generally familiar with Deluge scripting and the `invokeurl` function.

### Connection to Zoho Desk API
To use this custom function you will need to create an API Connection to Zoho Desk. You can learn how to use Connections in Zoho CRM [here] (https://www.zoho.com/crm/developer/docs/connectors/set-up.html#Invoke_Connectors) (for Zoho Desk use the Zoho OAuth connection). The scopes you need for this code to work are `Desk.search.READ` and `Desk.tickets.READ`.





# Zoho Desk Search Records
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

By way of using a relevant business use case in our script, we will be retrieving all of a CRM Contact's Tickets in Zoho Desk and adding a link to the most recently closed ticket 

## Configuration
### Connection to Zoho Desk API
To use this custom function you will need to create an API Connection to Zoho Desk. In this script the connection is named `zohodesk`.

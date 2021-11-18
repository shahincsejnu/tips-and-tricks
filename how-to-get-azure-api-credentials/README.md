# Getting Azure API Credentials to make API calls

## Steps

0. Login into your [Azure Account](https://portal.azure.com)
1. creating an application in Azure Active Directory 
2. getting subscription id 
3. getting tenant id 
4. getting client id 
5. getting client secret  

**Note:** `Client ID`, `Client Secret` are Application specific, but `Subscription ID`, `Tenant ID` are azure account specific.

## Step-1 : Create an Application in Azure Active Directory

* Click `Show portal menu` (left sidebar)
* Select `Azure Active Directory`
* Select `App registrations`
* you will see the `All applications`, your `Owned applications`, `Deleted applications` etc.
* Click on `+ New registration`
* Enter your Application `Name`, select `Supported account types`, enter `Redirect URI` etc.
* Click on `Register` button below

## Step-2 : Get the Subscription ID

* search `Subscriptions` on the search box (on the top of the azure portal site)
* you will see your subscriptions name and their respective ID (Subscription ID), role etc.
* Copy the `Subscriptions ID`

## Step-3 : Get the Tenant ID

* Click `Show portal menu` (left sidebar)
* Select `Azure Active Directory`
* Select `Properties` from the left sidebar (see the lower part of the left sidebar, will find it there)
* you will se the `Tenant properties`
* Copy the `Tenant ID`

## Step-4 : Get the Client ID

* Click `Show portal menu` (left sidebar)
* Select `Azure Active Directory`
* Click `Enterprise applications`
* Click `All applications` (if it is not selected automatically)
* Select the application which you have created
* Click `Properties` (by default should be opened when you clicked/selected your application)
* Copy the `Application ID`

## Step-5 : Get the Client Secret

* Click `Show portal menu` (left sidebar)
* Select `Azure Active Directory`
* Select `App registrations`
* Select the application which you have created
* Click on `Cetificate & secrets` from the left bar
* Click on `+ New client secret`
* Type key description and select and Duration
* Click `Add`
* Copy and store the `key value` **You will see this only once, so save it before leaving the page, after leaving the page you won't find it further**



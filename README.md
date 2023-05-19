# Sinch Voice API Postman Collection

## Application signed Postman requests

This Postman collection is a sample set of Sinch Voice API requests using application signing.

### Requirements

- [Postman](https://www.postman.com/downloads/)

### Install

1. Import the collection into Postman, by selecting the **Import** button

    ![Import into Postman, press import ](assets/Collection_Sinch_Voice.png)

2. Drag or select the collection from this repository ```Voice-API-application-signed.postman_collection.json``` into the import dialog.

    ![Import into Postman, import dialog](assets/Import.png)

3. The collection will show a small example set of API callouts and requests

    ![Import into Postman, collection menu](assets/Collection_menu.png)

4. Add your application key and secret from your [Dashboard](https://dashboard.sinch.com/voice/apps) to the ```appKey``` and ```appSecret``` Variables tab of the collection.

    ![Import into Postman, collection menu](assets/Variables.png)

5. Add the rest of the following variables:

    ![Import into Postman, request callout body](assets/Request_Body_Callout.png)

You can now send a request.

### Items to change in the POST examples

* ```cli:``` Your verified / Dashboard purchased number
* ```endpoint:``` The destination number to call
* ```conferenceid:``` Add the conference id of your choice

![Import into Postman, request callout body](assets/Request_Body_Callout.png)

### Items to change in the GET / DELETE examples

Postman variables are used, but do not resolve to any values, please replace the variables in place (the actual URLs) to use correctly

![Import into Postman, GET / DELETE example ](assets/GET-call-info.png)

```{{callid}}``` Enter a valid call-id

![Import into Postman, GET / DELETE example ](assets/GET-number-info.png)

```{{number}}``` A valid PSTN number to query

![Import into Postman, GET / DELETE example ](assets/DELETE-Conf-kick-all.png)

```{{conferenceid}}``` A valid conferenceId

![Import into Postman, GET / DELETE example ](assets/DELETE-Conf-kick-part.png)

```{{conferenceid}}``` A valid conferenceId
```{{callid}}``` Enter a valid call-id

### Debug
If you want to see the request signing steps output, you can use the postman console to view.


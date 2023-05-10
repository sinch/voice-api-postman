# Sinch Voice API Postman Collection

## Application signed Postman requests

This postman collection is a sample set of Sinch Voice API request using application signing.

### Requirements

- [Postman](https://www.postman.com/downloads/)

### Install

Import the collection into Postman, by selecting the **Import** button

![Import into Postman, press import ](assets/Collection_Sinch_Voice.png)

Drag or select the collection from this repository into the import dialog.

![Import into Postman, import dialog](assets/Import.png)

The collection will show a set of API callout

![Import into Postman, collection menu](assets/Collection_menu.png)


Add you application key and secret to the ```appKey``` and ```appSecret``` Variables tab of the collection

![Import into Postman, collection menu](assets/Variables.png)


* ```cli:``` Your verified / Dashboard purchased number
* ```endpoint:``` Into the cli and to number into the request body of the callout samples
* ```conferenceid:``` Add the conference id of your choice

![Import into Postman, request callout body](assets/Request_Body_Callout.png)

You can now send a request

### Debug
If you want to see the request signing output, you can use the postman console

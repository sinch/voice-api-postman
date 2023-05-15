# Sinch Voice API Postman Collection

## Application signed Postman requests

This Postman collection is a sample set of Sinch Voice API requests using application signing.

### Requirements

- [Postman](https://www.postman.com/downloads/)

### Install

1. Import the collection into Postman, by selecting the **Import** button

    ![Import into Postman, press import ](assets/Collection_Sinch_Voice.png)

2. Drag or select the collection from this repository into the import dialog.

    ![Import into Postman, import dialog](assets/Import.png)

3. The collection displays a set of API callouts:

    ![Import into Postman, collection menu](assets/Collection_menu.png)

4. Add your application key and secret from your [Dashboard](https://dashboard.sinch.com/voice/apps) to the ```appKey``` and ```appSecret``` Variables tab of the collection.

    ![Import into Postman, collection menu](assets/Variables.png)

5. Add the rest of the following variables:

    | Variable | Description |
    | -------- | ----------- |
    | ```cli:``` | Your purchased Sinch number |
    | ```endpoint:``` | Add the number that you want to receive the callout |
    | ```conferenceid:``` | Add the conference ID of your choice |

    ![Import into Postman, request callout body](assets/Request_Body_Callout.png)

You can now send a request.

### Debug

If you want to see the request signing output, you can use the postman console

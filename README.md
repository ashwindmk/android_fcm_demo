# FCM Android Demo


### Running the App:

1. Create app in Firebase Console with the given application ID.

2. Add `google-services.json` file in `app/` directory.

3. Build and Run the app.


### Test using Postman

1. Create a new POST request.

    https://fcm.googleapis.com/fcm/send

2. Add Headers

```
    Content-Type: application/json
    Authorization: key=<FCM-Server-Key>
```

3. Add Body:

```
{
    "to": "fcm-token",
    "data": {
      "key1" : "value-1",
      "key2" : "value-2"
    }
}
```

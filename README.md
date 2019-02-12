# Photo Wall

## Deployment
* Sign up for MongoDB Atlas, free tier should work
* Create a database called `carnival` with a collection called `photowall`
* Within Atlas, create a Stitch App
* Enable a Rule: On the DB and collection above, read any document
* Enable anonymous access under Users->Providers
* Edit `index.html` and change the global variables section to have your Stitch app ID and where you are uploading your pictures to
* Publish to a server
* Fill the database with documents in the format below

## Document format
```
{
    "_id":"5bb220419b586961c2c60c63",
    "path":"https://example.com/path/to/picture.jpg"
}
```
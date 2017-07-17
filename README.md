# Demo for Google OnBoarding

This is a quick demo meant to show how easy it is to do simple powerful things with App Engine and Google ML APIs

## Products
- [App Engine][1]

## Language
- [Python][2]

## APIs
- [NDB Datastore API][3]
- [Users API][4]
- [Natural Language API][5]

## Dependencies
- [webapp2][6]
- [jinja2][7]
- [Twitter Bootstrap][8]

[1]: https://developers.google.com/appengine
[2]: https://python.org
[3]: https://developers.google.com/appengine/docs/python/ndb/
[4]: https://developers.google.com/appengine/docs/python/users/
[5]: https://cloud.google.com/natural-language/docs/
[6]: http://webapp-improved.appspot.com/
[7]: http://jinja.pocoo.org/docs/
[8]: http://twitter.github.com/bootstrap/

## To Install

1) Install the Google Cloud API
See steps 1-5 here: https://cloud.google.com/compute/docs/tutorials/python-guide 
Keep track of the name of the project you just created.

2) Clone this repo locally

git clone https://github.com/JonGal/appengine-ml-demo.git

3) Change to the appengine-ml-demo directory

4) Upload the application into the project you created in the first step

gcloud app deploy app.yaml index.yaml --project <NAME–OF_PROJECT_YOU_CREATED>

5) You will be prompted to choose a region. Pick one closest to whereever you are demoing.

6) Once the scrip ends, wait at least 15 minutes for all the indexes to finish building.

7) Go back to the Google Console. Choose API Explorer

8) Click on Library (left hand column)

9) Click on Natural Language API.

10) Click on Enable.

That's it! You are ready to go!

# flask-restful-jwt-auth
basic sign-up, login, logout functionalities using flask-restful and flask-jwt.
The backend should read in raw data from the csv file and store the data in a Movie
database, then create a RESTful API for the frontend.
The frontend requires the following functionalities:
1) Sort Movies by Name
2) Sort Movies by Runtime
3) Filter Movies by Type
4) Filter Movies by Language
5) Search Movies containing a specific genre
Some examples include:
/api/movies
/api/movies?type=scripted
/api/movies?sortBy=runtime
## Resources
* [code burst jwt in flask](https://codeburst.io/jwt-authorization-in-flask-c63c1acf4eeb)
* [flask jwt extended official docs](http://flask-jwt-extended.readthedocs.io)
* [using marshmallow](https://medium.com/python-pandemonium/build-simple-restful-api-with-python-and-flask-part-2-724ebf04d12)
* [flask marshmallow](https://flask-marshmallow.readthedocs.io/en/latest/)

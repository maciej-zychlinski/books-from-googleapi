# PROJECT DEPRECATED!

## Books from Google API

This web application can interact with the Google Books API. 
Check how it works on https://books-from-googleapi.herokuapp.com/

Search and import to this web aplication volumes that contain text string. There are special keywords you can specify in the search terms to search in particular fields, such as:
* intitle: Returns results where the text following this keyword is found in the title.
* inauthor: Returns results where the text following this keyword is found in the author.
* inpublisher: Returns results where the text following this keyword is found in the publisher.
* subject: Returns results where the text following this keyword is listed in the category list of the volume.
* isbn: Returns results where the text following this keyword is the ISBN number.
* lccn: Returns results where the text following this keyword is the Library of Congress Control Number.
* oclc: Returns results where the text following this keyword is the Online Computer Library Center number.

## Using the API

You can perform a volumes search by sending an HTTP GET request to the following URI:

https://<i></i>books-from-googleapi.herokuapp.com/api/v1/volumes/terms/search

There are special keywords you can specify in the search terms to search in particular fields, such as: 
* title
* authors
* language
* publishedDate

Here is an example of searching for J.R.R. Tolkien books:

https://books-from-googleapi.herokuapp.com/api/v1/volumes/authors/Tolkien

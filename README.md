# Postman Library API Collection

This repository contains a Postman collection I created for a fictional Library API, showcasing various API requests and responses. This collection demonstrates my skills in API testing, automation, and integration using Postman.

## Collection Overview

The Postman Library API collection includes the following endpoints:

1. **Get Books**
   - **Method:** GET
   - **Endpoint:** `/books`
   - **Description:** Retrieves a list of all books in the library.

2. **Get Fiction Books**
   - **Method:** GET
   - **Endpoint:** `/books?genre=fiction&checkedOut=false`
   - **Description:** Retrieves a list of all fiction books that are not checked out.

3. **Get Book by ID**
   - **Method:** GET
   - **Endpoint:** `/books/:id`
   - **Description:** Retrieves details of a book by its ID.

4. **Add Book**
   - **Method:** POST
   - **Endpoint:** `/books`
   - **Description:** Adds a new book to the library.
   - **Test Script:** Saves the `id` value from the response to a collection variable named `id`.

5. **Check-Out a Book**
   - **Method:** PATCH
   - **Endpoint:** `/books/:id`
   - **Description:** Updates the status of a book to checked out.

6. **Delete a Book**
   - **Method:** DELETE
   - **Endpoint:** `/books/:id`
   - **Description:** Deletes a book from the library.

7. **Skill Check**
   - **Method:** POST
   - **Endpoint:** `/post?movieName=Alice in Wonderland`
   - **Description:** Example request to demonstrate skill check functionality.
   - **Test Script:** Saves the `actorName` value from the response to a collection variable named `favoriteActor`.


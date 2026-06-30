# Book Review Site

A site to post book reviews.

## Structure

This project is made using:
- html
- css
- ejs
- javascript
- pgAdmin (sql)

## Implementation

### Review page:

![Image](/photos/reviewsite1.png)

1. Multiple data types (id, title, isbn, and review) are stored on a local server in pgAdmin 4.
2. When the review page is open a for statement utilizing embeded javascript creates templates and loads the data from the database on to said templates.
3. The book cover is fetched utilizing the openlibrary book covers api (https://openlibrary.org/dev/docs/api/covers) by using the isbn as a key and inserting the isbn value of the book into the link of the image source.

### Edit Page:

![Image](/photos/reviewsite4.png)

1. The data from the post that is chosen is loaded on to a form by using embeded javascript.
2. When the chnages are submited they are sent to the server.

### Add Page:

![Image](/photos/reviewsite2.png)

1. There is an empty form that the user can submit a title, review, and isbn for the book they choose.
2. Once submited the data is sent to the server and the user is sent back to the review page.

### pgAdmin 4 set up

![Image](/photos/reviewsite3.png)

1.

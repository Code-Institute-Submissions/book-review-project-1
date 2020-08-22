
`<addr>` 
``` text in gray ```


 # Best Reads - Code Institute. Milestone 3
 ![Main picture](/static/images/main.png)

https://book-review-app-ci.herokuapp.com/


### Table of contents:

- [Description](#Description)
- [UX](#UX)
    - [Business Goals](#Business-goals)
    - [User need](#User-needs)
- [Features](#Features)
- [Features Left to Implement](#Features-Left-to-Implement)
- [Mockups](#Mockups)
- [Technologies used](#Technolies-used)
- [Data structure](#Data-structure)
- [Testing](#Testing)
     - [Validation](#Validation)
     - [Responsiveness](#Responsiveness)
     - [Manual testing](#Manual-testting)
- [Bugs](#Bugs)
- [Deployment](#Deployment)
- [Credits](#Credits)
    
    ## Description
The Best Reads project is focused around the people who are looking for the books via the Internet. The project aims to help people making crowdsource-based decisions about their next good read and attempts to help the owner making a few bucks. Therefore, it takes shape of a database backed website that not only allows the users to search, rate, recommend and review books, but also enables the site owner to participate in the Amazon’s affiliate program.

## UX
In order to build good UX it is necessary to identify business goals and to determine user needs. Therefore, this section gives an insight into the aforementioned aspects, which in turn helps to specify features for this project.

#### Business goals
* increase business value by allowing the owner to earn money via an affiliate program.
* increase earning potential by encouraging the users to upload more books.

#### User needs
As a book hunter, I would like to:
* be able to search for the books.
* find the information about the books such as the book format.
* know what other people think about the particular book.
* be able to buy a book directly from the site or be redirected to an e-shop via a link from the site.

As a user who read a particular book and found it on the site, I would like to:
* let others know about my opinion regarding the book.
* know what others think about the book.

As a user who read a particular book, searched for it and did not find it on the website, I would like to:
* share the book with others and let others know what I think about the book.

As a user who has submitted a review or a book, I would like to:
* be able to edit or delete my submition, in case I have changed my mind.

As a user who has questions I would like to contact someone.

As a site owner, I would like to: 
* allow the website users to contact me,incase they have any queries.
* be able to obtain information such as the most popular search titles or genres, so I could analyse data in order to improve the UX.

 ## Features
This section describes features that satisfy the requirements for the current version release. Also the section briefly outlines additional features for the subsequent versions of this project.

### Existing Features
* **Search form.** Enables the website users to search for the books by allowing them to choose a category and enter the book title, as shown in Figure 1. The form is accessible throughout the site. It appears in the middle of the index page and is available at the top of other pages.  

 <img width="460" height="300" src="http://www.fillmurray.com/460/300">
 
 Figure 1. Shows the search form.

* **Search result page.** Displays up to ten search results matching a search criteria. If a query returns more than ten items, a pagination is displayed at the bottom of the page.
* **Pagination.**  Allows the website users to move forward and backward between the the search result pages. Also enables users to get to a particular page by allowing them to enter a page number. As mentioned in the Search result page section every search query is limited to return up to ten items. Moving between the pages simply performs a new search with the same query but, with a number of items skipped depending on the user action. For example, if a search returns thirty books only first ten books are requested from the database. Moving to a next page would perform the same query with the first ten books excluded.


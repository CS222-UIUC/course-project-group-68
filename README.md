# course-project-group-68

## Summary of Presentation
* Our website was our original idea, as lines have always been inconvenient for us to deal with. Linecheck is a user-driven website used to update the wait times of popular bars and restaurants in Champaign. Through information crowdsourcing, users can actively update the information of their location to inform others about wait times at certain businesses.

## Technical Architecture
* Frontend
  * When it comes to the architecture of our project, it was quite simple. We had a frontend aspect that dealt with everything that the user sees. This was coded in HTML, CSS, and JS. The HTML dealt with most of the text and pictures that appeared on the site. The CSS was used to add fonts and other styling elements to the HTML. The JS was used to animate some features of the HTML and also supported some technical functions used in the HTML files.
* Backend
  * On the backend side, we used FireBase to store our data. We included a request handler in our Bar and Restaurant HTML files to connect the collection we created in FireBase to our code. Then we created a query where we checked the bar’s name and the time the query was created. If the query is not the bar's name or wasn’t created in the last 30 minutes, then we don’t pull the data. After adding each query to a document, we parse through the document and put the wait time that the user posted into an array. Then we take the average value of that array and post it to our landing page. 



course-project-group-68 created by GitHub Classroom

![Linter](https://github.com/CS222-UIUC/course-project-group-68/actions/workflows/super-linter.yml/badge.svg)

<!-- Pytest Coverage Comment:Begin -->
\n<!-- Pytest Coverage Comment:End -->

![check-code-coverage](https://img.shields.io/badge/code--coverage-100%25-brightgreen)


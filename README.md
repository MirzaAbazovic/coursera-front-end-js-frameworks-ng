#Front-End JavaScript Frameworks: AngularJS
https://www.coursera.org/learn/angular-js/home/welcome

## [Assignment 1]
Instructions

Assignment Overview

In this assignment you will construct a page using Angular to display information about a dish and the customer comments posted about the dish. At the end of this assignment, you should have completed the following tasks to update the page to:

Display details of the dish
Display a list of comments.
Let the user order the comments by author, date or rating.
Assignment Requirements

This assignment requires you to complete the following three tasks. Detailed instructions for each task are given below.

* Task 1

In this task you will display the information about the dish in the page. This should be displayed in the first column div inside the row div. To do this, you need to complete the following:

Set up the row to use the dishDetailController
Use the Bootstrap Media Object to display the information about the dish.

* Task 2

In this task you will display all the comments from the dish JavaScript object as a list of comments underneath the dish description on the page. The comments should be displayed in the second column div inside the row div. To do this, you need to complete the following:

Use the Bootstrap blockquote class to format the comments. The author and the date information should be in the footer of the blockquote.
The date field should be formatted using the Angular date filter.
The comments are constructed by iterating over the comments array using the appropriate ng- directive.

* Task 3

In this task you will add the filter to the comments section so that the comments can be ordered according to user's selected criteria. You will use the orderBy filter in Angular to achieve this. To do this, you need to complete the following:

Set up an input field that enables the user to type in their ordering criteria: author, date and rating. These could be prefixed with a '-' sign to indicate reverse ordering.
Set up the orderBy filter on the comments so that the comments will be ordered as per the user's specification.
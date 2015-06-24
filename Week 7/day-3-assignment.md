# Week 7 - Assignment 3

## jQuery Ajax

We're going to add commenting with AJAX to our blog posts. You'll need to do a fair bit of reading and research on jQuery and javascript to build on what we demoed in class. Try using some of the terminology in the requirements here as search keywords to guide you. This research is primary component of this assignment. You'll really only end up writing a few lines of code to get this done.

## Requirement

- [ ] Remember about `$(function { '...' })` to wait for the DOM to be ready.
- [ ] Catch the `submit` event on your comment form. Look into `event.preventDefault()` to stop it from actually submitting, and do an AJAX request to `comments#create` instead.
- [ ] Have your create action respond to both HTML and JSON
- [ ] The JSON response should render a partial for a single comment into a string 
- [ ] Your AJAX `success` handler should take the response data (your comment partial) and `append` it to the comments list.
- [ ] BAM AJAX!
# Headstorm Programming Challenges

  The following is a set of front-end and back-end challenges that can be completed to supplement your resume as part of the interview process with Headstorm. Technology is a core element of our culture at Headstorm and we hope you find these challenges interesting. Complete as much of each challenge as you are able. It is acceptable to submit an incomplete solution.

### Submission Instructions

  Submit a [Pull Request](https://help.github.com/en/articles/about-pull-requests) (PR) to this repository. Once your PR is created, engineers at Headstorm will review the request and engage in commentary and questions on your PR.

## Front End Challenge

A company has approached you for help in developing their product and establishing an online presence. You have been tasked with quickly creating a web page for this startup to launch their web page. This page has the following requirements:

* Startup name title

* Startup logo as icon in browser tab

* Contact us web form that captures contact information

* Google reCaptcha V2 implement in page. Submission of form requires Google captcha pass

* Dump all the information from the form submission to browser console. Google reCaptcha Reference: https://developers.google.com/recaptcha/docs/display

## Back End Challenge

  Create a [REST API](https://www.restapitutorial.com) using any language or web framework you prefer, which performs the following functionality: 
  - Provides a POST endpoint at `/data` where a user submits a JSON formatted list of 500 random numbers.  The list has to be exactly 500 numbers, if there are more or less than 500 an error must be returned.  Similarly, if something other than a list of numbers is submitted, an error must be returned.
  - Provides a GET endpoint at `/data` which provides the same JSON formatted list of 500 numbers that are sorted from lowest to highest.
  **BONUS:**
  - Provides a PATCH endpoint at `/data` which inserts a random number into the list in the proper order which will be returned by the above POST api.
  
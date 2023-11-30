# Class 12 Notes

## In your own words, describe what each group of status code represents:

### 100’s =

Its basically saying it heard your request and is waiting for more information from the server

### 200’s =

This is somewhat like the 100's where it says the request was made but now it is also validating that the server has accepted the request. However, it does not mean the request is fully processed.

### 300’s =

Basically says that the thing you are looking for is in a new place but they should also point you to where you can find the new information.

### 400’s =

This is a client error. So think of this like the user put information in the wrong place. It will also tell you something went wrong when sending info to the server (again could be a incorrect request). 

### 500’s =

this is a server side error.  It may mean the server is down or that it cannot receive requests for some reason. Sometimes it may be temporary and other times it may mean something is seriously wrong.

## What is a status code 202?

Accepted

## What is a status code 308?

Permanent Redirect

## What code would you use if an update didn’t return data to a client?

204 - No Content

## What code would you use if a resource used to exist but no longer does?

401 - Gone

## What is the ‘Forbidden’ status code?

600+

## Why do we need to pull our MongoDB database string out of our server and put it into our .env?

Its a security measure to make sure you are not giving away sensitive info. It can also help make deployment easier because you can customize environment variables

## What is middleware?

It is the code between request and response. It is usually authentication, logging, error and data handling.

## What does app.use(express.json()) do?

It parses incoming request into json

## What does the /:id mean in a route?

it is a route used to capture a specific url

## What is the difference between PUT and PATCH?

put  updates the entire representation of the data where as patch is used to update only specific fields

## How do you make a default value in a schema?

you are going to write a default value within the document and set it to the data  specified. An example might be under a username docuement you may specifiy the type of data and then under that you may set the default as guest. this ensures that each person has a user name even if the user does not fill in this parameter.

## What does a 500 error status code mean?

Error is on the server side.

## What is the difference between a status 200 and a status 201?

200 responses are usually used for get requests where the 201 is usually used to respond to successful post requests.

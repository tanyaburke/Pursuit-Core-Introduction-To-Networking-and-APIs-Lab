# Pursuit-Core-Introduction-To-Networking-and-APIs-Lab

# Part One

API Scavenger Hunt!

For each of the questions below, identify a website and search query that will give you the appropriate JSON.  Paste the url and a snippet of the json below.  Googling the category + API will generally take you to where you need.  Ex. https://lmgtfy.com/?q=cat+fact+api

1. A random cat fact
https://catfact.ninja/docs
{
"swagger": "2.0",
"info": {
    "title": "Cat Facts API",
    "description": "This API provides endpoints to get random cat facts. <a target='_blank' href='https://documenter.getpostman.com/view/1946054/S11HvKSz'>See Postman Docs</a>",
    "version": "1.0.0"

1. A list of 150 random users in English.
https://randomuser.me/api/
"results": [
       {
           "gender": "male",
           "name": {
               "title": "Mr",
               "first": "Mason",
               "last": "Jackson"
           },
           "location": {
               "street": {
                   "number": 1748,
                   "name": "Tennyson Street"
        

1. All the repos on Github with Pursuit their name
https://api.github.com/search/repositories?q=pursuit{&page,per_page,sort,order}
{
"total_count": 828,
"incomplete_results": false,
"items": [
    {
        "id": 63269236,
        "node_id": "MDEwOlJlcG9zaXRvcnk2MzI2OTIzNg==",
        "name": "Pursuit-Core-Android",
        "full_name": "joinpursuit/Pursuit-Core-Android",
        "private": false,
        "owner": {
            "login": "joinpursuit",
            "id": 5825944,
            "node_id": "MDEyOk9yZ2FuaXphdGlvbjU4MjU5NDQ=",
            "avatar_url": "https://avatars2.githubusercontent.com/u/5825944?v=4",
            "gravatar_id": "",
            "url": "https://api.github.com/users/joinpursuit",

1. All the JavaScript repos on Github with Pursuit in their name

1. All the Swift repos on Github with Pursuit in their name

1. A list of all Pokemon
https://pokeapi.co/api/v2/pokemon

{
"count": 964,
"next": "https://pokeapi.co/api/v2/pokemon?offset=20&limit=20",
"previous": null,
"results": [
  {
    "name": "bulbasaur",
    "url": "https://pokeapi.co/api/v2/pokemon/1/"
  },
  {
    "name": "ivysaur",
    "url": "https://pokeapi.co/api/v2/pokemon/2/"


1. A list of all items in Fortnite

1. A list of all Game of Thrones Episodes.

1. A list of all songs with "Love" in the title.
1. All information about Petyr Baelish from the Game of Thrones books
1. All the movies Leonardo Dicaprio has acted in

# Part Two

Status Code Scavenger Hunt!

Use Postman to find each of the following HTTP codes:


1. 200
https://catfact.ninja
the action was successfully received, understood, and accepted
1. 301
Moved Permanently is used for permanent URL redirection
1. 400
Bad Request response status code indicates that the server cannot or will not process the request due to something that is perceived to be a client error 
1. 401
(Unauthorized) status code indicates that the request has not been applied because it lacks valid authentication credentials for the target resource
1. 403
server to indicate that access to the requested (valid) URL by the client is Forbidden for some reason. The server understood the request, but will not fulfill it due to client related issues.
1. 404
https://en.wikipedia.org/wiki/List_of_HTTP_status_codes_(Links_to_an_external_site.)_https://http.cat
Page Not Found
1. 418
I'm a teapot
1. 500
 Internal Server Error, means that server cannot process the request for an unknown reason


For each of the questions below, write:

1. The website which generated the HTTP status code
2. A description of what the status code means
3. If an app you were writing encountered this status code, what would you do (if anything) to resolve any issues?


For reference, see:

https://en.wikipedia.org/wiki/List_of_HTTP_status_codes (Links to an external site.)
https://http.cat




# #100DaysOfCode Log - Round 1 - Alyona

The log of my #100DaysOfCode challenge. Started on [July 12, Thursday, 2018].

## Log

### R1D1 
Was working on authorization via Google Oauth2. Not fully implemented yet, but I am very close to the end.

### R1D2
Not very productive, but I did my best! Worked under google oauth2 authorization. Wrote methods on backend for exchanging authorization code and implemented frontenf part which receives code from google and send it to backend

### R1D3
Debugged google oauth2. Don't know why, but fiddler does not capture all traffic from my pc, only from edge browser. It is weird. Proxy settings seems to be right. 

### R1D4
I've almost finished implementation of google oauth. The problem was in content type. Seems posting data as json is not supported by google api "token" method. Rewrited it to form data. Next step is to rewrite some existing code with new user model

### R1D5
Authorization via Google is completed! But it is very basic authorization, not secure.. I must make it more secure and use token validation while user uses app. But this feature is not in the current sprint. My next step is show user avatar near messages 

### R1D6
Today I implemented displaying user avatar from google in user list. Next step is to display this avatar near every message. 

### R1D7
Today I added user avatars from google near user messages. Looks nice, but I've also found some bugs.. next step is to run integration tests and check what becomes broken after last changes. And I must write some new tests to cover new functionality

### R1D8
Made one small fix on frontend and fixed integration tests. I thought about how to test google oauth, but I have no idea yet. Maybe I don't need such kind of test. I'll think more about it

## R1D9
Closed 2nd sprint and started 3rd. My first task is create DB and integrate in with existing code. I must use DB instead of memory storages. I chose PostgreSQL as DB. I know it is free, pretty cool and fast.  And I started write init migration in node 

## R1D10
Completed init migration, wrote 3 repositories and 1 querier. I use node-postgres to communicate with db and I like it! It supports async/await and my code looks pretty clear! I thought I complete db integration today, but seems it will take more time

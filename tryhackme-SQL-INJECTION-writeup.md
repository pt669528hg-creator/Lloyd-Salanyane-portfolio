# TryHackMe: SQL INJECTION
completed by: Lloyd Itumeleng Salanyane 
Date: 20 June 2026

## What I learned
- I learned what is a database and what exactly does a data base do
- And I was exposed to SQL and how do we work with it in a database
- So understanding SQL helped me understand how to work through my task better even though I did not finish my task
- SQL Injection happens when input isn't filtered/validated
- single quote "'" is the quickest way to spot it
- Can bypass logins , list all tables, and pull private data

  ## Steps & commands I used
  1. Here's what I did first I set up a attacker machine and a lab machine
  2. These are the commands that I used
  3. check vulnerability:"'"
  4. login bypass: "' or 1=1--"
  5. find columns:" Order by" + "union select"
  6. Get info: " database()", " version()"
  7. Dump table/column names: query " information_schema"
  8. Get credentials:" select username,password from users"
 
# Challenges
- My first challenge was getting the spacing right after "--" was tricky at first
- As well as I needed to match exact column count for union to work
- The only thing that I need to remember next time is to always work on time and not relax because the lab machine uses timer and if I don't work fast enough I won't be able to finish my lab 

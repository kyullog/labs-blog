---
title: Sprint Challenge Two
date: "2019-06-01T12:46:37.121Z"
description: "Working with Other Developers"
---

## Working with Other Developers

This sprint was all about learning to work together as a team.

### Individual Accomplishments

This sprint, I was essentially the Firebase point-man for our group. I managed to configure our backend in such a way as to technically work with Firebase, but it was not the _correct_ way. Luckily, I found a [Medium article](https://medium.com/@_josueperalta/using-firebase-auth-with-a-custom-node-js-server-part-1-53bdb622c89a) written by Lambda's own Josue Peralta that helped me figure out how use regex to solve the problem I was having with parsing my Firebase private key from an environment variable. After that was taken care of, it was much easier to get into the nitty-gritty of setting up our authentication and database systems. I spent the rest of the sprint writing database helper functions, and some of the endpoints. I also set up Firebase to work with our front-end for authentication purposes. We now have the ability to obtain a key (with proper credentials, of course) from Firebase, that will work with our authentication middleware on the back-end to secure our server endpoints.

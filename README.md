# COMS4995

Columbia University's COMS4995 - Open Source Development

## Overview

`CU-Later` is a free online chat platform designed for Columbia University students who would like to anonymously message friends, love-interests, and strangers with common interests. The idea was inspired by Wesleyan University’s [Wescam](https://www.nytimes.com/2004/04/25/education/are-we-a-match.html) which was an instant “big-hit” back in 1998 and continues to be in the present day. **My goal is to not only introduce the platform to Columbia’s campus, but also document the design process and cloud infrastructure with hopes of opening the source code to all universities/campuses around the world.**

Using the `CU-Later` app, students can reach out to other students anonymously (with very limited information).   Once connected, the recipient of the message has to guess the identity of the sender - they can message back-n-forth until the recipient guesses the identity of the sender.  The sender knows the identity of the recipient but the recipient does not know the sender’s identity.  There is no penalty of incorrect guesses, and the sender can at any time reveal their identity.  And they can continue their conversation and potentially create plans to hang out.  Only Columbia and Barnard students can sign-up.

## Use Case 

Assume Rachel would like to message Carlos.

1. Rachel registers her university email account on the platform; no other form of email account accepted. Rachel will receive an email containing a random-generated message to confirm her identity.

2. Rachel finds Carlos’s name on the platform and initiates a conversation under the pseudo name of `Pikachu`. Carlos receives an email saying that someone, in this case, `Pikachu`, would like to talk to him. Carlos then registers an account.

3. Carlos doesn’t know who `Pikachu` is, but Carlos is (very) curious to know, so Carlos decides to guess the `Pikachu`’s identity via a series of questions. The only information that Carlos is given is `Pikachu`’s class year, school (ex. CC, SEAS, GS), and/or some other attribute(s).

4. Carlos continues to talk to `Pikachu` and ...
    1. correctly guesses `Pikachu`’s identity. Rachel reveals herself they have a fun conversation afterward.
    2. incorrectly guesses `Pikachu`’s identity. There’s no penalty so Carlos can continue to guess as much as he wants. At any point, Rachel can reveal her identity and their fun conversation can continue to exist. 

5. Carlos and Rachel can continue to use the platform to connect with other people.  They can take on new identities and prank friends, message love-interests, and/or connect with fellow students on campus. If they decide to connect with other students on campus whom they have never met, they can be matched with users who share the same interests (ex. sports, hobbies, etc). 

**Note**: It’s not necessary for users to respond to other user’s messages. Everyone has the choice to talk, block, and report users. Our user’s safety is our main concern, therefore, we are planning to create some functionality for reporting inappropriate behavior and contacting Public Safety.
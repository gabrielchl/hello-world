+++
date = '2020-06-02T07:19:00+01:00'
draft = false
title = 'GSoC Wikimedia Bi-Weekly Report 2'
categories = ['Google Summer of Code 2020']
+++

(This is part of a (mandatory) blog series documenting my experience in GSoC 2020 with Wikimedia Foundation. This series should serve for record-keeping purposes and as a reference for future GSoC students.)

## Community Consultation

Before we dive into coding, we decided that we had a few questions that we wanted to ask our community, our future possible users for some opinion on that new tool to be developed. For that purpose, a questionnaire was created and the link to it was posted on the Commons Village Pump.

The responses were slow. Before my topic was thrown into the archive, the questionnaire only got 6 submissions. Well, 6 is definitely not enough to reach any conclusions. In the meeting with Navino and Eugene, my mentors, they suggested that perhaps I should try to send personal invitations. Well, out of expectation, it worked amazingly, till today, we got 18 submissions.

The main question that we wanted to solve or at least get some insight into what the community prefers is what method of user verification would be the best for MDVT, name (at least for now) of our new tool. For most of you who doesn’t know what does that mean in MDVT, here’s a short explanation. Basically, we want to ensure that data created using our tool are as real as they can get, given that MDVT is a “data verification tool”, it’d be hilarious if data generated wasn’t correct. To do that, we have to verify our users’ edits in the tool. We proposed multiple methods to do so, such as:

- Only allow “trusted” users to use the tool (maybe require a certain amount of edits and/or a certain account age?)
- Have users to verify/approve others’ entries
- Show users test questions (maybe 1 test in every 10 real questions) to see if they choose the right answer
- Show a question to multiple users and save the majority choice
- This will not be a problem so we shouldn’t worry about this

50% of the questionnaire participants chose the “majority” option, followed by the “test questions” option.

## Problem with “Saving the Majority Choice” method

The biggest problem is it’s impossible to make it fair amongst all participants. As we are showing multiple users the same question and using the majority choice, we need to pick one of the participants to take the edit. There were a few proposed solutions, such as to keep a “fair score” of all users, we’ll give the user with the highest score the edit, and deduct 1 from his score. Or, we could setup a new Wikimedia account for the tool and make all edits through that account.

After an internal meeting, considering the pros and cons and the communiy’s input on the subject, we decided to go with the 2nd most popular option – the “test questions” method. We decided that it’s easy to understand, effective and doesn’t affect our users a lot (they won’t even know that their looking at a test question, only will they know after answering it).

## Question Design

Another thing that we did was design the questions for the tool. This tool is entirely built on simple questions and answer. For example, we wanna know if there’s a bird in the image, if the bird is white in color, if the bird is a prominent object in that image, if there is only 1 bird in the image, etc. Therefore, question design is an important part of the development process, as it is one of the few things the user will see.

Question structures and examples were developed for depict statements and some of the popular depict qualifiers statements.

## Roadmap

The last thing we did was list out all features required for a MVP (minimal viable product).

Now that everything is settled on the planning side, we know what were gonna do next, which is to dive into the code. And that’s what exactly I’m gonna do 🙂 .

## The End of the Community Bonding Period

Well, to me it isn’t really a special “period”. I mean, we never considered it and it never affected our schedule or stuff like that. Overall, we (me and my mentors) make a wonderful team and I sincerely can’t wait to see the great product we develop. 🙂

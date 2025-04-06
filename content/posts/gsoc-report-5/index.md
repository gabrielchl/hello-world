+++
date = '2020-07-13T07:11:00+01:00'
draft = false
title = 'GSoC Wikimedia Bi-Weekly Report 5'
categories = ['Google Summer of Code 2020']
header_image = 'gsoc-blog-5-thumb.jpg'
+++

(This is part of a (mandatory) blog series documenting my experience in GSoC 2020 with Wikimedia Foundation. This series should serve for record-keeping purposes and as a reference for future GSoC students.)

## Feature Added: Contributions Page

As promised last week, here comes the contributions page, showing which questions, along with the collected answers, were answered by the user.

## Feature Added: Qualifier – Prominence

Adding qualifiers support to the tool would be a pretty huge task, and is probably the last huge task before our team move onto code testing, internationalization and stuff like that. These 2 weeks, I started working on qualifiers, starting with prominence.

## Upcoming

I guess you guys already know what’s next: more qualifiers. Yup, count of objects, location of object in the media… We’ve got a list of qualifiers, and were gonna add support for them one-by-one.

## One Slight Problem (?)

Coding’s fine, no worries. The problem is more about the project design. We set off hoping to create an easily-navigatable tool, thus the extremely simple UI with just 3 buttons: “True”, “False” and “Skip”.

But then as I started working on qualifiers, I realized that making the tool user-friendly isn’t just about making the UI as simple as possible. Thinking about the qualifiers, I started having another UI design idea. Which is to show the image, and the list of all qualifiers of one depict statement under it, asking the user to label the false ones. Rather than showing a question for every single qualifier statement, this might be a simpler way for the user to understand.

Well that’s just a thought, I’m not sure which way is better. After all, I kind of have 0 experience in UI design. Our team will discuss this issue.

## The End (of the report)

Yup, bye. 😂.

# HTML Assessment

## Description

This project was created to display an understanding of the HTML language by creating text blocks, a table, a list, and a form with multiple inputs.

In this project, I used randomly generated "lorem ipsum" text for the normal text and blockquote. I then took the information from the National Football League's Super Bowl 50 game to fill out the list and table information. I centered the form around sports. It asks what your first and last name are, it has a dropdown menu for your favorite sport, it has a set of checkbox options for if you've ever interacted with the sport in particular ways, and it asks which level of the sport you prefer. At the end of the form, there is a submit button to submit all of the information.

## Lessons Learned

HTML is very straight forward. What you are building in your code is what is usually being reflected on the webpage. However, it is important to keep your code organized. I ran into a few problems with the code purely because I didn't organize it well or look where I was placing my code thoroughly. Some of my inputs would end up outside of the form I had created, and that caused some problems.

I also had a little bit of difficulty at first with nesting certain tags. I would sometimes nest them backwards and it would cause problems with the code.

For example, I tried putting a p (paragraph) tag around a blockquote tag, but it did not work. I then tried to put the paragraph tag inside of the blockquote tag, and it worked. After thinking about it, it made sense that a blockquote would need the paragraph tag nested inside of it, but at the time, it was somewhat confusing.

Here's an example of what I originally tried to do:

`<p><blockquote cite="http://"><strong>Orci</strong> varius natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. (continued)</blockquote></p>`

Here's an example of the resolution:

`<blockquote cite="http://">
      <p><strong>Orci</strong> varius natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. (continued)</p>
    </blockquote>`

## Technologies Used

- Tables.
- Blockquotes.
- Unordered lists.
- Image tags.
- Forms.
- Inputs.
- Select/Option for the dropdown menu.
- Break tags.

## What was the most difficult part of this project?

The most difficult part of this program was the dropdown menu. I had initially thought you would achieve it through being a type of input in a form. However, there are completely separate tags for dropdown menus. I found the select/option tags as the proper way to create a dropdown menu.

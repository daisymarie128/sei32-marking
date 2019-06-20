# SEi32 Project 1 Marking

## Links
Repo: https://github.com/parryjos1/project-1
[Live Site](https://buffetbrokerage.herokuapp.com/)

#### General comments
 Congrats on creating your first website with cool features like logins, sign ups and managing your apps database logic. Big claps to you 👏👏👏

#### Code feedback
I notcied when you signup for an account the password fields arn't protected by being blured out with stars.

This is something you should considering fixing, and luckily it's only going to take a you a few seconds 😀

Instead of using the `:text_filed` tag on line of `views/users/new.html.erb` you just need to use `:password_field_tag` instead 😀

```html
<h3>
<%= link_to "Back to Dashboard", user_path %>
</h3>

<hr>

<h2>
  Current Price of Bitcoin ($USD):   <%= number_to_currency(@current_bitcoin_price) %>
</h2>
```

Considering this block of HTML above ☝️ . It's usually good to follow best practices with your DOM structure. And using headings from the top of the page downwards should start with `h1` then move down accordingly. 

Here you used `h3` then below a `h2` instead this could be written as:

```html
<%= link_to "Back to Dashboard" , user_path :class "dashboard__link" %>

<h1> Current Price ... etc </h1>
```

Then you can just style you class `.dashboard__link` to be the sizing that you want.

I also strongly recommend you spend some time on styling your application, as this is an important skill to learn when becoming a web developer.
So far you've done great with your DOM structure but haven't pushed that far with CSS.

Some tips: 
- Try writting mobile first CSS
	- This means styling your application by writting code for mobiles in mind first. For this you'll have to use `media queries` find out more [here](https://css-tricks.com/snippets/css/media-queries-for-standard-devices/)
- Try styling your buttons, these are always a great way to start developing css skills
- Practice implementing a grid layout using flexbox
	- Try this article for how to get started [article](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)
- Use google fonts to import different fonts and change the colors of them

Also consider deleting unused files in your application you don't need anymore 

Other than that you did a great job getting your functionality working in your application, keep up the good work 👍

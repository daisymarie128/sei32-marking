# SEi32 Project 1 Marking

## Links
Repo: https://github.com/parryjos1/project-1
[Live Site](https://buffetbrokerage.herokuapp.com/)

#### General comments
Great job getting a working website up where you can sign in, sign up and start managing a Database for you application. Big claps 👏👏👏, these things arn't easy and you did a great job. I found some of the pages have some broken links like when trying to create a new gowl, this might be worth fixing before graduation, but don't stress you can clearly see you've got a working application thats managing your databases state. 👍

#### Code feedback
It's great to see you put some time and effort into your CSS and styling, looks like you've learnt how to structure your DOM to place elemensts where you want them to be. 

To take your front end skills further you could perhaps practice implementing a few of these things.
- Implement a grid layout using `flexbox` [how to use it here](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)
- Create a responsive website. This is in relation to making your site work well on a mobile. [Read more about media quries here](https://css-tricks.com/snippets/css/media-queries-for-standard-devices/)
- Create an image gallery for your images.
- Responsive images and positions

Also consider deleting any files or folders which don't end up getting used in the application. This is really important to do, so that any one else who uses the repo later on doesn't get confused by missing files.

Its great to see you using conditionals to render things in your controllers `if user.present? && user.authenticate(params[:password])`

Great stuff keep it up!!

It's also good to see you taking advantage of Rails templating logic
```ror
<% @current_user.goals.each do |goal| %>
```

You could also consider breaking up these parts into seperate template files and importing them. This can help your code become more reabable and seperate concerns in your application.

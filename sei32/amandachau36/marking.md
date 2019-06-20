# SEi32 Project 1 Marking

## Links
Repo: https://github.com/amandachau36/project-1
[Live Site](https://sydney-yoga.herokuapp.com/login)

#### General comments
You did an awesome job with all the features you managed to get implemented in the week. Huge claps to you 👏👏👏
It's always impressive getting a login, sign up, image upload website working, but also really cool for project 1 to see that you got a map working with custom locations as well - great work!!

I think you can very much see your understanding programming and logic well, The things that could be worked on more is your front-end styling. So far you've done a great job with it all, but you could take tis futher in future, more below 😀

#### Code feedback
I like your readme and great to see you put time and effort into writting this. A good readme is a great sign in a developer, so it's important to practice writting these. For future projects practice structuring it with this in mind.
Readmes are for future developers or people that need to work with your code or application. 

Things that are handy to inlcude are - languages and frameworks you used - with version numbers. Also a 1-2 sentence discription of what the repo does. Plus detailed explanation of how to get your code running locally and any deployment methods needed.

Heres a link to a helpful way to write readmes: [article](https://www.makeareadme.com/)

Its awesome to see that already in Prject 1 you've started to implement testing and giving that a go. Really wonderful to see, keep up the good work as this is a great skill to impress employers with!

To improve the testing in the future you could write tests so they cover all the methods for that file. and they return the value you want.
For example in your `bookings controller` you have a unless statement `unless e.present?`

You could write a test to check this scenario is working and return the value you want as well.

Also when creating variables/constants try avoid using short un derscriptive names. Like this code in some of your controllers
```ruby
u = @current_user.id
```

Instead try naming this as `userId` so your code is more readable for the next developer.

I saw you commented this in your `show.erb` file
```html
<!-- How do I get the correct number of stars show up-->
<p><strong>Password: </Strong> ***** </p>
```

You could do something like this to get the right amount of stars:
```html
<% @user.password.length do |star| %>
   <span>*</span>
<%end %>
```

For styling, it would be good to practice some mobile first styling. This will really help your skils on the front end. 

Great work!! 

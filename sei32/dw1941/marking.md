# SEi32 Project 1 Marking

## Links
Repo: https://github.com/dw1941/project-1
[Live Site](https://face-palm.herokuapp.com/)

#### General comments
Great job in geeting a working website going where you can sign up, log in and having images get uploaded. This is great work, and looks like your learning loads. Keep up the great work! 👏👏👏

#### Code feedback
You had a good readme with nice detail about what the app is, how a user can use it and images to support. To improve on this, in the future remeber readmes are for future developers who come across your repo or need to work with your application and code.

Standard practice is to have a 1 or 2 sentence description of what the repo is. Languages and frameworks you've used along with version numbers.

And most importantly how to run your application locally
usually looks something like this:
```
git clone repo...
yarn install
yarn start
open browser to localhost:8080
```

Would be great to see you use additional CSS to center align to divs so you can see the whole image.

It looks like you have a good understanding of tamplates in Rails, great work

It would be great to see you start implementing accessibility tags in your projects. Especially with images. Adding `alt` tags to images can go along way to help this.
This: 
`<%= cl_image_tag(image.url, width: 250, height: 250, gravity: "faces", crop: "fill", class: 'my-images') %>`

Could add this to make it more accessable.
`<%= cl_image_tag(image.url, width: 250, height: 250, gravity: "faces", crop: "fill", class: 'my-images' alt: 'description of image here') %>`

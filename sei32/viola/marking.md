# SEi32 Project 1 Marking

## Links
Repo: https://github.com/viola-hu/project-1
[Live Site](https://face-palm.herokuapp.com/)

#### General comments
Congradulations on building your first ever website!! Awesome work. I love your colors and design on your home page, great to see! 👏👏👏

#### Code feedback
In future it would be great to 
always include a detailed readme for all your repos. This repo just needs a one sentence description, a list of the languages and frameworks you used and how to run your application locally. You can find more information on readmes [here](https://www.makeareadme.com/)

It's awesome to see you got a search funcationality working, great stuff! 

To improve on this you could work on using extra CSS functionality to style your image results into a grid like system.
And perhaps adding a link to the image url as well

You could also consider refactoring some parts like this one below, to use partial rendering to make components more reusable.
```html
<div id='search_form'>
      <%= form_tag recipes_search_path, method:'get' do %>
        <%= text_field_tag :query, nil, placeholder:'search ingredients...'%>
        <%= submit_tag 'Search' %>
      <% end %>
</div>
```

You could also practice accessability standards with your templating. Simple things like adding `alt` tags to images helps with this.

[accessability intro article for the web](https://developer.mozilla.org/en-US/docs/Learn/Accessibility/HTML)

[LightHouse](https://developers.google.com/web/tools/lighthouse/) - This is a chrome dev tool which can help you measure your website and test different things - one inparticular is accessability 😀

Great job! Well done!

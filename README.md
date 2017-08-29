# Homework: Portfolio  website with jekyll

## Project Setup

- Clone the project: ```git clone git@github.com:victorjeman/example-portfolio-jekyll.git```
- Enter the project: ```cd example-portfolio-jekyll```
- Install dependencies: ```gem install```
- Run the projectusing : ```jekyll serve --livereload```

## Project Technologies
- [Jekyll](https://jekyllrb.com/docs/home/)
- [HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)
- [CSS](https://developer.mozilla.org/en-US/docs/Web/CSS)
- [Javascript](https://developer.mozilla.org/en-US/docs/Web/javascript)

## Story
Create a website that will be your personal Portfolio.

```
NOTE: This project doesn't have a specific design.
The students should try to make something original.
This doesn't mean that they can't search for free online design examples and implement them.
```

 This website will have 5 main pages:

```------------------------------------------------------------------------------------```

##### LANDING page

```Description:```
This is the very first page on which a user will land, hence the name.
In this page we will have some summary information taken from other pages.

```EXAMPLE:```https://assist-software.net/

```This page may contain:```
- summary information from other pages.
- text
- pictures
- icons
- socials links
- call to actions banner
- testimonials
- carousel with pictures
- whatever your imagination is giving you

```------------------------------------------------------------------------------------```

##### ABOUT page

```Description:```
In this page the author will have a short description about himself, some interesting pictures, some inspiring quotes and other cool stuff.

```EXAMPLE:``` https://assist-software.net/portfolio

```This page may contain:```
- general information about the author
- what I like
- what I don't like
- what I would love to do in future
- some nice pictures
- a gallery
- more text with different layouts
- whatever your imagination is giving you

```------------------------------------------------------------------------------------```

##### PROJECT LIST page

```Description:```
This page will have a list of thumbnails for personal projects(add some dummy projects in order to have a bigger list)

```EXAMPLE:``` https://assist-software.net/portfolio

```This page may contain:```
- an intro message
- the thumbnail list
- whatever your imagination is giving you

```Each thumbnail may contain:```
- project title
- project small description
- project picture
- se more button
- whatever your imagination is giving you

```------------------------------------------------------------------------------------```

##### PROJECT page

```Description:```
When clicking on the thumbnail for a specific project we will be redirected to this page.

```
NOTE: All project thumbnails could redirect to the same extended project.
In order to avoid the unnecessary work of adding extra dummy projects.
Having one extended project we could focus more on the design the on the content.
```

```EXAMPLE:``` https://assist-software.net/project/english-attack

```This page may contain:```
- various information about the project
- pictures
- technologies used
- whatever your imagination is giving you

## Tasks

```NOTE: In order have a more clean codebase we should try to work using the component approach. What this means? We should write small and independent components that are reusable. A reusable component is one that does not exist only on a specific part of the DOM tree or require the use of certain element types. If necessary, extra HTML elements should be used to make a component reusable. I understand that this approach is highly valuable for web applications but we should use this approach even for small web sites like our example.
```

1. In this first step we should create all the needed markup. We'll think of our site as an application that is created from multiple components. Each component will have a HTML and CSS part and in some cases a javascript part. So first task would be to create all the necessary HTML components(no CSS or JS at this step). This will help us to create a HTML wireframe of our site. The markup should be clean and it should contain the classes that later on will be used for styling.
2. Create all the necessary CSS component files without any styling. In `./_sass/components` you should create a specific file for every HTML component that you defined in the first tasks. There are some examples in `components folder, you can delete them an create your personal components.
3. At this point we should have our components defined. We have the HTML for those components and some scss files that don't have any styles yet. Starting from the top of the landing page, we will start adding css for all our components that should go in that page.
4. At this point We did defined some css components for a certain page. Our markup should be in place then it's time to glue those components together in that page(landing page for example). Task 1. and 3. will be repetead as long as needed until we have our full website.

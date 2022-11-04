# Crash Course: Build a Headless WordPress App with Next.js and WPGraphQL

This crash course is a part of WP Engine's Headless Developer Roadmap. It covers the basics of creating a headless WordPress site using Next.js and WPGraphQL. You can find a step-by-step guide on the WP Engine Developer Relations site. By the end of the course, you will be able to:
- Create static and dynamic routes in Next.js
- Use the GraphiQL IDE to compose GraphQL queries
- Use Apollo Client fetch data in your app
- Choose appropriate Next.js rendering methods based on your content


[✍️ Read the step-by-step tutorial](https://developers.wpengine.com/blog/crash-course-build-a-simple-headless-wordpress-app-with-next-js-wpgraphql)
[📹 Watch the video](https://www.youtube.com/watch?v=wfy51nhjfUQ&t=1680s)

## Getting Started
Follow along with the blog post, and run the following commands to clone this repo:

    git clone https://github.com/JEverhart383/crash-course-headless-wp-next-wpgraphql.git
    cd crash-course-headless-wp-next-wpgraphql
    npm install
    npm run dev


## Headless WordPress Hosting with Atlas

WP Engine's Atlas platform provides a performant and user-friendly hosting platform for headless WordPress and Node-based JavaScript apps. [Create a free sandbox account](https://wpengine.com/atlas/) to try the platform.

## Notes
What is Headless Wordpress?
The main concept of Headless Wordpress, is basically taking the whole CMS to backend and renders the frontend
with some other frameworks. Such as ReactJS or VueJS. The "glue" between Wordpress and in our case NextJS will be GraphQL API.
In Summary, we will create the content as we used todo through Wordpress admin, but the rendering part or the part that the client sees will be generated with NextJS, getting the data from GraphQL.

1. First we will create an wordpress installation, and then we will install a GraphQL plugins enabling data transaction from Wordpress to NextJS.
2. We will also need to make sure the way Wordpress handles permalink or URI to make it directory oriented. Which mean going to WPAdmin -> Settings -> Permalinks and set it to post name
2. We will then clone a WP NextJS scaffolding repo from github called **Crash Course Headless WP Next WPGraphQL**, it's a long name.
3.

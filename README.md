### blog template

- all mdx blog template
- to add a new blog, add a new mdx file in the /src/posts directory, sub folders are allowed
- to add a new medium blog, add it to the file /src/pages/m/[...slug].js
  - the medium blog slug is /m instead of /post, so it will be like /m/your-medium-blog-slug 
- to add a new page, (not a blog page), create a mdx file for it in /src/content directory and create a astro file in /pages directory.
  - for example, the / route fetches the mdx file in /src/content/index.mdx
  - the 404 route fetches the mdx file in /src/content/404.mdx
- i also have a component called Callout, which is currently used in the pydantic blog

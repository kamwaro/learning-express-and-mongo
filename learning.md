# Guides:

1. Express/Node introduction
2. Setting up a Node(Express) development environment
3. Express Tutorial: The Local Library tutorial
4. Express Tutorial Part 2: Creating a skeleton website
5. Express Tutorial Part 3: Using a Database (with Mongoose)
6. EXpress Tutorial Part 4: Routes and Controllers
7. EXpress Tutorial Part 5: Displaying library data
8. EXpress Tutorial Part 6: Working with Forms
9. EXpress Tutorial Part 7: Deploying to production

# 1: Express / Node introduction

- Node is an open-source, cross-platform runtime environment that allows developers to create all kinds of server-side tools and applications in Javascript.
- The runtime is intended for use outside of a browser context.
- The environment omits browser-specific Javascipt API's.
- It adds support for more traditonal OS APIs including HTTP and file system libraries.

## Introdudcing Express:

- Express is the most popular Node Web Framework.

  Its provides mechanisms to:

  1. Write handlers for requests with different HTTP verbs at different URL paths (routes) .
  2. Integrate with "view" rendering engines in order to generate responses by inserting data into templates.
  3. Set common web application settings like the `port to use for connecting`, and the location of templates that are used for rendering the response.
  4. Add additional request processing "middleware" at any point within the request handling pipeline.


    - While Express itself is fairly minimalist, developers have created compatible middleware packages to address almost any web development problem.
    - There are libraries to work with:
        1. Cookies
        2. Sessions
        3. User logins
        4. URL parameters
        5. POST data,
        6. Security headers

# Group Mastery: Discuss Key Frontend Concepts

Spend the next 5-10 minutes writing out answers for the following sub-standards. If you don't have an answer, write out some ideas/notes you have about the topic. Once everyone has their own answers written out we will discuss as a group and go over what an ideal answer looks like.

## Define and Describe AJAX
  - Definition: asynchronous JavaScript and XML
  - Description: Ajax is a set of Web development techniques using many Web technologies on the client side to create             asynchronous Web applications. With Ajax, Web applications can send data to and retrieve from a server asynchronously         without interfering with the display and behavior of the existing page. (Dynamic Content // requesting DATA from API //)
    Page will load... not waiting for information from API.. When information is available, will show on page.

## Define and Describe DOM
  - Definition: Document Object Model
  - Description: The Document Object Model (DOM) is an application programming interface (API) for valid HTML and well-formed                  XML documents. It defines the logical structure of documents and the way a document is accessed and                            manipulated. With the Document Object Model, programmers can build documents, navigate their structure, and                    add, modify, or delete elements and content. Anything found in an HTML or XML document can be accessed,                        changed, deleted, or added using the Document Object Model.

                 - API to interface with the page through JavaScript / DOM gets created first
                 - A tree data srtucture, this root elements (HTML) parent/children elements
                 - created by browser on page load
                 - each element is a node

## Define and Describe CSS
  - Definition: Cascading Style Sheets
  - Description: a style sheet language used for describing the presentation of a document written in a markup language.                        Although most often used to set the visual style of web pages and user interfaces written in HTML and XHTML,                  the language can be applied to any XML document, including plain XML, SVG and XUL, and is applicable to                        rendering in speech, or on other media.

                 - Reads from top to bottom - last/ lower styles override earlier styles
                 - CSS is thew skin of the apllication/page
                 - Styling
                 - can select HTML elements by id or class
                 - the more spacific selection takes precedence

## Define and Describe HTML
  - Definition: Hyper Text Markup Language
  - Description: is the standard markup language for creating web pages and web applications.

                 - the structure/bones of the page/app
                 - defines structure and layout witha variety of tags/elements/attribute

## Describe how events work
  - Description: Event are many, (click, mouseover, scroll, ..etc)
                  - they get attached to DOM Nodes
                  - relationship between listeners / handlers - (function that runs when listener is triggerd)

## Describe jQuery
  - Description: is a JS library that makes it quicker and easier to build JavaScript webpages and web apps.
                  - a collection of functions and methods
                  - DOM manipulation
                  - AJAX
                  - CDN and Download into project

## Describe event delegation / bubbling
  - Description:
      - Delegation: attach listener to parent where the children inherit the
       - attach event listener to parent when dynamically appending information/content

      - Bubbling: Event bubbling directs an event to its intended target, it works like this: A button is clicked and the             event is directed to the button. If an event handler is set for that object, the event is triggered. If no event               handler is set for that object, the event bubbles up (like a bubble in water) to the objects parent.
          - Nested elements with the same elements will trigger parent events.
          - The events Bubble Up

## Describe how linking to stylesheets / images / scripts works as far as requests and responses
  - Description: Loading resourses is a sequence of request
                 - HTML gets loaded first (initial request)
                 - Then reads through the code...
                 - If unavailable <link> or additional resource ..then it makes another requeset

## Describe how urls are resolved in a browser (http://student-galvanize.com/myProfile?name=matt)
  - Description: (http://) protocol hyper text transfer protocol
                 (student- or www) sub-domain
                 (galvanize) domain
                 (myProfile) path
                 (?name=matt) query string

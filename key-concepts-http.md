# Group Mastery: Discuss Key Concepts of HTTP

Spend the next 5-10 minutes writing out answers for the following sub-standards. If you don't have an answer, write out some ideas/notes you have about the topic. Once everyone has their own answers written out we will discuss as a group and go over what an ideal answer looks like.

## Describe and define the parts of a URL
  - Definition: Uniform Resource Locator (URL) or Web Address
  - Description: is a reference to a web resource that specifies its location on a computer network and a mechanism for retrieving it.

## Describe the 3 parts of an HTTP Request
  - Description:
                 1. (METHOD - GET / POST / PUT (edits) / PATCH (edits)/ DELETE)
                 2. (PROTOCOL - HTTP Server needs to know what your asking for || What language)
                    a. (VERSION -  HTTP 0.9 -> HTTP 1.0 Server may need to know this information as well)
                 3. (HEADERS - additional info about request.. )
                 4. (BODY - Data of the request ... if necessary)

## Describe the 3 parts of an HTTP Response
  - Description:
                1. (PROTOCOL - Will match the request)
                    a. VERSION - this make sure we are sinked up
                2. (STATUS CODE - Let's us know if the request succeeded or failed)
                    a. 200 - Success || 404 - Unavailable || 500 - Internal Server Error
                3. (HEADERS)
                    a. ADDITIONAL info about the response
                4. (BODY - Data from request or Response)

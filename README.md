# Audio FIle Server
> WebAPI that simulates the behaviour of an audio file server

## Description and Features
A Web API buikt with FASTAPI that simulates the behavior of an audio file server while using a SQL database. Based on simple REST principles, the  Web API endpoints return JSON metadata about audio files.


Audio file type can be one of the following:
1. Song
2. Podcast
3. Audiobook


## Web API Endpoint Reference
The Web API is based on [`REST`](http://en.wikipedia.org/wiki/Representational_state_transfer) principles. Data resources are accessed via standard HTTPS requests in UTF-8 format to an API endpoint. Where possible, Web API uses appropriate HTTP verbs for each action.

Web API Base URL: [`https://`]()


| Method     | Endpoint                | Usage                     | Reference                |
| -----------| ----------------------- | ------------------------- |--------------------------|
| POST| /api/v1/ | Create |  |
| DELETE| /api/v1/ | Delete |  |
| PUT | /api/v1/ | Update |  |
| GET | /api/v1/ | Return |  |

## Response Status Code

This Web API uses the following response status codes, as defined in the [RFC 2616](https://www.ietf.org/rfc/rfc2616.txt) and [RFC 6585](https://www.ietf.org/rfc/rfc6585.txt):

| STATUS CODE | DESCRIPTION                |
| ----------- | ---------------------------|
| 200 | OK - The request has succeeded. The client can read the result of the request in the body and the headers of the response. |
| 400 | Bad Request - The request could not be understood by the server due to malformed syntax.  |
| 500 | Internal Server Error. |

## Authentication
All requests to this Web API require authentication. This is achieved by sending a valid OAuth access token in the request header. 


## Installation

OS X & Linux:

```sh
npm install my-crazy-module --save
```

Windows:

```sh
edit autoexec.bat
```

## Usage example

A few motivating and useful examples of how your product can be used. Spice this up with code blocks and potentially more screenshots.

_For more examples and usage, please refer to the [Wiki][wiki]._

## Development setup

Describe how to install all development dependencies and how to run an automated test-suite of some kind. Potentially do this for multiple platforms.

```sh
make install
npm test
```

## Release History

* v1
    * The first proper release
    * CHANGE: Rename `foo()` to `bar()`


## Meta

Doyinsolami Samuel OLAOYE – [LinkedIn](https://www.linkedin.com/in/doyinsolami-olaoye/) | [Email](doyinsolamiolaoye@gmail.com) | [GITHUB](https://github.com/doyinsolamiolaoye/)

Distributed under the `MIT` license. See ``LICENSE`` for more information.


<!-- Markdown link & img dfn's -->
[wiki]: https://github.com/yourname/yourproject/wiki

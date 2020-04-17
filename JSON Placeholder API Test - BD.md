# JSON Placeholder API Test

## Introduction

The objective of this exercise is to test API&#39;s endpoints for &quot;posts&quot; provided by JSON Placeholder [https://jsonplaceholder.typicode.com/](https://jsonplaceholder.typicode.com/)

## Available Resources

- Posts [https://jsonplaceholder.typicode.com/posts/1](https://jsonplaceholder.typicode.com/posts/1)
- Comments [https://jsonplaceholder.typicode.com/comments/1](https://jsonplaceholder.typicode.com/comments/1)
- Albums [https://jsonplaceholder.typicode.com/albums/1](https://jsonplaceholder.typicode.com/albums/1)
- Photos [https://jsonplaceholder.typicode.com/photos/1](https://jsonplaceholder.typicode.com/photos/1)
- Users [https://jsonplaceholder.typicode.com/users/1](https://jsonplaceholder.typicode.com/users/1)
- Todos [https://jsonplaceholder.typicode.com/todos/1](https://jsonplaceholder.typicode.com/todos/1)

**Note** : resources have relations. For example: posts have many comments, albums have many photos, see below for routes examples.

## Resources Under Test

| GET | [/posts/1](https://jsonplaceholder.typicode.com/posts/1) |
| --- | --- |
| GET | [/posts/1/comments](https://jsonplaceholder.typicode.com/posts/1/comments) |

**Note** : you can view detailed examples [here](https://github.com/typicode/jsonplaceholder#jsonplaceholder).

## Important Note

To avoid problems with firewalls/antivirus checker, please do **not include** any binary executable files (delete _bin_, _obj_ folders etc.) before submitting the test.

## Task

Test the two provided API&#39;s under test by employing automated C# acceptance tests (preferably .Net Core). The Test Solution may be expanded on in the future, so please use SOLID principles in its implementation.

Note: The test Requirements are sparse to let us see what tests you would think of without being boxed in. Think of as many test scenarios you can by simply exploring the API&#39;s under test.

Report your findings and indicate whether you would sign off the implementation for release into production?

### Expected format for automated tests and restrictions

- You **may not** collaborate with others or post this on a discussion board.
- Check-in your solution / project to GitHub using your personal account and share link to your project with us.
- The findings report can be a simple bulleted list (no special formatting expected).

## Good luck!

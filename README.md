# Todo List API Challenges

## About the project

This project includes my solutions to the [evil tester's API challenges](https://apichallenges.herokuapp.com/apichallenges). The API is used to manage a To-Do list with simple CRUD (Create, Read, Update, Delete), [here is the API documentation](https://apichallenges.herokuapp.com/docs).

Here is a diagram that I made that visualises the API:

![A UML-style diagram of the todo list API](./docs/api-diagram.png)

## Test Approach

Although the app is runnable locally, I decided to develop my tests against the public cloud instance (https://apichallenges.herokuapp.com/).

- [Simply doing the challenges](./docs/challenges-list.pdf) - Initially I went through the challenges as listed. This helped me to learn more about the API, REST methods, different response codes.
- Going beyond the challenges - Now that I finished the challenges, I can think more about how to implement automated checks and other tests beyond the challenges.

## Tools used

| Tool                                                                                                                                                                          | Description                                                                                                                          |
| ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------ |
| <a href="https://www.usebruno.com/"><img src="https://github.com/usebruno/bruno/raw/main/assets/images/logo-transparent.png" width="120" alt="Icon of Bruno API client"/></a> | Bruno v1.18.1 (API client) MacOS version - To read and write API requests and responses, write simple asserts e.g. check for 200 OK. |

## Challenges I faced

1. Test Data Availability - On the cloud instance, the test data clears itself every 10 minutes so this makes my testing less efficient. Luckily, the API supports the save/restore of session data.

## List of issues found

[See logged issues on the eviltester repo](https://github.com/eviltester/thingifier/issues/created_by/p2635) (this is filtered by the issues that I logged).

## What I learned

- I learned to use the Bruno API client - configure variables, headers, auth, simple asserts, inspecting response.

## License

[MIT](LICENSE)

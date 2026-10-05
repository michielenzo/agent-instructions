## Intro

This is a shared instructions file that should be inherited by AGENTS.md in other git repositories. The instructions of the inheriting AGENTS.md take precedence over conflicting shared instructions.

## Repository structure

How the repository works and information about its features should be described in the README.md. The README.md sits at the root of the project and follows the following format:

> ### Table of Contents
> - [Development](#development)
> - [Overview](#overview)
> - [Features](#features) 
> - [Architecture](#architecture)

| Chapter      | Description                                                                                  |
| ------------ | -------------------------------------------------------------------------------------------- |
| Development  | This chapter describes how to setuup the local development environment and how to deploy it. |
| Overview     | This is a quick summary of the project and its purpose.                                      |
| Features     | This chapter explains all the features of the project and how the user can use them.         |
| Architecture | This chapter describes the high-level architecture of the project.                           |

Make use of additional AGENTS.md in different components of the project. If you feel like some architectural explanation can be made about a component document that in its root with this AGENTS.md Make sure this is readable for both agents and humans.

## Coding style

- If the code does something unexpected or unusual A comment should be placed explaining what it does and why.
- Make sure to apply the Single Responsibility principle.
  - Don't go overboard with this principle if it makes the code less readable

## Testing

Write unit tests if applicable for the technology that is used. While working use these tests to verify your changes.

If applicable make use of frontend integration testing.  Think about technologies such as playwright, selenium etc.

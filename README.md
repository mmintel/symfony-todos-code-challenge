![i22 Logo](resources/assets/i22_web-styleguide_down_wortmarke1rgb_blau.png "i22")

# Symfony todos code challenge
**symfony-todos-code-challenge** is a code challenge for fullstack developers.
for the frontend counterpart see (https://github.com/i22-digitalagentur/vue-todos-code-challenge)

## Scenario
So here you are! You decided to apply for a job at i22 and now they are asking you to help them out.
Unfortunatley we decided to create one more todo app which the world doesn't need and your task is to finish this one.

Our team was already able to complete the following:
* Create the symfony skeleton with `composer create-project symfony/skeleton symfony-todos-code-challenge`
* Adding Symfony WebServer with `composer require server --dev`
* Adding Symfony FrameworkBundle with `composer require symfony/framework-bundle`
* Adding ORM-Pack for Doctrine Usage with `composer require symfony/orm-pack`
* Adding Debug-Pack for Debugging with `composer require symfony/debug-pack --dev`
* Created first entity `Task` for our cool todos app

## Mission
- [] create api for listing all existing todos
- [] create api for creating a new todo
- [] create api for updating the status of a todo
- [] create api for deleting a todo
- [] apply usefull validations
- [] apply alice fixtures to generate some test data
- [] write some tests

## Please Note
- Pay attention to your code style, we like it clean and simple
- We are using DataTransferObject for validation, because entites should always be in a valid state, see (https://ocramius.github.io/doctrine-best-practices/#/)

## When in trouble
- We don't expect you to finish everything in one day.
- Focus on the *esentials*, do *bonus* only if there is time left.
- Don't focus only on one part (backend / frontend). this is a fullstack code challenge, so if time is missing, you should have done at least one mission from both frontend and backend
- Ask your colleagues, they are friendly.
- Also google is your friend.

## Project setup

```
composer install
bin/console doctrine:database:create
bin/console doctrine:schema:create
bin/console server:start
```


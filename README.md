# gh-actions-workflows

## What you'll learn

- Learn about writing serialized data in the YAML format.
- Learn about all the GitHub Actions concepts (Workflows, Steps, Jobs, Actions, etc..)
- Discover everything you can do in a GitHub workflow (events, schedules, filtering, environment variables, context, encryption, matrix and more)
- Learn how docker can be used in a GitHub workflow
- Create a real-life CI/CD workflow for code testing, formatting, versioning and more.
- Use caching in workflows for an improved performance.
- Learn about uploading artifacts in workflows.
- Learn about how to create your own custom GitHub Actions using Javascript or Docker
- Create an action for opening GitHub issues using JavaScript.
- Create an action for sending slack messages using PHP.
- Learn how to publish GitHub actions in the GitHub marketplace.

## Requirements

- You should have basic GitHub knowledge
- Some lectures will require some basic docker knowledge (it's not necessary if you want to skip it)
- Creating custom actions requires JavaScript and/or docker knowledge
- For some sections some stuff must be installed on your machine including: nodejs, npm, docker, composer, php.
- The last section requires an AWS account if you follow actively and you might be charged.

## Description

**NOTE: The last section in the course requires an AWS account and you might be charged if you follow the section actively. Check the promo video for more information.**

GitHub recently released GitHub Actions", a CI service competitor to services like TravisCI and CircleCI. GitHub Actions however has the edge of being natively integrated with your GitHub repository. In addition to that, thanks to GitHub's popularity; GitHub Actions has the advantage of having large ecosystem and community. Using GitHub Actions you will find a lot of official and community pre-made workflows and also the actions marketplace. In the actions marketplace you can find tons of actions which are reusable pieces of code that you can use in your workflows to perform certain tasks like deploying code, interacting with API's, sending SMS's, etc..

Learn everything you need to know in order to create GitHub workflows & Actions.
In this course we will comprehensively explore GitHub's CI service. We are going to learn what GitHub workflows & actions are. And we will discover everything we can do in a GitHub workflow including how to run commands, use actions, trigger workflows, build matrices, reuse workflows, use docker and more.  We are going to learn how to write custom actions and publish them to the marketplace so that other people can use them.  Finally, we will use what we learned to create a real-world example of a CI/CD workflow where we will test, build, deploy a web application to AWS.

Let's take a look at what will be discussed in each section in more detail:

### Section 1

In section 1 we will have a conceptual introduction to Github Actions. We are going to learn what terms like workflows, actions, jobs, steps and other terms mean. We are also going to learn about YAML which is the format used to write workflows in GitHub. Then we will start writing our first workflow and take a look at basic things like writing commands, using different shells and using actions including the most common action which is the checkout action.
### Section 2
In section 2 we will get a bit deeper and learn different ways that we can use in order to trigger a workflow to run. This includes GitHub events like push and pull_request, external events, manual events and CRON schedules. We will also see how to make a workflow only run for certain branches, tags and directory paths.
### Section 3
In this section we will take a look at how to write expressing in a workflow. And how to use context information and functions in our workflows. We will also see how can we use default environment variables and also how to add custom environment variables. We will discover how to encrypt sensitive information and also how to encrypt and decrypt sensitive files that we don't won't to push to our repository. Moreover, we will take a look at the GITHUB_TOKEN environment variable and how to use it to perform certain actions and how to customize its permissions.
### Section 4
In section 4 we will see how can we setup matrices, a matrix is a way to run a job multiple times but using different configurations. We will also learn about concurrency and how to reuse our workflows to avoid duplication. We are also going to take a look at caching and uploading and downloading artifacts.
### Section 5
In section 5 we are going to discuss using docker in GitHub Actions. We are going to see how to use docker images in our jobs and steps. We are also going to learn about running multiple service containers together and see how to communicate between them. Finally we are going to see how can we automate publishing docker images to DockerHub and the GitHub Container Registry.
### Section 6
During the course we will use some actions that are available in the marketplace. But in this section we are going to learn how to create our own actions. Actions can be created using JavaScript or using Docker. In this section we are going to learn about both ways and then we will create a JavaScript action that opens GitHub issues and a docker action that sends a slack message which we will write using PHP. We will also discover another way of writing actions which is Composite Actions.
### Section 7
In section 5 we will finally use our knowledge to create a real-world CI/CD example. In this section we are going to use an Amazon service called Elastic Beanstalk to deploy our app. We are going to use feature flags to continuously integrate and deploy our app without exposing all features to the end user. We are going to automate versioning our app and generating changelogs. In addition to that, we are going to add the option to deploy pull request branches to an isolated AWS environment and also add the option to destroy that environment. We are finally going to see how to use OpenID Connect to access AWS from our workflows without having to store any credentials.

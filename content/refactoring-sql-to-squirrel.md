+++
title = "Refactoring SQL to Squirrel"
date = 2023-06-22
draft = true
+++

An open source project that I've contributed to previously is [Mattermost](https://github.com/mattermost/mattermost), a messaging platform that is marketed as an alternative to Slack, where I added automated UI tests using the [Cypress](https://www.cypress.io/) library.
Mattermost's server code is written in Go, presenting a great opportunity for me to put my newfound skills to use.
On Mattermost's GitHub issues page, they have created labels to assist in narrowing down potential items for the community to work on.
Luckily, I found an issue that involved refactoring some raw SQL query strings to use the [Squirrel](https://github.com/Masterminds/squirrel) library.

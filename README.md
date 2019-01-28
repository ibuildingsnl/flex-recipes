# Ibuildings Flex Recipes

A repository for Symfony Flex recipes not distributed through the official repositories.

## Requirements
* Symfony Flex: ^1.1

## Instructions

To make use of these recipes:

* Run `composer symfony:generate-id` once. 
* This will generate an id which you'll need to add here: [config.json](config.json)
* `composer req <package>`

## Packages

* qa-tools: A preconfigured set of QA Tools for PHP (focussed on Symfony) 

## Development
To add or update a recipe please create PR's which allow the Symfony Flex integration to run QA checks and create a 
staging environment. 

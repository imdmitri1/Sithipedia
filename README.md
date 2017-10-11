# README

# Sithipedia
### By Marla, Gwynne, and Dmitri
[![Coverage Status](https://coveralls.io/repos/github/chi-nighthawks-2017/sithipedia/badge.svg?branch=master)](https://coveralls.io/github/chi-nighthawks-2017/sithipedia?branch=master)
[![Build Status](https://travis-ci.org/chi-nighthawks-2017/sithipedia.svg?branch=master)](https://travis-ci.org/chi-nighthawks-2017/sithipedia)
Our client has asked us to design a Wikipedia type application for Star Wars siths of the Dark Side.

## MVP User stories
### Key:
* Apprentice = unregistered user
* Master = registered user
* Lord = administrator
* User = all of the above

#### Creating New Articles
* As a Lord or Master, I want to be able to create a new article. The article may be published or unpublished (draft).

#### Viewing Articles & Versions
* As a user (Apprentice, Master, and Lord) I want to see a home page with a list of articles and some details. Featured articles should be displayed first, then the rest of the articles.
* As user, I want to be able to click on a link in the index to view the full article.
* As a user, I want to be able to see all previous versions of the article.
* As a user, I want to be able to search for articles by title.

#### User Authentication
* As a user, I want to be able to register and become a Master (registered user).
* As a user, I want to be able to log in to my Master or Lord account.

#### Draft (unpublished) Articles
* As a Lord, I want to be able to see articles that are currently unpublished (drafts).
* As a Master, I want to be able to see my articles that are unpublished (drafts).

#### Categories & Photos
* As a Master, I want to be able to choose a category for an article I authored.
* As a Lord, I want to be able to choose a category for any article.
* As a Master or Lord, I want to be able to create a new category if it doesn't exist yet.
* As a Master who authored an article, or a Lord, I want to be able to add photos to an article and version.

#### Editing Articles (creating a new version)
* As a Master, I want to be able to edit articles I authored - creating a new version.
* As a Lord, I want to be able to edit all articles (even those I didn't author) - creating a new version.

#### Editing User Authorization
* As a Lord, I want to be able to upgrade a Master's rank to be a Lord.

### Stretch goals
* As a user, I want to be able to view all articles from a given category.

This README would normally document whatever steps are necessary to get the
application up and running.

### Quickstart

1.  `bundle install`
2.  `bundle exec rake db:create`
3.  `bundle exec rake db:migrate`
4.  `bundle exec rake db:seed`
5.  `bundle exec shotgun config.ru`
6.  Open [http://localhost:9393](http://localhost:9393)

Things you may want to cover:

* Ruby version
* System dependencies
* Configuration
* Database creation
* Database initialization
* How to run the test suite
* Services (job queues, cache servers, search engines, etc.)
* Deployment instructions

# magnolia-blog
Blog app for [Magnolia cms](http://www.magnolia-cms.com).

In this module we provide a content app to create/edit/delete blog articles fast and easy. Select an author, write your blog, include photos and publish it right away.

Create your own website components with nl.tricode.magnolia.blogs.templates.BlogRenderableDefinition
to add to your Magnolia website.

## Prerequisites
* [git](http://git-scm.com/)
* [java 8](http://java.com)
* [Maven 3](http://maven.apache.org)

## Features
* Content App for creating/modifying blog items
* Templating Functions methods for using blog data in Freemarker
* Import existing Wordpress blog posts
* Using Magnolia Contacts app for blog author
* Optional use of Categories (Magnolia Categorization module will be added in the near future)

##License
Copyright (c) 2015 Tricode and contributors. Released under a [GNUv3 license](https://github.com/tricode/magnolia-blog/blob/master/license.txt).

##Release notes 1.1.3.
* Added correct query for nodes that needs to deactivated.
* Update to Java 7.
* Update to Magnolia 5.4.3.
* Update Magnolia scheduler module 2.2.2.
* Separation of Jcr queries.

##Release notes 1.1.4
* Upgrade to Magnolia 5.4.4

##Release notes 1.1.5
* Failed Release, use 1.1.6

##Release notes 1.1.6
* Upgrade to Magnolia 5.5
* Update to Java 8
* Detected dependency issues with this version. Will be resolved in next version.

##Release notes 1.1.7
* Fix for the dependency issues.

##Release notes 1.1.8
* Add 'publish date' to blogs

##Release notes 1.1.9
* Prevent huge stacktraces in logs when blog authorId is not found

##Release notes 1.1.10
* Update to Magnolia 5.5.3 + Nexus URL update
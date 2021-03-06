---
title: Migrate to Hugo
linktitle: Migrations
description: A list of community-developed tools for migrating from your existing static site generator or content management system to Hugo.
date: 2017-02-01
publishdate: 2017-02-01
lastmod: 2017-02-01
#tags: [migrations,jekyll,wordpress,drupal,ghost,contentful]
menu:
  docs:
    parent: "tools"
    weight: 10
weight: 10
sections_weight: 10
draft: false
aliases: [/developer-tools/migrations/,/developer-tools/migrated/]
toc: true
---

This section highlights some projects around Hugo that are independently developed. These tools try to extend the functionality of our static site generator or help you to get started.

{{% note %}}
Do you know or maintain a similar project around Hugo? Feel free to open a [pull request](https://github.com/gohugoio/hugo/pulls) on GitHub if you think it should be added.
{{% /note %}}

Take a look at this list of migration tools if you currently use other logging tools like Jekyll or WordPress but intend to switch to Hugo instead. They'll take care to export your content into Hugo-friendly formats.

## Jekyll

Alternatively, you can use the new [Jekyll import command](/commands/hugo_import_jekyll/).

- [JekyllToHugo](https://github.com/SenjinDarashiva/JekyllToHugo) - A Small script for converting Jekyll blog posts to a Hugo site.
- [ConvertToHugo](https://github.com/coderzh/ConvertToHugo) - Convert your blog from Jekyll to Hugo.

## Ghost

- [ghostToHugo](https://github.com/jbarone/ghostToHugo) - Convert Ghost blog posts and export them to Hugo.

## Octopress

- [octohug](https://github.com/codebrane/octohug) - Octopress to Hugo migrator.

## DokuWiki

- [dokuwiki-to-hugo](https://github.com/wgroeneveld/dokuwiki-to-hugo) - Migrates your dokuwiki source pages from [DokuWiki syntax](https://www.dokuwiki.org/wiki:syntax) to Hugo Markdown syntax. Includes extra's like the TODO plugin. Written with extensibility in mind using python 3. Also generates a TOML header for each page. Designed to copypaste the wiki directory into your /content directory.

## WordPress

- [wordpress-to-hugo-exporter](https://github.com/SchumacherFM/wordpress-to-hugo-exporter) - A one-click WordPress plugin that converts all posts, pages, taxonomies, metadata, and settings to Markdown and YAML which can be dropped into Hugo. (Note: If you have trouble using this plugin, you can [export your site for Jekyll](https://wordpress.org/plugins/jekyll-exporter/) and use Hugo's built in Jekyll converter listed above.)

## Tumblr

- [tumblr-importr](https://github.com/carlmjohnson/tumblr-importr) - An importer that uses the Tumblr API to create a Hugo static site.
- [tumblr2hugomarkdown](https://github.com/Wysie/tumblr2hugomarkdown) - Export all your Tumblr content to Hugo Markdown files with preserved original formatting.
- [Tumblr to Hugo](https://github.com/jipiboily/tumblr-to-hugo) - A migration tool that converts each of your Tumblr posts to a content file with a proper title and path. Furthermore, "Tumblr to Hugo" creates a CSV file with the original URL and the new path on Hugo, to help you setup the redirections.

## Drupal

- [drupal2hugo](https://github.com/danapsimer/drupal2hugo) - Convert a Drupal site to Hugo.

## Joomla

- [hugojoomla](https://github.com/davetcc/hugojoomla) - This utility written in Java takes a Joomla database and converts all the content into Markdown files. It changes any URLs that are in Joomla's internal format and converts them to a suitable form.

## Blogger

- [blogimport](https://github.com/natefinch/blogimport) - A tool to import from Blogger posts to Hugo.

## Contentful

- [contentful2hugo](https://github.com/ArnoNuyts/contentful2hugo) - A tool to create content-files for Hugo from content on [Contentful](https://www.contentful.com/).

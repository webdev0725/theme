# Incognito
Location: https://theseoframework.com/extensions/incognito/
License: GPLv3
License URI: http://www.gnu.org/licenses/gpl-3.0.html

This extension removes all development-comments from The SEO Framework.

## Overview

### A clean view

The SEO Framework is a very clean plugin. It helps you boost SERP presence without obstructing your WordPress experience.

To increase growth and help web developers to see where The SEO Framework is active, The SEO Framework outputs obscure annotations.

Not every web developer likes these annotations. If you're one of those developers, this extension is for you.

### How it works

Unlike other SEO plugins, The SEO Framework allows you to remove the annotations mentioned above easily through filters.

This extension uses those filters to disable the annotations. That's all there's to it.

Filters are the foundation of WordPress development. The filters in this extension merely act as an off switch.
For this reason, this extension won't affect performance when enabled.

### Which annotations are removed?

1. HTML comments around the metadata, annotated by e.g. `<!-- Start The SEO Framework by Sybre Waaijer -->`.
2. The [tsfep-extension name="title-fix"] annotation for that the title is fixed: `<!-- Fixed -->`.
3. At the bottom of the styled sitemap: `Generated by The SEO Framework`.

## Usage

[tsfep-bundled]

### Activate Incognito

All you must to do is activate the Incognito extension.

There is no setup required, and no options are available.

### Page and Browser Caching

If you're using a page caching solution, you might need to refresh the cache before the in-page annotations are removed.

The sitemap's stylesheet is cached in the browser for 30 minutes.
To see results, you could either wait for it to expire or perform a [forced refresh](https://refreshyourcache.com/en/cache/).

## Changelog

### 1.1.0

[tsfep-release time="February 17th, 2017"]

* **Added:** Now also removes The SEO Framework 2.8.0 sitemap stylesheet plugin annotation.

### 1.0.0

[tsfep-release time="January 1st, 2017"]

* Initial extension release.

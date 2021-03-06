---
layout: layout-hoodieverse
locales: de
---

# Welcome to Hoodie

## What is Hoodie?

Hoodie is library/server package for frontend web applications that abstracts away the backend. If you love working in jQuery, Backbone, Dojo, Ember, or any other frontend framework, but *dread* backend work, Hoodie is for you.

Hoodie gives your frontend code superpowers, by allowing you to do things that usually, only a backend can do (user accounts, emails, payments, etc.).

All of Hoodie is accessible through a simple script include, just like jQuery or lodash:

<pre><code class="language-markup">&lt;script src="hoodie.js"&gt;&lt;/script&gt;
&lt;script type="javascript"&gt;
  var hoodie = new Hoodie();
&lt;/script&gt;</code></pre>

Hoodie is a frontend abstraction of a generic backend web service. As such, it is agnostic to your choice of frontend application framework. For example, you can use jQuery for your web app and Hoodie for your connection to the backend, instead of raw jQuery.xhr. You could also [use Backbone with Hoodie as a data store](https://github.com/hoodiehq/backbone-hoodie), or any other frontend framework, really. There are also efforts to add Hoodie support to [Angular](https://www.npmjs.com/package/hoodie-plugin-angularjs) and [Ember](https://github.com/gr2m/ember-hoodie-adapter).

## Open Source

Hoodie is an Open Source project, so we don't own it, can't sell it, and it won't suddenly vanish because we got aquired. <a href="http://github.com/hoodiehq" target="_blank">The source code for Hoodie is available on GitHub</a> under the Apache License 2.0.

## How to proceed

You [could read up on some of the ideological concepts behind Hoodie](/en/hoodieverse/hoodie-concepts.html), such as noBackend and Offline First. These explain why Hoodie exists and why it looks and works the way it does.

If you're more interested in the technical details of Hoodie, check out [How Hoodie Works](/en/hoodieverse/how-hoodie-works.html). Learn how Hoodie handles data storage, does syncing, and where the offline support comes from.

Eager to build stuff? Skip ahead to the [installation guide](/en/start/)!

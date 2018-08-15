---
title: API Reference

language_tabs:
  - javascript

toc_footers:
  - <a href='https://www.bizzey.be/sign_up'>Sign Up for an API key</a>

includes:
  - 1.authentication
  - 2.errors
  - 3.clients
  - 4.projects
  - 5.invoices
  - 6.entries
  - 7.taxes
  - 8.expenses
  - 9.me

search: true
---

# Introduction

The Bizzey API is organized around REST. Our API has predictable, resource-oriented URLs and uses HTTP response codes to indicate API errors. We use built-in HTTP features, like HTTP authentication and HTTP verbs which are understood by off-the-shelf HTTP clients. We support cross-origin resource sharing [cross-origin resource sharing](http://en.wikipedia.org/wiki/Cross-origin_resource_sharing), allowing you to interact securely with our API from a client-side web application. [JSON](http://www.json.org/) is returned by all API responses, including errors.

**The requests in the right sidebar are designed to work as is.** The sample requests are performed using an API key, linked to your account under the account section inside Bizzey. Only you can see this account-specific value.


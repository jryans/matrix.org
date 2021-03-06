---
layout: project
title: matrix-redux-wrap
categories: projects sdk
description: A library that exposes matrix-js-sdk state via Redux
author: Luke Barnard
maturity: Stable
language: JavaScript
license: Apache
repo: https://github.com/lukebarnard1/matrix-redux-wrap
---

# {{ page.title }}
Matrix Redux Wrap was motivated by the need to expose the Matrix protocol via a Redux store. The matrix-js-sdk API does not expose a Redux-like pattern through which data flows but rather a number of asyncronous HTTP-request wrappers and a number of models that encapsulate the objects within the Matrix protocol. These models are updated by a mixture of server responses and API calls and do not necessarily lend themselves to simple mental models or the ability to be incorporated into frameworks such as Flux and Redux.

Repository: <{{page.repo}}>

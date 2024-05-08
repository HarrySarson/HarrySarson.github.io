---
title: SarsonWedding
description: Website for my wedding
date: "2021-06-05"
jobDate: 2024
work: []
techs: [elm]
thumbnail: sarsonwedding/thumbnail.png
projectUrl: https://harrysarson.github.io/sarsonwedding
---

A simple but visually pleasing website to provide information to family and friends.
To view the website you will need the password `050621` (the date of the wedding).
The website has two main parts, an entry page written in html and typescript and the main website written in elm.

The most interesting part of the website is its password protection.
The source of the website is hosted in a [public git repo](https://github.com/harrysarson/sarsonwedding) but all the interesting information is encrypted (see [the encrypted.ts file](https://github.com/harrysarson/sarsonwedding/blob/main/ts/encrypted.ts)).
I did not want to run a backend due to the cost and effort.
Neither did my integrity allow me to implement a solution that could be bypassed via modification of the javascript running on the page.
So I was really please to find a scheme for adding password protection (ostensibly to deter wedding gatecrashers) based on storing encrypted information in the source that runs entirely in the frontend but is still secure.

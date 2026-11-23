---
title: "Completing the Aurelia Contact Manager Tutorial"
description: "A few gotchas encountered while following the Aurelia Contact Manager tutorial in 2017."
date: 2017-07-16
---

I ran into a couple of issues while trying to run through the [Contact Manager tutorial](http://aurelia.io/hub.html#/doc/article/aurelia/framework/latest/contact-manager-tutorial/1) for Aurelia.

First, you should probably stick to ES2015 as the JavaScript option in aurelia-cli when creating the project. TypeScript has its own gotchas with this tutorial that I might go through if I have time later.

Second, I didn't have any problem with installing the latest version of jQuery with this tutorial - 3.2.1 as I write this.

After you install jQuery and Bootstrap in the tutorial, make sure that you stop the au run command and restart it. See [here](https://github.com/aurelia/cli/issues/508) for more details.

Later on in the tutorial, make sure you put the loading-indicator.js file in the src/resources/elements folder. I definitely didn't just put it in the src folder and wonder why it wouldn't work.

Nope.

That didn't happen.

In other news, I think the next few posts will be about the 'more ideas' that are at the end of this tutorial.

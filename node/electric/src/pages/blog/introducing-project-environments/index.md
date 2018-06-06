---
title: "Introducing Project Environments"
description: "From dev to staging to production, now you easily organize, duplicate and manage multiple application stages with WeDeploy Project Environments."
date: "June 11, 2018"
author: "Jonni Lundy"
image: "/images/blog/post-30--0.jpg"
layout: "blog"
---

<article>

Our goal is to build effective tools to make developers more successful.

Today, we are releasing a new feature that we believe will enable both solo developers and large teams alike in their pursuit of shipping incredible apps, faster.

<figure>
  <img src="/images/blog/post-30--0.jpg" alt="new environment">
  <figcaption>WeDeploy Project Environments</figcaption>
</figure>

{$page.description}

#### Why Environments?

Having multiple environments for your project is a powerful way to organize your releases and share those versions with the people you need to.

Here are some of our favorite environments to use:

* **dev**: for exploring breaking changes
* **testing**: for your QA team to run tests
* **staging**: for getting feedback from the team about the upcoming release
* **prod**: for publishing the new version of your app to the world

Having these stages in your development process seamlessly grouped together in your app's WeDeploy project will make it even easier to quickly and confidently push new changes to your users.

#### How Do Environments Work?

Each project begins with its default, or production, environment. Projects with just one environment will look and behave like your old projects.

<figure>
  <img class="blog-img-shadow" src="/images/blog/post-30--1.png" alt="single environment">
</figure>

From there, you can create a new environment by duplicating that original environment. All environments will bear the ID of the original project and then append the new environment name (e.g. `project-env`).

<figure>
  <img class="blog-img-shadow" src="/images/blog/post-30--2.png" alt="creating environment">
  <figcaption>Easily duplicate environments and customize environment variables</figcaption>
</figure>

Each Environment behaves like a separate projects so you can add unique collaborators, custom domains, environment variables, and even services to each one.

This means each environment can have its own configuration like datasets or user access.

<figure>
  <img class="blog-img-shadow" src="/images/blog/post-30--3.png" alt="creating environment">
  <figcaption>Add unique contributors to each environment</figcaption>
</figure>

So what are you waiting for? **[Login to your account](https://console.wedeploy.com)** and create a new environment for any of your projects!

---

We are very excited for you to try this new feature and to see how you use it to deploy amazing applications!

If you need any help getting started or want to give us feedback, please **[join our WeDeploy Community](https://chat.wedeploy.com)** or **[follow us on Twitter](https://twitter.com/wedeploy)**.

</article>

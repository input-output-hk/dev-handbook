---
title: "Cardano Development process"
---

# Cardano Development process

Welcome to the Cardano development process documentation, a community curated
guide to how we develop software on the cardano project.

## Purpose

The purposed of this documentation is to explain the standards and processes in
place for contributing to cardano. As we are a distrribute team working on a
project that's designed to last many decades, consistency and common
understanding is extremely important. The instructions and best practices laid
out here are intended to evolve and develop along with our understanding of
how to do our best work and build the most robust cryto currency and
infrastructure in the world.

## Contribute to this documentation
This project is open source and is hosted {{< github-link "at github" >}}. For
convenience there's also a link on all the content pages which will take you
directly to the markdown for that page. Just click the **Edit this page** link
displayed on top right, and create a pull request to update the content.
Deployment is automatic after the PR has been approved and merged.


## Documentation website
This current documentation has been statically generated with Hugo. If you want
to run and build locally you can do so by cloning
{{< github-link "this repository" >}}
and then running

```
hugo server -D
```

Changes you make to any of the file in the `content` directory will be reflected
immediately at the development site running at <http://localhost:1313>.

The documentation is also automatically built on any PR or branch and deployed when the master branch changes

{{% notice note %}}
Automatically published and hosted thanks to
[Netlify](https://www.netlify.com/).
Read more about
[Automated HUGO deployments with Netlify](https://www.netlify.com/blog/2015/07/30/hosting-hugo-on-netlifyinsanely-fast-deploys/)
{{% /notice %}}

---
title: 'GSoC Starter: kw lore interface'
date: 2022-06-13 20:30 -0300
categories: kw GSoC
tags: gsoc kw
---

It is June 13, 2022 and it marks the official [beginning][gsoc-timeline] of the
GSoC coding period. I was accepted as a contributor in the program to contribute
to the *[Kernel Workflow][kw]* (**kw**) tool. My [project][gsoc-project]
proposes the implementation of an interface to access and download patches that
have been sent to the Linux kernel public mailing lists and are available via
the [lore][lore] archive, and also integrate it with the current kw features,
such as *build* and *deploy*.

I have spent the last few weeks preparing the project and organizing what my
contributions will be. In addition to this blog, I have created issues on the
**kw** GitHub page, and organized them on a project [board][kw-board] and a
[milestone][kw-milestone] which I'll be using to manage my tasks and track my
progress, and so can you!

In this first week I'll be focusing on integrating the prototype of the library
we'll use to access and download the lore archives, in other words, the back
end.

[gsoc-timeline]: https://developers.google.com/open-source/gsoc/timeline#june_13
[gsoc-project]:  https://summerofcode.withgoogle.com/programs/2022/projects/RE49fQ8O
[lore]:          https://lore.kernel.org
[kw]:            https://github.com/kworkflow/kworkflow/
[kw-board]:      https://github.com/kworkflow/kworkflow/projects/7
[kw-milestone]:  https://github.com/kworkflow/kworkflow/milestone/8

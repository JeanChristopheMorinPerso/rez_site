---
title: "About Rez"
linkTitle: About
date: 2019-10-20T13:28:57-04:00
menu:
  main:
    weight: 1
---

## Overview

Rez is a cross-platform package manager with a difference. Using Rez you can create standalone environments configured for a given set of packages. However, unlike many other package managers, packages are not installed into these standalone environments. Instead, all package versions are installed into a central repository, and standalone environments reference these existing packages. This means that configured environments are lightweight, and very fast to create, often taking just a few seconds to configure despite containing hundreds of packages.

## What is Rez?

Rez is a cross-platform package manager with a difference. Using Rez you can create
standalone environments configured for a given set of packages. However, unlike many
other package managers, packages are not installed into these standalone environments.
Instead, all package versions are installed into a central repository, and standalone
environments reference these existing packages. This means that configured environments
are lightweight, and very fast to create, often taking just a few seconds to configure
despite containing hundreds of packages.

See [the wiki](https://github.com/nerdvegas/rez/wiki) for full documentation.

<p align="center">
<a href="https://github.com/nerdvegas/rez/wiki/media/other_pkg_mgr.png">
<img src="https://github.com/nerdvegas/rez/wiki/media/other_pkg_mgr.png"></a>
<br><i>Typical package managers install packages into an environment</i>
</p>

<br>
<p align="center">
<a href="https://github.com/nerdvegas/rez/wiki/media/rez_pkg_mgr.png">
<img src="https://github.com/nerdvegas/rez/wiki/media/rez_pkg_mgr.png"></a>
<br><i>Rez installs packages once, and configures environments dynamically</i>
</p>

<br>
Rez takes a list of package requests, and constructs the target environment, resolving
all the necessary package dependencies. Any type of software package is supported -
compiled, python, applications and libraries.


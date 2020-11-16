---
title: Github structure
author: OST
date: 2017-08-30
index: 1
banner:
  image: coding.jpg
category: Resources
---

#### All GfKs open source projects are hosted on GitHub under the GfK organization. We have a number of guidelines for how to use GitHub and what the different organizations are used for.

### Summary

* We have clear ownership - one project - one team
* We review all code and encourage Git-Flow
* Projects can have contributors from outside GfK

---

## Organizations

There is 1 primary organization which acts as the central source for GfK open source projects.

* [GfK](https://github.com/GfKSE)


## Joining GfK on GitHub

For all GfK employees the process is simple: Just reach out to oss@gfk.com to be added
to the GfK Github organization.

## Organization permissions

* Members cannot create, un-publish, delete or rename repositories
* The default access to all repositories for members is read-access
* Project maintainers have write access to the project they maintain
* External collaborators cannot have write access to the master branch

## Repository requirements

* Master branch is protected
* All pull requests must be reviewed by at least 2 [CODEOWNERS](https://help.github.com/articles/about-codeowners/)
* We recommend having Signed commits as per the [DCO](https://developercertificate.org/)

## Project ownership

Each published project have a dedicated team of maintainers. The maintainer team have write access to the repository and are the direct owners of the project. Everyone who is not an active maintainer are free to open a pull request which must be reviewed by at least 2 of the maintainers listed in the Codeowners file.

## External collaborators

All projects can have external contributors, maintainers are free to invite contributors from outside of GfK to join as an external contributor. This is a matter of judgment by the individual project team.

## Employees leaving GfK

GfK employees leaving GfK will be converted to external contributors. External Contributors cannot be a Codeowner, and can therefore not accept and merge pull requests, but can still comment on code as part of reviews.

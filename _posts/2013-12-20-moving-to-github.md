---
layout: post

title: Moving to Github
subtitle: "Tooling up and moving on."
cover_image: dino-run-se-9688.png

excerpt: "Over Christmas we will be moving all projects over to GitHub.com so I thought it would be a good idea to give you a basic introduction to the platform, and what it will mean to your current working processes."

author:
  name: Darren Royle
  twitter: royletron
  bio: Platform Manager
  image: dr.png
---

**Over Christmas** we will be moving all projects over to GitHub.com so I thought it would be a good idea to give you a basic introduction to the platform, and what it will mean to your current working processes.

###Github vs Git

One massive concept to get to grips with straight away is that there are two terms that are commonly interchanged, and often used incorrectly. That is the source control technology **Git** and the repository hosting service **GitHub**. So lets break these down:

**Git** is an application that allows users to track changes with their source files. It was developed by the **Linux** team as a way to manage their huge codebase, and has recently grown in popularity and has quickly become the source control software of choice for most developers. It is very similar to **Subversion**, which is what we currently use for source control, and works on a system of having a central *remote* version of all of your files (usually on an external server) which you then *pull* a copy of onto your machine. As you change the files, you issue *commits* which track all of the changes you have done on the files since your last *commit*, you then *push* your *commit* to the *remote* version and subsequent users will be told to *pull* the *remote* version again (receiving your changes) before they are able to *commit* their changes. If changes conflict, for example if you have changed the same file as someone else at the same time, you will be expected to *merge* your *commit* to the current *remote* version. This usually means you just comparing both versions and modifying the file to reflect both sets of changes.

**GitHub** is a **Git** hosting service that will act as the *remote* version of our various repositories. On top of this it also provides lots of useful functionality around those repositories, including:

* Issue/ticket management
* Repository/project wiki's
* A web front end to repositories, so you can see the files via your browser
* Simple user management

###So What Do I Need To change?

**This breaks down** into two cases, but in both cases you will need to [create a GitHub account](https://github.com/), and provide the technical team with your username:

**Code contributors**: these are people that actually want to be able to modify content and *commit* to repositories. If you currently use *TortoiseSVN* you will need to swap to using the *GitHub for Windows* client, this is currently being added to OUPs safe application list, those that I am aware of will have this installed automatically (all editors are included on this list). You will then need to *clone* the various repositories that you will want access for. We are going to run a training session in the New Year with information about how to do this.

**Project managers/others**: these are people that want to involved with projects at a reporting, or monitoring level. This might include people that want to submit issues to projects or monitor issues as they go through the various stages of completion. This may also be people who want to be able to access wiki's or just generally track progress of projects. All that these people need to do is to let the technical team know which projects they want access to, and it may also be an idea to attend the training session (all users will be contacted about this shortly)

###Why Is This Better?

**Git** and **GitHub** really benefit the programmer mostly, but it also provides an interface between what the programmer is doing, and what the various stakeholders expect. The use of **GitHub** issue tracking will provide a simple way to raise queries with functionality, and even with roadmapping new functionality going forward. The wiki will provide us with a platform to communicate what a project is actually about, and give really detailled information where required. Once projects are ticking along on **GitHub** we are also able to use that as a publishing route to the projects target, for example pusing content from the repository to a staging environment for testing, or deploying an updated platform to the production server. Finally **Git**, which this is all built on, is an excellent piece of software for source control management. Not only providing piece of mind, but also providing functions for developing new functionality without effecting the main project, and subsequently merging those changes back into the main project when signed off.

**All in all** this will put the whole team in a much stronger and light footed position, allowing us to provide access to projects to the right people very simply, and ensuring that our code is kept safe.
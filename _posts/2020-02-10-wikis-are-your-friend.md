---
layout: post
title:  "Wikis are your friend"
date:   2020-02-10 19:00:00 +0000
description: "They will improve your life and the life of those working with you, or at least that's what I'm being led to believe."
categories: wiki
tags: wiki markdown
---
{% highlight markdown %}
[[_TOC_]] << this becomes a table of contents!

# Example Title
This is an example of Markdown!

## Example Subtitle
A list in markdown:
1. It's really
2. Simple

{% endhighlight %}
## What?
Wikis are your friend; they will improve your life and the life of those working with you, or at least that's what I'm being led to believe. Ultimately, it's this sentiment that has lead me in the direction of blog writing, that and a prompt to properly research and understand the technologies and solutions I'm developing, how can I blog about it if I don't understand it?

### What are wikis?

For those new to the term in this context - a wiki serves as a reference point for all team members, it should be editable by all members, well-structured, easy to access, and provide whoever is using it with the information they need without having to ask around the office/slack or dig through word documents. If done correctly it can improve team efficiency; it's a collection of the team's knowledge!

So strictly speaking, I'm lumping two things into this, actual wikis and Readmes. Basically, anything that will help both yourself and those around you to understand what's happening through the convenient medium of markdown 🙄. 

For simplicity, I'm defining the two like this:
* Wiki - Project/Team documentation, e.g. and overview of the team and technologies used
* Readme - Repository documentation, e.g. Build or contribution guidelines

I'm going to try and cover two main topics here: why you should be using wikis and how you can get others to use wikis (I'm working on this one now). So, to start... 

### Why use wikis? 

Because what's worse than documentation? Fragmented documentation! No one wants to be trawling through something like SharePoint trying to find the document you hope explains what you're looking at only to find that you're then directed to a totally different document (and so on)! 🤯 Wikis solve this, they're simple, connected, and accessible.

From personal experience, working in process automation, I see an awful lot of industry specific technical jargon and I can remember this being impenetrable when I first started. How did my company overcome this? A series of presentations and one-to-one talks with people that know. While this isn't a bad approach - it gave me a base from which to start - it isn't the full package. I was forever wondering what an OPC server is, how it relates to a DCS, what's a tag, and which 1000-page document tells me all this? 

So, how would a wiki help in this situation?

Ideally a wiki would've offered me an easily accessible reference for all the terms, and I would've quickly been able to answer any questions I felt awkward asking because I had already been told multiple times before. 

Taking a step back; wikis are there for everyone, from managers to developers, both old and new, to help them understand the project and more effectively work on it. A well-structured, and maintained, wiki will improve everyone's understanding of a project or industry domain. That's both existing members and any new members that may join later on in the process. No, it's not a replacement for inductions from experienced staff members, or regular personal interactions, but it does give everyone involved a reference and a little helping hand if they need it.

As an example, I'm going to use something many developers would've seen before: the [.Net Core documentation](https://docs.microsoft.com/en-gb/dotnet/core/). This is a good example of a wiki, it's clean, simple, and linked. Anyone accessing this can quickly retrieve the information they need.

### Encouraging others

So, how do you get others onboard? Well this is a process I'm currently perfecting.

A couple of other developers on my team and I have been trying to encourage the take-up of wikis for a little while now, though the same issue seems to be blocking us; people aren't understanding what a wiki is. Either they think it's too hard to write, they create a single monolithic page and don't see the benefit, or simply fallback to older methods because that's what they're used to. Which has led me here, though I haven't explained markdown or gone into too much implementation detail (this varies based on what you're using, e.g. Azure DevOps or GitHub), I'm hoping this will have sold the concept to people so they can investigate further.

Ultimately: explain the idea, show it working, and hopefully they'll come around.

### Some useful links

Finishing off with some useful links for those that want to take it further. I primarily use Azure DevOps so that's my focus!

* [Azure DevOps Wiki Help](https://docs.microsoft.com/en-us/azure/devops/project/wiki/about-readme-wiki?view=azure-devops)
* [Azure DevOps Markdown](https://docs.microsoft.com/en-us/azure/devops/project/wiki/markdown-guidance?view=azure-devops)
* [GitHub Wiki Help](https://guides.github.com/features/wikis/)
* [GitHub Markdown](https://guides.github.com/features/mastering-markdown/)
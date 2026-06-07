# GitHub as infrastructure for african startups
_How African startups can use GitHub beyond code: project management, documentation, public roadmaps, collaboration, transparency, deployment, and community building, ...all while keeping costs close to zero._

---
## Table of contents

- [Foreword](#foreword)
  
- Foundation
  - [Chapter 1: The story of GitHub](#chapter-1-the-story-of-github)
  - [Chapter 2: Open Source Culture](#chapter-2-open-source-culture)

- Tools
  - [Chapter 3: Managing Work and Teams on GitHub (GitHub Projects)](#chapter-3-managing-work-and-teams-on-github-github-projects)
  - [Chapter 4: Your Website, Directly from a Repository (GitHub Pages)](#chapter-4-your-website-directly-from-a-repository-github-pages)
  - [Chapter 5: The Employee Who Never Sleeps (GitHub Actions)](#chapter-5-the-employee-who-never-sleeps-github-actions)
  
- Application
  - [Chapter 6: Building Startups on GitHub](#chapter-6-building-startups-on-github)

- Risks and Recommendations
  - [Chapter 7: Risks and Considerations](#chapter-7-risks-and-considerations)
  - [Chapter 8: Recommendations for African Startups](#chapter-8-recommendations-for-african-startups) 

- Vision
  - [Chapter 9: The Future of Collaborative Infrastructure](#chapter-7-the-future-of-collaborative-infrastructure)
  
 - [Epilogue](#epilogue) 

---
## Foreword

This article is not about learning [GitHub](https://github.com).

It is about **seeing GitHub differently**.

For many teams, GitHub is just a place to store code. But for resource-constrained startups, it can become something much bigger: project management software, documentation platform, public roadmap, collaboration workspace, deployment platform, and community hub.

In ecosystems where every subscription matters, understanding how to leverage a single platform for multiple purposes can be a competitive advantage.

This is especially true for many African startups, which often have to build ambitious products with limited resources.

GitHub is not just a developer tool.

It can become infrastructure on its own.

---
## Chapter 1: The Story of GitHub

### 1.1 - The Night It All Began

In 2007, three developers shared the same observation: Git, the version control system created by [Linus Torvalds](https://www.linkedin.com/in/linustorvalds), was incredibly powerful, but far too difficult for most people to use.

[Tom Preston-Werner](https://www.linkedin.com/in/mojombo), [Chris Wanstrath](https://en.wikipedia.org/wiki/Chris_Wanstrath), and [PJ Hyett](https://x.com/pjhyett) imagined a web platform built around Git. A place where developers could host projects, collaborate more easily, and share their work with the world.

In 2008, GitHub was launched.

The beginnings were modest. Then open-source projects started arriving. [Ruby on Rails](https://rubyonrails.org/) joined the platform, followed by many other frameworks. Word of mouth did the rest.

Within a few years, GitHub had become the place where developers built together.

> Understanding ***Git is not GitHub***. Git helps you understand GitHub. But you do not need to master Git to benefit from GitHub in your professional life.

### 1.2 - The Bet on Social Coding

GitHub's real innovation was not purely technical.

Its founders understood something important: developers did not just want to write code. They wanted to showcase their work, receive feedback, learn from others, and build a reputation.

**GitHub borrowed several ideas from social networks**: public profiles, activity feeds, followers, stars, comments, and open contributions.

For the first time, technical collaboration became visible.

GitHub was no longer just a code hosting platform.

It became a social network for building things.

### 1.3 - The Microsoft acquisition and the controversy

In June 2018, [Microsoft](https://www.microsoft.com) announced the acquisition of GitHub for $7.5 billion. 

The community’s reaction was immediate and fierce. Thousands of developers announced they were moving to [GitLab](https://about.gitlab.com/) or [Bitbucket](https://www.atlassian.com/software/bitbucket). Some called it a betrayal; others saw it as the end of an era.

The fear was understandable. 

Microsoft had historically had a strained relationship with open source. Its CEO, [Steve Ballmer](https://www.linkedin.com/in/steve-ballmer-7087a8157), had once called [Linux](https://www.linux.org/) a “cancer.” Entrusting the world’s open-source platform to this giant seemed paradoxical.

But under [Satya Nadella](https://www.linkedin.com/in/satyanadella)’s leadership, Microsoft had changed. The platform continued to grow; GitHub Actions was launched, and Copilot arrived. The mass exodus never happened. 

The acquisition turned out, for the most part, to be beneficial for the platform.

---
## Chapter 2: Open Source Culture

### 2.1 - What Is Open Source, Really?

Open source is often defined as software whose source code is accessible to everyone. 

That is true, but it is an incomplete definition. Open source is, above all, a philosophy of collaboration, transparency, and knowledge sharing.

[Richard Stallman](https://stallman.org/), founder of the free software movement in the 1980s, framed the question in moral terms: 

***Is it ethical to keep secret the inner workings of a tool used by millions of people?**

For him, the answer was no. Code should be free just as speech is free.

The open-source movement of the 1990s, led notably by [Eric Raymond](https://fr.wikipedia.org/wiki/Eric_Raymond), took a more pragmatic approach: open code produces better software because more people can examine, improve, and adapt it.

### 2.2 - Licenses: The Rules of Sharing

Any creative work is, by default, protected by copyright. 

If someone publishes their code on GitHub without specifying a license, you are not legally permitted to use, modify, or redistribute it. It may seem counterintuitive, but that is the law. 
Open-source licenses are explicit permissions granted by the author. 

There are many of them, with varying levels of freedom and obligations: 
  - **MIT** and **BSD**: The most permissive. You can do whatever you want with the code, including commercializing it, provided you retain the original author’s attribution.
  - **Apache 2.0**: Similar to MIT, with additional protections regarding patents.
  - **GPL** (GNU General Public License): Known as “copyleft.” If you use GPL code in your project and distribute it, your project must also be released under the GPL. A rule designed to prevent companies from “privatizing” free software.
  - **Creative Commons**: Not for code, but for content (documentation, images, text). Widely used on GitHub for documentation projects.
  
    > Caution:
    >
    > Choosing an open-source license is an important decision with legal and commercial implications. If you are hesitating between MIT and GPL, note that MIT favors broad adoption (including commercial use), while GPL favors sharing in return.

### 2.3 - Why Companies Contribute to Open Source ?

A question often comes up: 

***why do companies like Google, Microsoft, Facebook, and Red Hat invest heavily in open-source projects? What’s in it for them?***

There are many reasons. 

First, **shared infrastructure**: if many companies rely on the same tool, it makes sense to pool maintenance costs. 

Second, **recruitment**: contributing to a popular project is the best signal a company can send to talented developers. 

Third, **influence**: those who contribute the most naturally have more influence over the project’s direction.

And sometimes, there is simply the belief that certain things should belong to everyone.

### 2.4 - The Tragedies of Open Source

Open source is not without its drawbacks. The entire industry’s reliance on projects maintained by a handful of unpaid volunteers is one of the major vulnerabilities of the software ecosystem.

In 2021, a critical security flaw was discovered in [Log4j](https://logging.apache.org/log4j/2.x/index.html), a Java library used in thousands of enterprise applications. It was maintained by a few volunteers in their spare time. The entire industry suddenly realized just how much it relied on the unpaid work of strangers.

Initiatives like **GitHub Sponsors** or **Open Collective** are attempting to address this problem by allowing users to financially support the projects they depend on. 
It’s a start, but there’s still a long way to go.

> “Millions of dollars in economic value rest on the work of people who do this because they find it interesting.”
> 
>   [Nadia Eghbal](https://techiesproject.com/nadia-eghbal/), author of Working in Public

---
## Chapter 3: Managing Work and Teams on GitHub (GitHub Projects)

**GitHub Projects** is a project management tool that is directly integrated into the platform. 
At its core are Issues and Projects:

  - **Issues**: Start every task or bug as an issue. An issue can describe a feature request or a problem, and team members can comment, assign, tag with labels, and even attach files.
Issues centralize all discussion about a task. You can also break issues into smaller sub-issues to manage complex work hierarchies.

  - **Projects**: Think of Projects as kanban boards or tables that visualize your issues. GitHub Projects lets you organize issues and pull requests into customizable boards or roadmaps.
For example, you can create columns like “***To Do***”, “***In Progress***”, and “***Done***” and drag issues between them as work progresses.
Because Projects is built into GitHub, each board card links directly to the underlying issue (and the code or pull request that addresses it).

GitHub’s documentation highlights this integration: ***“Create issues, break them into sub-issues, track progress, add custom fields, and have conversations. Visualize large projects as tables, boards, or roadmaps, and automate everything with code.”***. 

In practice, this means **no disconnect between planning and execution**: if you track a task in a GitHub board, team members see its description, comments, and
associated commits/PRs all in one place. 

Every project remains linked to its code and documentation. Project columns can even be automated.

---
## Chapter 4: Your Website, Directly from a Repository (GitHub Pages)

***Is it possible to host a website for free, for life, in just a few clicks, while still getting an HTTPS certificate, fast loading speeds, and a reliable infrastructure?***

Yes. With **GitHub Pages**.

I know, this isn’t exactly news. 
And there are other options out there.

For example, [Render](https://render.com/) offers an attractive free plan, but applications can go into sleep mode after a period of inactivity. As a result, the first visitor may sometimes have to wait several dozen seconds before the site restarts.

There’s also [Vercel](https://vercel.com/), which is more advanced and particularly popular for modern applications. But today, let’s keep it simple.

With GitHub Pages, **a repository becomes a website** (no separate web host required).

You push your code to GitHub. GitHub builds your site and publishes it automatically. No server to configure. No SSL certificate to install. HTTPS is enabled by default.

Your site is then distributed through GitHub’s infrastructure, making it quickly accessible from virtually anywhere in the world.

**But there’s a trade-off.**

GitHub Pages is designed for static sites: HTML, CSS, and JavaScript. No backend, no database, no server-side APIs.

> Up to 1 GB per repository and 100 MB per file.

It’s perfect for:

- a portfolio;
- documentation;
- a landing page;
- a static blog.

However, the repository must be public with the free plan, which means the source code is visible to everyone. It’s also possible to publish from a private repository with GitHub’s paid plans, which remain relatively affordable for individuals and small teams.

---
## Chapter 5: The Employee Who Never Sleeps (GitHub Actions)

### 5.1 - What Is GitHub Actions?

A repository is no longer just a container for information. It becomes a system capable of reacting, making decisions, and performing work automatically.

Every time something happens inside a repository, a commit is pushed, a pull request is opened, a release is published, or even a specific time of day is reached;
GitHub can automatically execute a series of predefined tasks. 

These automated workflows are called **GitHub Actions**.

Imagine a team member whose only job is to watch your repository twenty-four hours a day.

When you push code, it immediately checks whether everything still works. When a release is published, it packages the project and deploys it. When documentation changes, it updates the website. When a scheduled date arrives, it launches a task without anyone touching a keyboard.

This is not artificial intelligence.

It is automation.

And although the idea sounds simple, the impact is enormous.

Before GitHub Actions, many of these tasks were performed manually. Developers had to remember to run tests, publish updates, generate reports, or deploy applications. The larger the project became, the greater the risk of human error.

GitHub Actions turns these repetitive tasks into repeatable systems. Once configured, the same process can run hundreds or thousands of times with the exact same behavior. GitHub itself describes Actions as a way to automate, customize, and execute workflows directly inside a repository.

In other words, a repository stops being passive.

It starts working for you.

### 5.4 - Beyond Software

One of the biggest misconceptions about GitHub Actions is that it is only useful for software development.

Yes, developers use it to run tests, build applications, and deploy code automatically. But GitHub Actions is not really about software.

It is about automating work.

**Any work.**

Consider a book written on GitHub.

Every time a chapter is updated, GitHub Actions can generate a PDF version, publish an online edition, verify that links are still valid, and even build a complete website for readers. The author writes. The repository handles the publishing process.

Or imagine a research project.

A workflow can collect data from public sources every morning, update datasets, generate charts, and publish a report automatically. Nobody has to repeat the same steps every day.

Communities use GitHub Actions to update documentation sites, create weekly newsletters, welcome new contributors, label discussions, and maintain knowledge bases.

Content creators use it to publish websites, optimize images, generate RSS feeds, and synchronize content across multiple platforms.

Students use it to maintain portfolios and publish projects automatically through GitHub Pages.

Even monitoring tasks can be automated. GitHub Actions supports scheduled workflows, allowing repositories to execute tasks at predefined intervals without human intervention. A repository can check whether a website is online, track changes in a public dataset, or generate periodic reports automatically.

This is where GitHub begins to look less like a code hosting platform and more like a digital workforce.

A repository stores information.

GitHub Pages distributes information.

GitHub Actions transforms information into action.

That distinction is important.

Because the real value of automation is not writing less code.

It is spending less time on repetitive work and more time on creating things that matter.

---
## Chapter 6: Building Startups on GitHub

***In this chapter, I'll use [ES_](https://www.linkedin.com/company/evolvesmarter/) as a real-world example to demonstrate how GitHub can serve as the operational backbone of a project or an early-stage startup.***

Rather than discussing theoretical use cases, we'll look at practical examples inspired by the way ES_ is structured and operated.

> The goal is not to suggest that every startup should run exactly the same way.
>
> The goal is to show how far a small team can go with a tool that most people still think is only for developers.

---
_To be continued..._

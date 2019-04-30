---
title: Develop
nav: true
---

# Collaborative Development + OER

- collaborative development 
- localized custom copy
- personal copy 

## GitHub <span class="fab fa-github"></span>

[GitHub](https://github.com/) is a cloud [Git](https://git-scm.com/) repository hosting service, with benefits!
It provides a handy web interface for managing, editing, and collaborating on remote Git repositories.
Originally designed to manage large open-source software projects, its use has expanded to many other types of organizations and individuals, with over 20 million users.
Accounts are free for public repositories--private repositories are available on a subscription pricing model.

Features: 

- Version control (permanently stores the history of your project)
- Friendly web platform (lowers barriers to contributors)
- Project management features (organize collaboration!)
- Large open source community (increases visibility and leverage outside contributors)

Hosting your source code on GitHub makes it easier to write, access, share, and reuse OER, ensuring the content is provided in a truly [open](https://opendefinition.org/) manner.

However, one amazingly useful GitHub feature is [GitHub Pages](https://guides.github.com/features/pages/), a free service that provides static web hosting from any repository.
Using GH-Pages removes infrastructure and cost barriers, making it a great option for teaching and learning because your web presentation and source code will be openly available from the same platform.

{% capture text %}Note:
GH-pages is intended to host relatively simple sites for your GitHub portfolio, project, or documentation.
There are *soft* limits and guidelines for gh-pages usage: sites should be < 1GB, use < 100GB bandwidth per month, and make < 10 builds per hour.
If your site exceeds these quotas, GitHub will send you a notice asking you to modify the repository.
All content must follow the [community guidelines](https://help.github.com/articles/github-community-guidelines/), e.g. no violence, obscene sex, or illegal stuff.{% endcapture %}
{% include alert.md text=text color=secondary %}

## Collaborative Workflow 

To make a website like this one (or like many of the [examples]({{ '/content/3-examples.html' | relative_url }})), the basic steps are:

{% capture text %}
1. Have a [GitHub](https://github.com) account.
2. *Optional:* have [Git](https://git-scm.com/), [Jekyll](https://jekyllrb.com/), and a nice [text editor](https://code.visualstudio.com/) installed.
3. [Import](https://help.github.com/articles/importing-a-repository-with-github-importer/) or Fork a Jekyll theme or template (such as [workshop-template](https://github.com/evanwill/workshop-template)) on GitHub.
4. Work on the GitHub web interface to edit files, or `clone` to your local machine.
5. Edit the site configuration `_config.yml` with your info.
6. Edit the content pages in markdown.
7. Add images to the "images" folder.
8. Push to GitHub (or commit on the web interface).
9. In your repo's settings, activate gh-pages, using master branch.{% endcapture %}
{% include card.md header="GH-Pages Overview" text=text %}

For a full introduction to the basics, check my [go-go gh-pages](https://evanwill.github.io/go-go-ghpages/) workshop.

{% include alert.md text="GitHub is not the only option! There are alternative hosts that offer the similar services, such as [Gitlab](https://about.gitlab.com/gitlab-com/), or you could manage your own simple static web hosting. This workshop focuses on GitHub because it is the largest community and features the easiest to use web interface." color="success" %}

## Why Open?

Open Educational Resources (OER) are *not just a free download*!

{% capture text %}<blockquote class="blockquote">
<p>Open Educational Resources are teaching, learning and research materials in any medium – digital or otherwise – that reside in the public domain or have been released under an open license that permits no-cost access, use, adaptation and redistribution by others with no or limited restrictions.</p>
<div class="blockquote-footer text-right">The William and Flora Hewlett Foundation, <cite title="Source Title"><a href="https://hewlett.org/strategy/open-educational-resources/" target="_blank">OER Defined</a></cite></div>
</blockquote>{% endcapture %}
{% include card.md text=text %}

OER are materials that are free to access and use--but are also licensed to be modified, adapted, re-mixed, and re-used in new ways. 
<span class="fas fa-lock-open"></span> *Open* is the key word (see the [Open Definition](https://opendefinition.org/)).
This is the feature that makes OERs so powerful for teaching and learning--they reduce costs for students, but also enable innovation, providing instructors the freedom to flexibly adapt and enrich the learning experience.

When using open licenses such as [Creative Commons](https://creativecommons.org/) <span class="fab fa-creative-commons"></span>, the author does NOT give up their copyright <span class="far fa-copyright"></span>. 
However, they grant everyone specific **permissions** to use the materials--freedoms!
These are summarized by David Wiley in the [Open Content Definition](http://opencontent.org/definition/) as the "5R permissions":

{% capture rs %}1. **Retain** – the right to make, own, and control copies of the content (e.g. download, duplicate, store, and manage)
2. **Reuse** – the right to use the content in a wide range of ways (e.g. in a class, in a study group, on a website, in a video)
3. **Revise** – the right to adapt, adjust, modify, or alter the content itself (e.g. translate the content into another language)
4. **Remix** – the right to combine the original or revised content with other material to create something new (e.g. incorporate the content into a mashup)
5. **Redistribute** – the right to share copies of the original content, your revisions, or your remixes with others (e.g. give a copy of the content to a friend)

{% include alert.md text="Licenses can also contain *requirements* (e.g. CC-BY-SA, must share with the same license) or *restrictions* (e.g. CC-BY-NC, no commercial use) that must be followed to granted the permissions. Remember, OER are more *open* if you choose simple licenses and open, easy to use formats!" %}
{% endcapture %}
{% include card.md text=rs header="5R Permissions" %}

Enjoying the freedoms of open content instructors can:

- Improve, update, or modify to ensure the most relevant content.
- Reformat to create new derivatives appropriate for different means of consuming content such as video, audio, or websites.
- Adapt to the specific context, enabling learning materials to be responsive to your course, students needs, and pedagogy.

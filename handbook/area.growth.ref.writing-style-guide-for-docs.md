---
id: JG8aRMn9RkKtQAaMmkh7p
title: Writing Style Guide for Docs
desc: ''
updated: 1646946735336
created: 1639612388568
---

## Summary
#stage.seed: this guide is a work in progress

Writing style guide at Dendron when writing documentation, we use the classification set forth in [the four types of documentation](https://documentation.divio.com/).

### Examples
- tutorial: https://docs.djangoproject.com/en/4.0/intro/tutorial01/
    - eg. 
        - `tutorial.*`
        - blog tutorials
- reference: aws docs
    - eg. 
        - `topic.lookup`
        - `ref.commands`
        - `topic.*.quickstart`
- howto: stack overflow
    - eg 
        - `guides.*`
        - `*.cook`
- explanation: http://aosabook.org/en/index.html
    - eg:
        - blog explanations
        - `pkg.*.arch` 

## Principles

### get to the point
- alias: most important/relevant thing first

### less is more

information overload is a thing, lets try to not add more information than we need to

- avoid fluff: less adjectives and get to the meat
- don't repeat yourself (DRY)
- [[prefer being terse|dendron://private/area.growth.ref.writing-style-guide#prefer-being-terse]]

### provide context
- don't presume use case

- eg:
    - https://github.com/dendronhq/dendron-site/pull/341#discussion_r776514497

### structured docs

- use repeating structures 
- be consistent


- bad, https://github.com/dendronhq/dendron-site/pull/341#discussion_r776514405
```
#### 5MJ Schema Contents

We are going to use [[Inline Schema|dendron://dendron.dendron-site/dendron.topic.schema#inline-schema-anatomy]]. Replace the content of `5mj.schema.yml` with the following:

```


- good
```
### Update 5MJ Schema Contents

Replace the content of `5mj.schema.yml` with the following:
...

You just created an [[inline schema]]. {one sentence description of inline schema}
```


- eg: 
    - see [[templates.topic]]
    - https://github.com/dendronhq/dendron-site/pull/341#discussion_r776446911
    - https://github.com/dendronhq/dendron-site/pull/341#discussion_r776515268

### be specific

- bad
> Dendron supports an extended Markdown syntax, which provides a lot of options for rich formatting. 

- good
> Dendron extends regular markdown with additional syntax. This covers everything in github flavored markdown as well as additional features that are unique to Dendron.

## Style

### prefer present tense
- eg:
    - https://github.com/dendronhq/dendron-site/pull/341#discussion_r776448643

### prefer being terse
- eg:
    - https://github.com/dendronhq/dendron-site/pull/341#discussion_r776449322


- bad
> Keep in mind: templates can be used with or without schemas automatically applying them.

- good
> Keep in mind: templates can be used with or without schemas.

### provide context
- provide full length definitions before using abbreviations

## Lookup

- [Part 1: Create and Deploy Your First Gatsby Site](https://www.gatsbyjs.com/docs/tutorial/part-1/)
- [Getting Started | Next.js](https://nextjs.org/docs/getting-started)
- [Getting Started | Create React App](https://create-react-app.dev/docs/getting-started/)
- [Writing your first Django app, part 1 | Django documentation | Django](https://docs.djangoproject.com/en/4.0/intro/tutorial01/)
- [Prebuilt subscription page with Stripe Checkout](https://stripe.com/docs/billing/quickstart#congratulations!)

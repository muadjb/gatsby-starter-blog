---
title: Gatsby Typescript
date: '2019-07-18T23:46:37.121Z'
---

I need to put together a portfolio site for some of my job applications. Also, I've had the idea to make a personal blog for over a year. I started Gatsby last year but stopped for some reason. I played around with Hakyll and thought it could be a nice way to learn something practical, but it's too niche and Gatsby helps me learn React and GraphQL which interest me and can be used in my career. So, back to Gatsby!

I found a long Gatsby [youtube video](https://www.youtube.com/watch?v=8t0vNu2fCCM) by [Andrew Mead](https://www.youtube.com/channel/UCScXYvmDD7hyFVX6X5ZwE_Q) that I'm gonig to work through today.

I want to use Typescript of course. I searched for a starter, but I like the step by step instructions I found by [Arden de Raaij](https://dev.to/ardennl/setting-up-a-gatsbyjs-starter-with-typescript-eslint-prettier-and-pre-commit-hooks-2ebg) better. This post will be my notes as I work through his instructions.

I researched a bit more and discovered that while tslint will be deprecated in favor of eslint, the actual transition not imminent. So I'm installing tslint and codelyzer instead. I copied a tslint.json from the AMS Angular project.

Whoa!!! It works!

I added two simple test pages using a .tsx extension. I can change them and the files are compiled and hot reloaded with the dev server. Cool!

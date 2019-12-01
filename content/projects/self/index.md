---
title: "this / self / danielschlomer.com"
date: 2019-12-01
---
I created this website so I could showcase and write about my work. Right now “work” means projects I work on in my free time,  but that might change in the future. I don’t see this site becoming much more than a project portfolio, so I decided early on that a simple static site would fit my needs.

I evaluated a few options for building a static site but I ended up choosing the static site generator [Hugo](https://gohugo.io/). I wish I had an insightful reason for choosing Hugo. The documentation on Hugo’s site was good and deployments seemed easy based on my quick research. Beyond those two things I didn’t really care what technology I used. Hugo is popular so it seemed like a good choice.

![Hugo Logo](hugo-logo-wide.svg)

Hugo is written in Go, which means it’s very fast. Generating new sites with Hugo is almost instantaneous. My only time investment involved learning Hugo’s approach to organizing content. But even that doesn’t take much time. After choosing a theme and adding a new markdown file for content, you can have a new website up in seconds. Writing Go code isn’t necessary either.

For a theme I chose Luiz F. A. de Prá’s [Coder theme](https://themes.gohugo.io/hugo-coder/). I made a few tweaks to the theme by adding my own css, but for the most part my site’s aesthetics come from his theme. I might change the theme or make my own down the road, but for now I want something simple and quick. There’s no need to spend a bunch of time styling my website if I don’t even have any posts. I can make things prettier after I have something to make pretty.

For hosting I chose AWS because, again, it’s popular. AWS has a product called the [AWS Amplify Console](https://aws.amazon.com/amplify/) that provides a continuous deployment workflow for full-stack serverless web applications. It’s ideal for single page applications and static sites. Pointing Amplify to my Git repo allowed me to set up a continuous deployment workflow in only a few clicks. Now my website automatically builds and deploys on every commit. Amplify made all of this setup incredibly easy. The [tutorial](https://gohugo.io/hosting-and-deployment/hosting-on-aws-amplify/) for this on Hugo’s website is only 4 steps. I think there’s something to be said about brevity.

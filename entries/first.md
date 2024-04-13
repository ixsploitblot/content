# Building a blog 

###  Why would one build a blog from scratch?

The problem I often had when writing a blog was that I never found a software that I really liked. They were either too complex and I didn't want to learn a blog software or offered too little control and felt to restrictive. 

When switching software I also often didn't bother too move old arcticles, as I am just writing for myself.

Another option would have been to use a publishing platform (like medium), but:
- I never found one I liked
- I don't want too be too dependent a hosting provider

### Technology decisions

The blog is written in Rust. I was always found of low level languages (due to my reverse engineering hobby) but Rust also offers many high level abstractions.

At the moment I simply host on cloudflare workers. They offer a free tier for workers of 1MB size and 100.000 requests per day.

Writing articles is done in markdown. I keep my personal notes in obsidian, so that's a very natural choice.
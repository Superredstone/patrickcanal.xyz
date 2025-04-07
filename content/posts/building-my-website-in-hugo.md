+++
date = '2025-04-07T19:16:28+02:00'
title = 'Building my website in Hugo'
tags = [ 'website', 'hosting' ]
+++

I always wanted a website/blog to write articles about what I like, so today I decided to make one! 

After buying a domain and setting up the server I had just to decide what to write the website with.

## Hugo
![hugo-logo](https://gohugo.io/images/hugo-logo-wide.svg)

As a tech stack I wanted something simple and easy to mantain, 
[Hugo](https://gohugo.io/) makes everything so easy and painless that it is too good to be true. 

Just install it and then write in the terminal
```bash 
hugo new site <website-name> && cd <website-name>
``` 
to generate the template, install a good-looking theme from the [themes page](https://themes.gohugo.io/themes/) on the Hugo website, in my case Ficurinia
```bash
git clone https://github.com/patrickacciaioli/ficurinia themes/ficurinia
```
add the following line inside of `hugo.toml` with the greatest editor ever lived (Vim)
```toml
theme = "ficurinia"
```
Start the server with
```bash
hugo server 
```
and you are ready to go. A complete blog in seconds.

## Conclusion
Building a personal website with Hugo was faster and easier than I could have ever done in plain HTML. With minimal setup and maximum flexibility, Hugo proved to be the perfect choice for my blog. Now, I can focus on writing posts worrying about the infamous [Hypertext Markup Language](https://en.wikipedia.org/wiki/HTML).

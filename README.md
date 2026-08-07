# web - Source code for ariadnavigo.com

This is the source code for my [website](https://ariadnavigo.com), developed
using Hugo and the [not-much](https://github.com/imgios/not-much) theme.

If you're using my website as a template, be aware that it also uses
[hugomods/images](https://github.com/hugomods/images) for one single image, so
Go will be a hard dependency to make it work.

## Why?

Why publishing this code, if my website is strictly personal? Mainly because the
way I learned how to write a website with Hugo was by reading other people's
code. So, I wanted to give back; Hugo is a great tool, but sometimes you need to
know its ins-and-outs.

## How?

As I've been learning more about open source development, I've been also
learning about how public repos are meant to be maintained, how commits should
be written (e.g. [Conventional Commits][conv-com]), why public pull requests to
your own main branch are a good idea (it helps documenting changes), etc. If you
take a look at my other repos, you'll see that those have gone through messy
development practices.

However this is a website/blog, so the most important of what is going on here
happens privately and locally on my system first, namely my writings. I do
extensively use local branches and many local commits to organize my writing,
but that process is ugly and intimate, so I won't be pushing those commits on
GitHub unless I wanted to share something as a "public draft". In the vast
majority of cases, I'll be merging a rebased commit for the final text and only
do public commits for changes _after_ the text was published (e.g., typos,
updates, or even removing a post from the site, etc.).

On the other hand, _development_ of the website follows the usual workflow for
any code project on GitHub.

## License

The full copyright and licensing terms for this website can be found in the
LICENSE file.

However, the gist of it is that _content_ is **not** licensed (text and images),
but the rest of the repo is MIT (namely the code and whatever tools might be
added to build or deploy the site).

[conv-com]: https://www.conventionalcommits.org/en/v1.0.0/

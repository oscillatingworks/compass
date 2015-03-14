go-metainspector
================
[![](https://img.shields.io/badge/oscillating-works-green.svg?style=flat)](https://github.com/oscillatingworks/compass#phases)

We are taking `go-metainspector` as our first in-house project.

Author
------
Fernando Alvarez

https://github.com/fern4lvarez

info@fer.ac

Link
----
https://github.com/fern4lvarez/go-metainspector

http://metainspector.dotcloudapp.com/

Category
--------
Web Tools

Language
--------
Go

Description
-----------
Simple web metadata scraping in Go. `go-metainspector` is a web scraper package that
provides access to basic info and meta tags of a given URL. It is inspired by the
`metainspector` gem by Jaime Iniesta and completely written in Go.

:thumbsup:
----------
- It's an in-house project, so we don't need to deal with external authors and use it
  for experimenting with new open source conventions or common practices.
- It's small and easy to maintain, requires not so many documentation.
- It got relatively important interest from the community (35 starts, 9 forks).
- It's not only a Go package, but a command line tool than can be distributed in all
  architectures, i.e. it can be user by everyone, not only Go devs.
- Big room for improvements.
- It's fast.

:thumbsdown:
------------
- It's a port from another existing tool, i.e. it's not original or unique.
- The name, with the `go-` prefix, is not cool.
- Some of its dependencies are outdated, requires work to put everything
  up-to-date.

Further comments
----------------
I was hesitating whether I should submit some of my projects to our oscillating
selection. I have few of them, but I wasn't really sure they would match our requirements.
Then I remembered that `go-metainspector` surprisingly still gets attention, I see people
starring it from time to time and even seeing how some forks got new commits. So
maybe after all it could be adopted as one of our in-house projects.

I actually have ideas to make it more interesting for everyone to use it - there's a long
TODO list, but specially the command line tool needs to be improved, turning it
into a proper UNIX command line tool that everyone can use to fetch metadata super
fast (something that would make it special compared to the original project), and make it
play together with other UNIX tools. I was thinking on renaming it to `mi` and moving
the repo to the oscillatingworks account, so it looks more official.

Also, we can use this project as a test for many of the stuff we want to do in bigger
projects: binaries distribution, native packaging (apt, brew, rpm, etc.), CHANGELOG maintenance,
use of open source services/badges, or play with project/doc site on Github pages. -
[@fern4lvarez](https://github.com/fern4lvarez)

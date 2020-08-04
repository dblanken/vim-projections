# vim-projections

## Description

Vim-projections is a configuration file repository for projection configuration
files used by different frameworks and languages.  It was created as a way to
have a sane default when starting a new project without having to create your
own or find the location of the last projections file you had in a different
project.

## Why

This spawned from a commit message that I can't seem to find now by tpope
regarding a completely different thread.  In it, he explained that the solution
to it would require separating the projectionist specific parts out of
rails.vim, which would be tedious.  I decided to look at the rails.vim source
and extract what I could out of it into a projectionist file to use as a way to
possibly not need rails.vim.

Short answer, I needed rails.vim, but I was able to extract a "good enough"
projection file that could be used.

I then began looking at vue code, and really missed something like Esource.  So
I attempted to write a new projections file.  I am by no means an experienced
Vue developer, so I have no idea what the starting point of a vue project would
be except by looking at the structure.  I thought it would be nice if I could
go to a repo to get the projections file for that file as a base so I could
then focus on the application or project than how my editor is working on the
app/project.

## Contributions

You are free to make pull requests adding new projections.  I ask that these
be what would be considered default behavior in the framework/language.  As an
example, I'd like to see a framework that stores its source files in /src and
tests in /tests to have a mapping that reflects this.

Modifications are also allowed, however, since I am not experienced in every
language/framework, it may be up to the collective to decide if the change
needs to happen to a file.

svn-explorer
========
Browse the SVN repository as you use the shell! Requires Ruby 2.3+

```console
$ bundle
Install dependencies...

$ bundle exec svn-explorer https://svn.example.com/repo/

https://svn.example.com/repo/$ ls
project1/       project2/       project3/

https://svn.example.com/repo/$ cd project1/
https://svn.example.com/repo/project1/$ ls
contrib/        LICENSE         README.md       src/
```

### Features
- Easy repository navigation.
- Tab completion.
- Shell-like user experience.

<br>

--------

*svn-explorer* is primarily distributed under the terms of the [GNU General
Public License v3.0](LICENSE) or any later version.

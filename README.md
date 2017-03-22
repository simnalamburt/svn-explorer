svn-explorer
========
Requires Ruby 2.3+

```bash
# Install dependencies
bundle

# Explore the SVN repository!
bundle exec svn-explorer https://svn.example.com/repo/
```

```console
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

# [Life Changing Labs](http://www.lifechanginglabs.com/)

<!-- [![Build Status](https://travis-ci.org/quilljs/quill.svg?branch=master)](http://travis-ci.org/quilljs/quill) [![Dependency Status](https://gemnasium.com/quilljs/quill.png)](https://gemnasium.com/quilljs/quill) -->

The LCL website is hosted on [Github Pages](https://pages.github.com/) and therefore supports [Jekyll](http://jekyllrb.com/). Please read the corresponding documentations for usage specific to either. This website was created by [Lillian Chen](http://lillian-chen.com/) and should not be used or altered without appropriate permissions.

## Editing
Before attempting to edit general text information, please note the following.

### YAML Data
All data are loaded from [YAML](http://www.yaml.org/spec/1.2/spec.html) files in the `_data` directory. Right now, the following "databases" are in usage:

- Companies - `/companies`
- Guests - `/network`
- Members - `/network`
- Partners - `/network`

Properties in these data files are accessed via `site.data`.

### Blog
The blog is managed by Jekyll's native "blog aware" functionality in the `_posts` directory. 

When creating new posts, you *must* follow the Jekyll convention for naming post files. All posts are written in Markdown with the following front matter: `title, author, categories, layout`.
ITcase Sphinx Theme
===================

It's copy of pylons_sphinx_theme

This repository contains ITCase themes for ITCase related projects.
To use a theme in your Sphinx documentation, follow this guide:

1. put this directory as _themes into your docs folder.  Alternatively
   you can also use git submodules to check out the contents there
   or symlink this directory as _themes.

2. add this to your conf.py::

    sys.path.append(os.path.abspath('_themes'))
    html_theme_path = ['_themes']
    html_theme = 'itcase'

3. (optional) set a canonical root url in conf.py::

   html_theme_options = dict(
     canonical_url='http://the_root_domain/latest/docs/'
   )
   
The url points to the root of the documentation. Requires a trailing slash.

The following themes exist:

- **itcase** - the generic ITCase Project documentation theme
- **sacrud** - the specific SACRUD documentation theme

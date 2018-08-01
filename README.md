# Thales blog

To set up the blog you'll need to create a virtualenv and install:

```
pip install pelican markdown
```

Then you'll need to generate the content with

```
cd thales
pelican content
```

You can build content by running a tab with `pelican -r content`. The `-r` will update on changes to the filesystem. Then you just run a simple web server with:

```
cd thales/output
python -m http.server
```

This takes two tabs. You'll survive

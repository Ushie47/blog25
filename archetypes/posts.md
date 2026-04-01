+++
title   = '{{ replace .File.ContentBaseName "-" " " | title }}'
date    = '{{ .Date }}'
draft   = true

# Authors — leave blank to default to site params.author_name.
# For collaborations: authors = ["Alice Smith", "Bob Jones"]
authors = []

# Optional hero/caption image.
# Use a page bundle resource (place image next to index.md) or a root-relative path.
image         = ''
image_caption = ''

# Taxonomy
# tags       = ["hugo", "web"]
# categories = ["tutorial"]

# Related projects — list of project content paths relative to content/.
# e.g. related_projects = ["projects/my-project"]
# Omit if none — do NOT set to [] (empty taxonomy array issue).
# related_projects = ["projects/my-project"]
+++

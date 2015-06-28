# phototag
bash suite for image tagging and metadata-based search

## Requirements
- exiv2
- terminology (for photointer)

## Components

- phototag: core program, used to set, clear and query tags from images
- photointer: interactively (re)set tags using terminology to display images on terminal window
- photofind: search for images that have all (AND mode) or at least one (OR mode) specific tags
- tagstocomment: internal program used to convert input syntax to internal syntax

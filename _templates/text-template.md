---
# Don't touch this
layout: text

# Mandatory fields
title: # title of the text
type: # 'poetry' or 'story'
date: # format: YYYY-MM-DD

# Optional fields
description: # falls back to title if empty
author: # falls back to author name in site config if empty

# If published – remove block if not published
published:
  # Required when 'published' is present
  name: # title of publication
  publisher: # book publisher
  isbn: # 13-digit ISBN, digits only (no dashes)
  date: # format: YYYY-MM-DD
  info_text: # shown after the text, next to the 'published' icon
  url: # where to find the book
  link_label: # label for the link (e.g. "Verfügbar auf Amazon")

  # Optional fields
  editor: # book editor
  author: # book author

# If malika – remove block if not awarded
malika:
  # Required when 'malika' is present
  name: # name of the award
  info_text: # shown after the text, next to the 'malika' icon

# Deprecated fields (safe to ignore)
order: # obsolete – texts are sorted alphabetically
---

TEXT TEXT TEXT
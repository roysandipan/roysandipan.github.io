---
title: People
summary: team members
show_date: false
type: landing

# Page title
#title: My page
# Page type - we want a landing page (such as a homepage)
#type: landing

# Your landing page sections - add as many different content blocks as you like
sections:
  # A section to display blog posts
  - block: collection
    id: PhD Students
    content:
      title: Team Members
      #subtitle: A subtitle
      #text: Add any **markdown** formatted content here - text, images, videos, galleries - and even HTML code!
      # Display content from the `content/people/` folder
      filters:
        folders:
          - people
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      # Choose your content listing view - here we use the `showcase` view
      view: showcase
      # For the Showcase view, do you want to flip alternate rows?
      flip_alt_rows: false
---
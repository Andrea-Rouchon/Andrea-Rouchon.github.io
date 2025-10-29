---
title: 'Curriculum Vitae'
date: 2023-10-24
type: landing

design:
  spacing: '5rem'

# Note: `username` refers to the user's folder name in `content/authors/`

# Page sections
sections:
  - block: resume-experience
    content:
      username: admin
    design:
      # Hugo date format
      date_format: 'January 2006'
      # Education or Experience section first?
      is_education_first: false
  - block: resume-skills
    content:
      title: Skills & Hobbies
      username: admin
    design:
      show_skill_percentage: false
  - block: resume-awards
    content:
      title: Awards
      username: admin
  - block: resume-languages
    content:
      title: Languages
      username: admin
    design:
      background:
        color: ""
        gradient_start: "#fb923c" # warm orange
        gradient_end:   "#ef4444" # warm red
        text_color_light: true
        spacing:
          padding: ["6", "6", "6", "6"]
        columns: "1"
---
---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: markdown
    id: news 
    content: 
      title: 📣 News
      text: 
        - **18.12.2023** I gave my first ever contributed talk on my master's thesis "A Latent Causal Inference Framework for Ordinal Variables" at the [2023 IMS International Conference on Statistics and Data Science (ICSDS)](https://sites.google.com/view/icsds2023) in Lisbon.


  - block: contact
    id: contact
    content:
      title: Contact
      email: ms2985@cam.ac.uk
      address:
        street: Centre for Mathematical Sciences, Wilberforce Road
        city: Cambridge
        postcode: 'CB3 0WB'
        country: United Kingdom
        country_code: UK
      directions: Pavillion D – Room D0.04
      # Automatically link email and phone or display as text?
      autolink: true
    design:
      columns: '2'
---

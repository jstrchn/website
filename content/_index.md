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
  - block: skills
    content:
      title: Research Interests
      text: ''
      # Choose a user to display skills from (a folder name within `content/authors/`)
      username: admin
    design:
      columns: '1'
  - block: experience
    content:
      title: Experience
      # Date format for experience
      #   Refer to https://docs.hugoblox.com/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Postdoctoral Researcher
          company: Université Mohamed VI Polytechnique
          company_url: 'https://um6p.ma'
          company_logo: um6p
          location: Rabat, Morocco
          date_start: '2026-01-05'
          date_end: ''
          description: |2-
              Researcher on social learning and cultural evolution. In this role, I also teach the *Experimental Psychology: Design and Data Collection* 2nd year undergraduate module
        - title: Humboldt Research Fellow / Postdoc
          company: University Medical Center Hamburg-Eppendorf
          company_url: 'https://uke.de'
          company_logo: uke
          location: Hamburg, Germany
          date_start: '2023-03-01'
          date_end: '2025-11-30'
          description: |2-
              Recipient of a research grant for experienced researchers awarded by the Alexander von Humboldt Foundation to study kinematics of pedagogical actions during demonstration. I then transitioned to a postdoctoral position on the EU-funded [ASTOUND Project](https://astound-project.eu) researching the social competencies of AI and ways to integrate cognitive psychological methods and theory with the development of virtual agents

              [Lab webpage ](https://cmon-uke.github.io/website)
        - title: MINDED (MSCA-COFUND) Fellow
          company: Cognition, Motion, and Neuroscience Unit, Italian Institute of Technology
          company_url: 'https://www.iit.it/research/lines/cognition-motion-and-neuroscience'
          company_logo: iit
          location: Genoa, Italy
          date_start: '2020-07-01'
          date_end: '2022-12-31'
          description: |-
            Postdoctoral research fellowship investigating movement-to-movement variability of upper limb kinematics in teaching interactions
            
            [Institutional webpage (archived)](https://www.iit.it/it/people-details/-/people/james-strachan)
            
            [MINDED Project](https://minded-cofund.eu/people/minded-fellows)
        - title: Postdoctoral Researcher
          company: Social Mind and Body lab, Department of Cognitive Science, Central European University
          company_url: 'http://somby.ceu.edu/'
          company_logo: ceu
          location: Budapest, Hungary
          date_start: '2016-11-01'
          date_end: '2020-06-30'
          description: |-
            Postdoctoral researcher studying coordination and communication in joint action
            
            [Institutional webpage (archived)](https://somby.ceu.edu/james-strachan)
        - title: PhD Student
          company: Department of Psychology, University of York
          company_url: 'https://www.york.ac.uk/psychology'
          company_logo: uoy
          location: York, UK
          date_start: '2013-10-01'
          date_end: '2016-09-30'
          description: |-
            Supervised by Professor Steve Tipper on thesis titled, *Incidental learning of trust from identity-contingent gaze cues: boundaries, extensions and applications.*
            
            [Find the thesis in the university repository](https://etheses.whiterose.ac.uk/15774/)
    design:
      columns: '2'
  - block: collection
    id: publications
    content:
      title: Recent Publications
      text: |-
        {{% callout tip %}}
        [See list of collaborators](./collaborators).
        {{% /callout %}}
      filters:
        folders:
          - publication
    design:
      columns: '2'
      view: citation
  - block: portfolio
    id: projects
    content:
      title: Projects
      filters:
        folders:
          - project
      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
      default_button_index: 0
      # Filter toolbar (optional).
      # Add or remove as many filters (`filter_button` instances) as you like.
      # To show all items, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the toolbar, delete the entire `filter_button` block.
      
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: true
  - block: collection
    id: talks
    content:
      title: Recent & Upcoming Talks
      text: |-
        {{% callout tip %}}
        [See past presentations](./event/)
        {{% /callout %}}
      filters:
        folders:
          - event
        exclude_past: true
    design:
      columns: '2'
      view: compact
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: 
      email: james.wa.strachan@gmail.com
      address:
        street: Université Mohamed VI Polytechnique, Rocade Rabat-Salé
        city: Rabat
        region: 
        postcode: '11103'
        country: Morocco
        country_code: MA
      contact_links:
        - icon: bluesky
          icon_pack: fab
          name: '@jwastrachan.bsky.social'
          link: 'https://bsky.app/profile/jwastrachan.bsky.social'
    design:
      columns: '2'
---

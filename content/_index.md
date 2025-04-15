---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
      text: |
        <br>
        
        **Analogical Reasoning in Contemporary Physics** is a PRIN 2022 collaborative research project in **philosophy of science** between Politecnico di Milano and Università degli Studi di Urbino Carlo Bo
  
  - block: markdown
    content:
      title:
      subtitle: ''
      text:
    design:
      columns: '1'
      background:
        image: 
          filename: abstract.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen
   
  - block: markdown
    content:
      title: The Project
      text: "Analogy is an effective form of reasoning adopted in scientific practice. Indeed, hypotheses are often formulated by applying analogical inferences based on alleged similarities with previously successful cases. As a matter of fact, analogical thinking proves to be a powerful heuristic tool, both in the context of discovery and in the context of justification, or confirmation, of scientific hypotheses, especially in physics. Furthermore, thanks to the ability of making complicated concepts more accessible by drawing upon already familiar similar cases, it represents a useful pedagogical vehicle to transfer scientific knowledge both in school teaching and in the popularization of science. Yet, the conceptual and formal status of analogies remains an open problem in nowadays philosophy of science.
      

      The putative scheme for analogical inferences holds that, given two systems sharing a number of properties, one can infer that if the source system is known to possess an additional property, then the target system ought to possess a similar property as well. Nevertheless, this conclusion is not logically warranted. There thus arises an outstanding philosophical question: that is, how can we draw plausible analogies in science? Such a question becomes even more pressing in those domains of physics where we have limited empirical access to a target system, as it happens in the sub-atomic quantum world as well as in the large-scale structure of spacetime."

  - block: collection
    content:
      title: Latest Publications
      text: ""
      count: 5
      filters:
        folders:
          - publication
        publication_type: 'article'
    design:
      view: citation
      columns: '1'

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
---

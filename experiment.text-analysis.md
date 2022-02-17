---
id: 7_ug5qkhWRcPsYKaeMsG8
title: Text Analysis
desc: ''
updated: 1645076605442
created: 1624955696999
---

![](/assets/images/sample_dat_filtered.png)
<p>
<figcaption>
Excerpt from text analysis of <i>Gormenghast</i>.
</figcaption>
</p>

### Context

Standard introduction for any tasks involving text analysis of *[[Gormenghast|example.gormenghast]]*.

#### Objectives

- Provide tools and methods for "quantifying" the use of language related to [[place|relationship.place]] in *Gormenghast* with a focus on the relationships between:
  1. Phenomena such as [[color|relationship.color]], light, texture and atmosphere.
  2. Discrete geographical locations and their component parts, e.g. buildings and rooms, forests and trees, etc.
- Explore and discuss issues relevant to [[place|relationship.place]], [[design|relationship.design]] and [[communication|relationship.communication]] that emerge from attempts to create these tools, particularly those that emphasize the differences in [[subjectivity|relationship.subjectivity]] between species.
- Describe the difficulties inherent in attempting to "quantify" subjective phenomena such as atmosphere, mood and events from unstructured text.
  - Ambiguous/loosely-defined cultural phenomena such as [[place|relationship.place]] are amalgamations of different sources not limited to the impression created directly by language, e.g. collective/cultural memory such as awareness of other works, history, symbolic associations play a large part.


## Research Question
- Text analysis tools can automate the extraction of descriptive words about places in literary text(s)
## Methods

1. Select a text containing descriptive language about places.
   - This research grant uses *[[Gormenghast|example.gormenghast]]* by Mervyn Peake to explore synergies between design, literature and place.
2. Use text analysis tools to extract data about place from this text
   - [[Sentiment analysis|experiment.sentiment-analysis]] summarises moods and emotions in text(s).
   - Measuring [[collocations|experiment.term-explorer]] between words highlights the descriptive words associated with place nouns.
   - [[Frequency searches|experiment.color-words]] measures the importance of words in text(s).
   - Reviewing [[words in context|experiment.library-sentences]] helps verify assumptions derived from automated methods.
    - [[Arranging words|experiment.color-timeline]] by occurence reveals trends in language usage over 'time'.  
3. Explore the limitations of this data and suggest improvements.
   - A working [[schema|experiment.place-schema]] relates this data about place language.
   - Exploring the [[biases implict in language|experiment.bias-in-language]] reveals the limitations 
4. Suggest applications for this data.
   - This data can inform [[representatations|experiment.parametric-hermeneutics]] of places.
#### Agents

- Directly involved
  - Readers of the novel can use the timeline as a tool to supplement deep reading and exploration of the novel.
  - Designers and artists can use the tool to support creative (re-)interpretations of the novel.
- Implicitly invoked
  - [[The author|example.gormenghast]] and his unique set of experiences, biases, stylistic flourishes, etc.

#### Medium

  1. The full text of the novel (unstructured text).
  2. External sources, databases and techniques (lists of colors from thesauri, specialist databases, natural language processing libraries, etc.).
  3. Images, graphs and tables that [[interpret the novel (item 1) using information from item 2|experiment.place-schema]].

### Methods

- Select a test corpus
  - We limited our analysis to a single fictional text, _The Gormenghast Novels_ by Mervyn Peake. We selected these novels for their focus on place, which others have observed: in his introduction to *Titus Groan*, Anthony Burgess describes Peake’s writing as architectural and three-dimensional qualities.[^1] The trilogy is also the subject of a PhD thesis by Lesser Woods, who uses the novel’s descriptions as the basis for architectural designs.[^2]

### Results

- See [[example.experiment]] for the outcomes of our attempts to apply the above logic to several "phenomena" in the novel.

[^1]: Mervyn Peake, Anthony Burgess, and Quentin Crisp, _The Gormenghast Novels_ (Woodstock: Overlook Press, 1995).
[^2]: Imogen Helen Louise Lesser Woods, “Literary Language as a Tool for Design: An Architectural Study of the Spaces of Mervyn Peake’s The Gormenghast Trilogy and ‘Boy in Darkness’” (PhD, Kent, University of Kent, 2018).

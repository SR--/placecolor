---
id: 7_ug5qkhWRcPsYKaeMsG8
title: Text Analysis Overview
desc: 'Standard introduction for experiments using text analysis to explore place in *[[Gormenghast|example.gormenghast]]*.'
updated: 1646185161593
created: 1624955696999
---

![](/assets/images/sample_dat_filtered.png)
<p>
<figcaption>
Excerpt from text analysis of <i>Gormenghast</i>.
</figcaption>
</p>

- An observer's perception of an environment contributes to their sense of a place.
- Cultural and biological factors influence these perceptions
  - A bird species may instinctively fear a shape resembling a predator, or covet a certain color.
  - First Nations people may avoid a place they consider sacred based on a shared oral and/or written history.
- Species possessing sentience, language and culture generate complex narratives about places that can vary between members of the same cultural group. 
## Significance

- What motivated our inquiry?
  - Desire to extract subjective descriptions of place from text (e.g., adjectives, place names) and parse them to identify patterns and trends (e.g., common associations between nouns and descriptive words).
- Who could this research benefit?
  - Our intended audience is designers, particularly those working with nonhumans.
    - Benefits extend to collaborators, e.g. ecologists, biologists, botanists, etc.
    - Greater knowledge of nonhuman perspectives can improve design outcomes.
  - The [[timeline|experiment.color-timeline]] can support exploration of the novel and guide deep reading.
  - Tools can support creative efforts by designers and artists.
- How does it relate to the [[broader themes|relationship]]?
  - Differences in perceptual abilities between species influences their conception of place, which informs culture, social dynamics, and ways of understanding their environment.
    - Concepts from animal justice studies conted that nonhuman species enact behaviours that satisfy ecocentric definitions of culture [REF]. Animals develop instinctive (fight or flight) responses to places based on positive and negative experiences and share this knowledge with others [REF]. 
      - For example, crows communicate rituals ([Example]) to eachother using rudimentary language, hereditary exchange, and mirroring [REF].
      - Plant species "prefer" places with resources that support flourishing.
      - One can argue that nonhuman species can construct place attachments depending on the sophistication of their perceptual abilities.


- [ ] Integrate the paragraph below.
- Provide tools and methods for "quantifying" the use of language related to [[place|relationship.place]] in *Gormenghast* with a focus on the relationships between:
  1. Phenomena such as [[color|relationship.color]], light, texture and atmosphere.
  2. Discrete geographical locations and their component parts, e.g. buildings and rooms, forests and trees, etc.
- Explore and discuss issues relevant to [[place|relationship.place]], [[design|relationship.design]] and [[communication|relationship.communication]] that emerge from attempts to create these tools, particularly those that emphasize the differences in [[subjectivity|relationship.subjectivity]] between species.
- Describe the difficulties inherent in attempting to "quantify" subjective phenomena such as atmosphere, mood and events from unstructured text.
  - Ambiguous/loosely-defined cultural phenomena such as [[place|relationship.place]] are amalgamations of different sources not limited to the impression created directly by language, e.g. collective/cultural memory such as awareness of other works, history, symbolic associations play a large part.

## Research Gap

- Challenges and limitations of quantifying subjective text 
  - Statistical analysis of subjective descriptions is difficult. 
  - Current methods for quantifying interpretations of places (e.g., journal entries, online reviews, social media posts) capture few descriptive place terms. 
    - These methods produce binary or hierarchical interpretations of a place, e.g. what adjectives visitors use to describe a Google Maps location.[REF]
    - Large datasets exist to support analysis, but these are intended for commercial applications (e.g., market research, improving search engine results).
- Quantifying a 'place' is difficult because places are subjective and complex.
  - Cultural, physical, biological, evolutionary, social, and economic dynamics contribute to an individual's sense of place. It is difficult to delineate and extract these factors from texts alone.

## Opportunity

- Literature describes the subjective qualities (atmosphere, geography, histories, culture, emotions, etc.) of fictional places.
- Use methods from other disciplines to analyse representative texts. 
  - Digital humanities and natural language processing
    - Digital humanities scholars use natural language processing and statistical analysis to quantify literary texts. These approaches identify trends in word usage (how many times a word or word pair is used) in a single text (e.g., *Moby Dick* by Herman Melville) or large corpora (e.g., the works of Jane Austen or all Gothic novels published during the 19<sup>th</sup> century).
    - Sentiment analysis uses lexicons to approximate the sentiment of words.  The process determines the 'sentiment' of a text (e.g., a sentence or paragraph) by assigning each word to a lexicon category. 
      - The [NRC Emotion Lexicon](https://saifmohammad.com/WebPages/NRC-Emotion-Lexicon.htm) is an open-source lexicon for sentiment analysis that can score words based on sentiments (positive or negative) and eight emotions (anger, anticipation, disgust, fear, etc...).[^c]
  - Geographical information (imagination) systems
    - Speculative research (c.f. 'geographic imagination systems') demonstrates applications of these methods.[^a] [^b]
  - Automating semi-supervised methods for extracting place data establishes a basic standard for 

### Limitations

- Our only source of information is the English language, which biases Enlightenment-era worldviews founded on rationalist principles [REF]. Anthropocentric language is blind to the richness of nonhuman life.
  - As society becomes less enmeshed with nonhuman nature, language has lost many place-based terms. [REF, Robert MacFarlane]
  - Reference material about nonhuman species (textbooks, academic papers, natural history) adopt an ecocentric position eliminates some anthropocentric bias, as does fiction focused on places.
    - The influence of errors decreases as corpus size increases: trends observed in the works of Jane Austen are more reliable than one paragraph from *Pride and Prejudice*.
  - An author's experiences, biases and style influence results. 
- Our knowledge of statistical methods limits the replicability of our findings. We acknowledge that errors will exist, but hope others will find our conceptual approach interesting. We aim to demonstrate that applying these methods to novel scenarios can produce interesting results that others can extend. 
## Research Question

- Text analysis tools can automate the extraction of descriptive words about places in literary text(s)
## Methods

1. Select a text containing descriptive language about places.
   - This research grant uses *[[Gormenghast|example.gormenghast]]* by Mervyn Peake to explore synergies between design, literature and place.
     - In his introduction to *Titus Groan*, Anthony Burgess describes Peake’s writing as architectural and three-dimensional qualities.[^d] The trilogy is also the subject of a PhD thesis by Lesser Woods, who uses the novel’s descriptions as the basis for architectural designs.[^e]
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


- [ ]: Integrate this text with the main Methods section
5. The full text of the novel (unstructured text).
6. External sources, databases and techniques (lists of colors from thesauri, specialist databases, natural language processing libraries, etc.).
7. Images, graphs and tables that [[interpret the novel (item 1) using information from item 2|experiment.place-schema]].
## Results

- See [[example.experiment]] for the outcomes of our attempts to apply the above logic to several "phenomena" in the novel.


[^a]: Michael E. Martin and Nadine Schuurman, “Area-Based Topic Modeling and Visualization of Social Media for Qualitative GIS,” *Annals of the American Association of Geographers* 107, no. 5 (2017): 1028–39, https://doi.org/10/gg6twg.
[^b]: Luke Bergmann and Nick Lally, “For Geographical Imagination Systems,” *Annals of the American Association of Geographers*, 2020, 1–10, https://doi.org/10/gg6tb6.
[^c]: Saif M. Mohammad and Peter D. Turney, “Crowdsourcing a Word-Emotion Association Lexicon,” *Computer Intelligence* 29, no. 3 (2013): 436–65, https://doi.org/10/f45xmb.
[^d]: Mervyn Peake, Anthony Burgess, and Quentin Crisp, _The Gormenghast Novels_ (Woodstock: Overlook Press, 1995).
[^e]: Imogen Lesser Woods, “Literary Language as a Tool for Design: An Architectural Study of the Spaces of Mervyn Peake’s The Gormenghast Trilogy and ‘Boy in Darkness’” (PhD, Kent, University of Kent, 2018).

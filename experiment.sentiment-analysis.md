---
id: w9rAi27i4oZvgEKfBZKSI
title: Sentiment Analysis
desc: ''
updated: 1645420709578
created: 1624857363634
---

- [ ] Find specific examples 

- An observer's perception of an environment contributes to their sense of a place.
- Cultural and biological factors influence these perceptions
  - A bird species may instinctively fear a shape resembling a predator, or covet a certain color.
  - First Nations people may avoid a place they consider sacred based on a shared oral and/or written history.
- Species possessing sentience, language and culture generate complex narratives about places that can vary between members of the same cultural group. 
    

## Significance

- What motivated our inquiry?
  - Desire to extract subjective descriptions of place from text (e.g., adjectives, place names) and parse them to identify patterns and trends (e.g., common associations between nouns and descriptive words)
  - Use descriptive
- Who could this research benefit?
  - Our intended audience is designers, particularly those working with nonhumans.
    - Benefits extend to collaborators, e.g. ecologists, biologists, botanists, etc.
    - Greater knowledge of nonhuman perspectives can improve design outcomes.   
- How does it relate to the [[broader themes|relationship]]?
  - Differences in perceptual abilities between species influences their conception of place, which informs culture, social dynamics, and ways of understanding their environment.
    - Concepts from animal justice studies conted that nonhuman species enact behaviours that satisfy ecocentric definitions of culture [REF]. Animals develop instinctive (fight or flight) responses to places based on positive and negative experiences and share this knowledge with others [REF]. 
      - For example, crows communicate rituals ([Example]) to eachother using rudimentary language, hereditary exchange, and mirroring [REF].
      - Plant species "prefer" places with resources that support flourishing.
      - One can argue that nonhuman species can construct place attachments depending on the sophistication of their perceptual abilities.

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
- Accessible (open-source, suitable for personal computers) software can perform categorisation based on word frequency (how many 'positive' words appear in this sentence?) but struggles with complex language tasks (detecting sarcasm, negation, qualifications), which can reduce accuracy. 
    - The influence of errors decreases as corpus size increases: trends observed in the works of Jane Austen are more reliable than one paragraph from *Pride and Prejudice*.
- Our knowledge of statistical methods limits the replicability of our findings.We acknowledge that errors will exist, but hope others will find our conceptual approach interesting. We aim to demonstrate that applying these methods to novel scenarios can produce interesting results that others can extend. 

## Methods

### Agents

- Who is involved?
- Who/what are the perceiving agents?
  - Clients
  - Actors
- What is the medium?

### Process

- How did we conduct the experiment?

## Results

- What is the format of the experiment?
- How is the experiment accessed?
- Represent the experiment
  - [ ] Give more evocative examples
  - [ ] Extract .svg sentiment analysis graphs from R as discrete images


## Discussion

- What research could extend or use these ideas? 

[^a]: Michael E. Martin and Nadine Schuurman, “Area-Based Topic Modeling and Visualization of Social Media for Qualitative GIS,” *Annals of the American Association of Geographers* 107, no. 5 (2017): 1028–39, https://doi.org/10/gg6twg.
[^b]: Luke Bergmann and Nick Lally, “For Geographical Imagination Systems,” *Annals of the American Association of Geographers*, 2020, 1–10, https://doi.org/10/gg6tb6.
[^c]: Saif M. Mohammad and Peter D. Turney, “Crowdsourcing a Word-Emotion Association Lexicon,” *Computer Intelligence* 29, no. 3 (2013): 436–65, https://doi.org/10/f45xmb.
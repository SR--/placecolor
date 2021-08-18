---
id: 070rnS3sw99-bshQ2dr5E
title: ' Library Sentences'
desc: ''
updated: 1628660949224
created: 1624857724848
---

- [ ] Compile library sentences into an animated GIF
- [ ] Adapt explanation from Word document
- [ ] Convert R table image to Markdown 
- [ ] Format antConc collocates table

### Exhibition

![Library sentences (Placeholder)](/assets/images/2021-08-11-14-57-39.png)

- Sentences from *Gormenghast* containing the word "library"
- Demonstrates the variety of contexts that the library appears in
- Provide a simple interface (gallery or a series of animated GIFs) that allows users to browse the "library" sentences

### Technical Discussion

- Highlights the difficulty of extracting meaningful information about nouns in a restricted corpus
  - Statistical measures such as concordance make inferences that rely on large sample sizes for accuracy
  - Advanced dependency parsers such as [spaCy](https://spacy.io/api/dependencyparser) can identify related words and label them based on defined categories (e.g. an adjective that describes a noun)   
- Basic statistics
  - "library" (NOUN) appears 82 times

![Library collocates from antConc](/assets/images/2021-08-11-15-17-04.png)

- Calculates collocates (words that appear most frequently within a 5 word window) of "library" using the Mutual Information (MI) statistic

![Parsed library sentences as a table](/assets/images/2021-08-11-15-43-14.png)

- Example of table containing parsed tokens with the lemma fomr "library" from *Gormenghast*
# HarborChurchSermons
Harbor Church Sermons

Relation Information
- Series have sermons
- Sermons have a date, speaker, views, transcript, summary, tags, verses
- Verses have words, bigrams, trigrams, with stopwords or without; tags
- Topics have tags
  




Inputs

Outputs




Steps
1. Download transcripts
2. Summarize transcripts with GPT - Sermon Insight
3. Clean and summarize

Summarization Prompt:

Please summarize the sermon using the following format:

**Summary**: [Provide a one-sentence summary of the sermon.]

**Bible Verses**:
For each Bible verse mentioned in the sermon, provide:
1) **Reference**: [Book Chapter:Verse]
2) **Summary**: [One-sentence summary of the verse.]
3) **Text**: [The verbatim biblical text.]

**Content Tags**:
- [Tag 1]
- [Tag 2]
- [Tag 3]
- [Tag 4]
- [Tag 5]

*Note*: Limit content tags to 5, each on a separate line, without any preceding symbols like '#'.
Please ensure that the output strictly follows the format above, as consistency is essential for indexing purposes.


## 1. Download transscripts

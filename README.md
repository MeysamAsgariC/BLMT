# GeorgeFloydTopicDetection
In this repository, you can find the tweet ids and features extracted for the hand labeled 5k dataset.

In the `Obfuscated Data` zip file, you can find the xlsx, json and csv formats of the obfuscated data. In these files, ID means the tweet ids; which are also in the ids folder, which means the user can only crawl the needed dataset. 

In order to reference and learn more about the dataset, you can use the following bibtex and link to read the paper:

```bibtex
@misc{kemik2023blm17m,
      title={BLM-17m: A Large-Scale Dataset for Black Lives Matter Topic Detection on Twitter}, 
      author={Hasan Kemik and Nusret Özateş and Meysam Asgari-Chenaghlu and Yang Li and Erik Cambria},
      year={2023},
      eprint={2105.01331},
      archivePrefix={arXiv},
      primaryClass={cs.CL}
}
```
[Link to the paper.](https://arxiv.org/abs/2105.01331)

## METADATA

### Manually edited and crawled data:

- Hashtag: Hashtag that tweet crawled from
- Sentiment: Sentiment of the tweet
- Related_blm: If it's related with blm or not
- Sentiment Keyword(s): If there's a sentiment(1,2,3,4) on which words it's decided
- Day Keyword(s): Day keywords tagged from news headlines on the days.

Sentiment Labels:
- 1: Positive
- 2: Negative
- 3: Neutral
- 4: No Data
  
Related_blm Labels:
- 0: Not related
- 1: Related
- 4: No Data

### Automatically generated data:

- concept parsing
- subjectivity detection
- polarity
- intensity
- emotion recognition
- aspect extraction
- aspect based sentiment analysis
- personality ocean
- personality mbti
- depression
- toxicity
- engagement
- well being

For more information of these labels, please visit the [following link.](https://sentic.net/api/)

### Contributors

- [Hasan Kemik](https://scholar.google.com/citations?hl=en&user=cuU1gNMAAAAJ)
- [M. Nusret Özateş](https://scholar.google.com/citations?user=MBf9L5kAAAAJ&hl=en&oi=ao)
- [Meysam Asgari-Chenaghlou](https://scholar.google.com/citations?user=dEwOhQoAAAAJ&hl=en)
- [Yang Li](https://scholar.google.com/citations?user=jtogpBkAAAAJ&hl=en)
- [Erik Cambria](https://scholar.google.com/citations?user=ilSYpW0AAAAJ&hl=en)

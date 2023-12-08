# OrChiD
[EMNLP 2023] OrChiD: A Chinese Debate Corpus for Target-Independent Stance Detection and Argumentative Dialogue Summarization

Data format
The datast is saved as a list of dicts, and each dict consists of a debate match.
```
[
  {
    "competition": "debate name",
    "match": "specific match",
    "topic": "debate topic",
    "positions": {
      "PRO": "position statement of the pro side",
      "CON": "position statement of the con side"
    }
    "debate": [
      {
        "stance": "PRO",
        "debater": "P1",
        "utterance": "utterance by the 1st debater of the pro side"
      },
      ...
    ]
  },
  ...
]
```

The dataset is subject to further update.

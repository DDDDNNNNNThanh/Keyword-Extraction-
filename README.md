# Keyword-Extraction-

Keyword extraction algorithms are techniques designed to identify significant keywords or key phrases within textual documents. Their primary purpose lies in facilitating text summarization, indexing, and searching processes.

# Keyword Extraction Experiment

In this experiment, we explore different approaches to build a hot keyword extractor and compare them. The three approaches we investigate are:

| Approach        | Description                                                                                               |
| -------------- | --------------------------------------------------------------------------------------------------------- |
| Statistical    | Compute statistics for keywords and use those statistics to score them. Examples include word frequency, word collocation, co-occurrence, TF-IDF, and YAKE.  |
| Graph-based    | Create a graph of words or phrases and use graph algorithms to rank them. Examples include TextRank, Multi-word Keyword Scoring Strategy, ExpandRank, PositionRank, and Word Attraction Rank. |
| Deep-Learning  | Use embedding and similarity functions to compute the keywords. An example algorithm is KeyBERT.         |

For each approach, we pick one or two algorithms to be tested.

## Approach Details

1. **Statistical Approach**
   - Based on: Statistical properties
   - Inference Time: Low
   - Example Algorithms: Word frequency, word collocation, co-occurrence, TF-IDF, YAKE.

2. **Graph-based Approach**
   - Based on: Statistical properties
   - Inference Time: Low
   - Example Algorithms: TextRank, Multi-word Keyword Scoring Strategy, ExpandRank, PositionRank, Word Attraction Rank.

3. **Deep-Learning Approach**
   - Based on: Semantic Meaning
   - Inference Time: High
   - Example Algorithm: KeyBERT

Feel free to experiment with these algorithms and see how they perform in the context of the hot keyword extraction task.

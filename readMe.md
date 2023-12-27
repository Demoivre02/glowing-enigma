### String Merging Algorithms

This repository provides a set of algorithms for merging a collection of words into a superstring. Each algorithm adopts a distinct approach to find an optimal superstring based on specific criteria. Below is a concise overview of the functions included in this repository:

1. **exact(T):** Finds the exact superstring of a list of words by iteratively adding characters.

2. **naive(T):** Forms a superstring by overlapping words without changing their order.

3. **group_merge(T):** Merges overlapping words based on weights and selects the best superstring.

4. **greedy(T):** Greedily merges words to form a superstring, maximizing the overlap.

5. **mgreedy(T):** Applies a modified greedy algorithm to find the superstring.

6. **tgreedy(T):** Applies another variant of the greedy algorithm (tgreedy) to find the superstring.

### Usage

```python
from string_merging import exact, naive, group_merge, greedy, mgreedy, tgreedy

# Example list of words
word_list = ['word1', 'word2', 'word3']

# Use the desired algorithm
result_exact = exact(word_list)
result_naive = naive(word_list)
result_group_merge = group_merge(word_list)
result_greedy = greedy(word_list)
result_mgreedy = mgreedy(word_list)
result_tgreedy = tgreedy(word_list)
```

Choose the algorithm that best suits your requirements based on the characteristics of your input set.

### License

This code is provided under the MIT License. Refer to the [LICENSE](LICENSE) file for more details.
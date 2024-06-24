# Wordle-like-puzzle-heuristic
A heuristic solution for Wordle-like puzzle.

This algorithm uses an English dictionary to suggest words base on the response from API. Could reduce tons of requests.

## How to run
Open in Jupyter Notebook and just click `run all`.

Change the `seed` and the `size` in the following code block and run it for other words guessing.

```python
word, num_requests = guess_word(seed=17, size=7)
print(f"Word: {word}")
print(f"Number of requests: {num_requests}")
```

Sometimes the algorithm might not work in the first time. You could retry several times.

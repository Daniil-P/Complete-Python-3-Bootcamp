# Complete-Python-3-Bootcamp — review guidance

## Code Review Rules

These rules apply to pull request review. Check the current code and the applicable project specification before reporting a concrete regression.

- Keep lesson/exercise notebooks and their corresponding solutions distinct. Flag changes that silently replace an exercise with its answer or break relative dataset/import paths used by the notebook.
- When a notebook changes, check code-cell order, saved outputs and the documented Python assumptions together. A plausible saved output is not evidence that the modified cells execute from a fresh kernel.

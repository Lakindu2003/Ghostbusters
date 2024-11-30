# Ghostbusters
- Implement Bayes' nets inference in the file inference.py.
- Algorithms implemented
    1) Exact inference (using the Bayes' nets forward algorithm)
    2) Approximate inference (using particle filtering) to track the distribution of each ghost independently.
    3) Joint particle inference to track the joint distribution all ghost. This is to account for the DispersingGhost which avoids other ghost (ghost are no longer independent).

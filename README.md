image-resize-dp
===============

Image resizing dynamic programming.

How to use
----------

0. (Recommended) Set up a virtual environment and activate.
1. Install required modueles.
```bash
pip install -r requirements.txt
```
2. Run the program. NUMBER_SEAMS_TO_REMOVE=100 will take ~1.5 hour to complete.
```bash
python carve.py [INPUT_IMAGE] [NUMBER_SEAMS_TO_REMOVE] [OUTPUT_IMAGE]
# e.g. python carve.py surfer.jpg 2 surfer-output.jpg
```

What is used
-------------

Python, Algebra, Probabilities

Program-related knowledge
--------------------------

**Dynamic programming (DP)** - a technique for computing **recursive** algorithm with
highly **overlapping** subproblems by only solving each subproblem once.

Ascending by efficiency (descending by complexity): recursion, memoization, bottom-up.

**Content-aware image resizing** - resizing based on the content so that the result
looks natural.

**Seam carving** - removing uninterrupted sequences of pixels when resizing.

Props
-------------

For creating the course - [Avik Das on LinkedIn](https://www.linkedin.com/in/avikdas1990)

Image credits
-------------

All images are free to redistribute. Attribution is not necessary, but encouraged:

- Surfer - [Kiril Dobrev](https://pixabay.com/users/kirildobrev-12266114/) on [Pixabay](https://pixabay.com/photos/blue-beach-surf-travel-surfer-4145659/)

- Arch - [Mike Goad](https://www.flickr.com/photos/exit78/) on [Flickr](https://flic.kr/p/4hxxz5)
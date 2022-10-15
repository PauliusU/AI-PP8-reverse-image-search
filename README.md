# PP8 reverse image search

[![Open in Google Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/PauliusU/AI-PP8-reverse-image-search/blob/master/AI-PP8-reverse-image-search.ipynb)
[![MIT license](https://img.shields.io/badge/License-MIT-blue.svg)](https://github.com/PauliusU/AI-PP8-reverse-image-search/blob/master/LICENSE)

Practical Project 8 (PP8) for Artificial Intelligence studies to solidify basics of **reverse image search** by practicing.

## Usage

### Automatic launch

1. To run in browser click on [![Open in Google Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/PauliusU/AI-PP8-reverse-image-search/blob/master/AI-PP8-reverse-image-search.ipynb) badge.
2. (Or) To launch locally on Windows just **run automatic setup script** in `Git Bash`:

```bash
bash <(curl -s https://raw.githubusercontent.com/PauliusU/AI-PP8-reverse-image-search/master/setup.sh)
```

### Manual launch

1. Clone this repo:

```bash
git clone https://github.com/PauliusU/AI-PP8-reverse-image-search.git
```

2. Navigate into project:

```bash
cd AI-PP8-reverse-image-search/
```

3. Ensure pipenv is installed:

```bash
pip install --upgrade pipenv --user
```

4. Install dependencies:

```bash
pipenv install
```

5. Run project:

```bash
pipenv run jupyter notebook AI-PP8-reverse-image-search.ipynb
```

## Requirements

- [ ] Take all the code available for this part in the notebooks and create a single notebook that has all the
main parts of the code:
    - downloads the data (caltech101 or similar),
    - initialization of the model,
    - extracting the weights from CNN,
    - using KNN for similarity search and
    - the flask web app code. You can skip the optimizations for KNN / PCA and so on.
- [ ] You don’t need to improve the model or the webapp, just make it comfortable to create the web app
from the code in the notebook - the only requirement is that the code should work.
- [ ] Write a short paragraph on what you learned while implementing a solution for this specific task (4 sentences / ideas minimum).
- [ ] Provide a link to the collab notebook for review and evaluation.

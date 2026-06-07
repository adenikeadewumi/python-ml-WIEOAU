# 📓 Opening Notebooks in Google Colab

## The "Open in Colab" Button

Every notebook in this repository has an **Open in Colab** badge at the top:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/)

When you push this repository to GitHub, clicking the badge will open that exact notebook in Google Colab — no setup required.

## How to Make It Work

The badge URL contains your GitHub username and repository name. Before publishing, replace `YOUR_GITHUB_USERNAME` in every notebook with your actual GitHub username.

**Quick way to do this:**
```bash
# Replace in all notebooks at once (run from the repo root)
find . -name "*.ipynb" -exec sed -i 's/YOUR_GITHUB_USERNAME/your-actual-username/g' {} +
```

For example, if your GitHub username is `pythonlearner`:
```bash
find . -name "*.ipynb" -exec sed -i 's/YOUR_GITHUB_USERNAME/pythonlearner/g' {} +
```

## Publishing to GitHub

```bash
# 1. Create a new repository on github.com (do NOT initialise with README)

# 2. In your local course folder:
git init
git add .
git commit -m "Initial commit: Python for ML & Data Science course"

# 3. Link to your GitHub repository
git remote add origin https://github.com/YOUR_USERNAME/python-ml-course.git

# 4. Push
git branch -M main
git push -u origin main
```

After pushing, go to any `.ipynb` file on GitHub — you will see the Colab badge. Click it and the notebook opens instantly in Colab.

## Running in Colab

When a notebook opens in Colab, run this in the first code cell to install dependencies:

```python
!pip install scikit-learn pandas matplotlib seaborn numpy
```

For the deep learning module:
```python
!pip install tensorflow
```

Colab provides free GPU access — use it for Module 15 (Deep Learning).

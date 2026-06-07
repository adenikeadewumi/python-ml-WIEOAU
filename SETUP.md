# 🛠️ Setup Guide

## Option 1: Local Installation (Recommended)

### 1. Install Python
Download Python 3.10+ from [python.org](https://www.python.org/downloads/).

**Verify:**
```bash
python --version   # Should show 3.10 or higher
```

### 2. Clone This Repository
```bash
git clone https://github.com/YOUR_USERNAME/python-ml-course.git
cd python-ml-course
```

### 3. Create a Virtual Environment
```bash
# Create
python -m venv venv

# Activate
source venv/bin/activate        # macOS / Linux
venv\Scripts\activate           # Windows (Command Prompt)
.\venv\Scripts\Activate.ps1     # Windows (PowerShell)

# Your prompt should now show (venv)
```

### 4. Install Dependencies
```bash
pip install -r requirements.txt
```
This installs: Jupyter, NumPy, Pandas, Matplotlib, Seaborn, Scikit-learn, and more.

> **Note:** TensorFlow (for Module 15) may need a separate install:
> ```bash
> pip install tensorflow
> ```

### 5. Launch Jupyter
```bash
jupyter notebook
```
Your browser will open. Navigate to any `.ipynb` file to begin.

---

## Option 2: Google Colab (Zero Setup)

1. Go to [colab.research.google.com](https://colab.research.google.com/)
2. Click **File → Open notebook → GitHub**
3. Paste this repo's URL
4. Open any notebook — all packages are pre-installed!

> Most packages are pre-installed in Colab. For anything missing, run `!pip install package_name` in a cell.

---

## Option 3: Kaggle Kernels

1. Go to [kaggle.com](https://www.kaggle.com/) and create a free account
2. Click **Code → New Notebook**
3. Upload individual `.ipynb` files
4. Free GPU access available!

---

## Troubleshooting

| Problem | Solution |
|---------|---------|
| `python: command not found` | Use `python3` instead, or check PATH |
| `pip: command not found` | Use `pip3` or `python -m pip` |
| Package not found | Make sure your venv is activated |
| Jupyter won't open | Try `jupyter notebook --no-browser` and open the URL manually |
| TensorFlow install fails | Try `pip install tensorflow-cpu` for a lighter install |

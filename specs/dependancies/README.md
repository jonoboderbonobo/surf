# Project Setup Guide

This project requires a Python virtual environment for managing dependencies.  
You can set up the environment using either **pip** (`requirements.txt`) or **conda** (`environment.yml`).

---

## **1. Using `environment.yml` (Recommended)**
If you are using **Conda**, you can create the exact same environment with:

```bash
conda env create -f environment.yml
```

After installation, activate the environment:

```bash
conda activate venv_anac_tt10_specs
```

If you need to update the environment later (after adding new dependencies), run:

```bash
conda env update --file environment.yml --prune
```

---

## **2. Using `requirements.txt` (For Pip Users)**
If you prefer using **pip** instead of Conda, manually create a virtual environment and install dependencies:

```bash
python -m venv venv_anac_tt10_specs
source venv_anac_tt10_specs/bin/activate  # Linux/macOS
venv_anac_tt10_specs\Scripts\activate     # Windows (cmd)
```

Then install dependencies:

```bash
pip install -r requirements.txt
```

To deactivate the environment:

```bash
deactivate
```

---

## **3. Running the Project**
Once the environment is set up and activated, you can run your script:

```bash
python main.py
```
(or replace `main.py` with the actual script file)

---

## **4. Updating Dependencies**
If you install new packages during development, update the dependency files:

### **For Conda Users**
```bash
conda env export --name venv_anac_tt10_specs > environment.yml
```

### **For Pip Users**
```bash
pip freeze > requirements.txt
```

---

## **5. Removing the Environment**
If you ever need to remove the virtual environment:

### **For Conda**
```bash
conda remove --name venv_anac_tt10_specs --all
```

### **For Pip**
Simply delete the `venv_anac_tt10_specs` folder:

```bash
rm -rf venv_anac_tt10_specs
```

---

Now your environment is set up and ready to use!

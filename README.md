# 👽 UFO Sightings: From Data Cleaning to Quantum Computing

> *Learning Pandas, NumPy, and Qiskit through one real-world dataset.*

## Overview

I didn't build this project to prove that quantum computers can explain UFOs.

I built it because I wanted one project that would force me to learn three different technologies the way they're actually used: **Pandas** for cleaning data, **NumPy** for numerical analysis, and **Qiskit** for introductory quantum computing.

Instead of jumping between tutorials and toy examples, I wanted to follow an end-to-end workflow using a real dataset. Every notebook in this repository represents another step in that journey.

The dataset contains over **80,000 reported UFO sightings** from multiple countries, including information such as location, date, encounter duration, UFO shape, and eyewitness descriptions.

By the end of this project, I had cleaned messy real-world data, explored it numerically, visualized patterns, and even represented parts of it inside quantum circuits.

---

# Why I Built This

One thing I've learned is that I understand technologies much better when I build something with them instead of simply watching courses.

This repository became my personal learning laboratory.

Instead of asking:

> "How do I learn Pandas?"

I asked:

> "How would a data scientist clean this dataset?"

Instead of asking:

> "How does NumPy work?"

I asked:

> "How can I analyze this cleaned data efficiently?"

Instead of asking:

> "How do I learn Qiskit?"

I asked:

> "How can I encode real numerical data into quantum circuits?"

That mindset completely changed how I approached learning.

---

# Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Qiskit
* Qiskit Aer
* Jupyter Notebook

---

# Dataset

This project uses a public UFO sightings dataset containing approximately **80,000 reports**.

The dataset includes:

* Date and time
* City
* State / Province
* Country
* UFO shape
* Encounter duration
* Description
* Date documented
* Latitude
* Longitude

Like most real-world datasets, it wasn't clean.

Some columns contained missing values.

Some numerical columns were stored as text.

Dates needed conversion.

Text columns had inconsistent formatting.

That made it an excellent dataset for learning data cleaning.

---

# Project Structure

```text
ufo-analysis/
│
├── data/
│   ├── raw/
│   └── processed/
│
├── notebooks/
│   ├── 01_data_cleaning.ipynb
│   ├── 02_numpy_analysis.ipynb
│   ├── 03_visualization.ipynb
│   └── 04_qiskit_analysis.ipynb
│
├── requirements.txt
├── README.md
└── .gitignore
```

---

# Notebook 01 — Data Cleaning (Pandas)

The first notebook focuses entirely on understanding and cleaning the dataset.

Topics covered include:

* Exploring the dataset
* Understanding data types
* Detecting missing values
* Converting text to numeric values
* Cleaning text columns
* Standardizing formatting
* Converting dates
* Creating new time-based features
* Saving a cleaned dataset

This notebook represents a realistic data cleaning workflow rather than a collection of isolated Pandas commands.

---

# Notebook 02 — NumPy Analysis

After cleaning the data, I switched from Pandas to NumPy.

Topics explored include:

* NumPy arrays
* Array indexing and slicing
* Descriptive statistics
* Percentiles
* Boolean indexing
* Outlier detection using IQR
* Normalization
* Building feature matrices

Rather than treating NumPy as a separate subject, I used it to continue analyzing the same dataset.

---

# Notebook 03 — Data Visualization

Numbers tell part of the story.

Visualization tells the rest.

Using Matplotlib, I explored patterns such as:

* Most common UFO shapes
* Sightings by country
* Distribution of encounter duration
* Geographic distribution of sightings
* Sightings over time
* Cities with the highest number of reports
* Outliers using boxplots

These visualizations helped reveal patterns that weren't obvious from tables alone.

---

# Notebook 04 — Quantum Computing with Qiskit

This notebook marks my introduction to quantum computing.

Instead of relying on artificial examples, I experimented with encoding real values from the UFO dataset into quantum circuits.

Topics include:

* Building quantum circuits
* Qubits
* Superposition
* Quantum gates
* Measurement
* Simulation with Qiskit Aer
* Encoding normalized encounter durations using rotation gates
* Simple quantum experiments

The goal wasn't to "solve UFOs with quantum computing."

The goal was to understand how classical numerical information can be represented inside quantum systems.

---

# What I Learned

This project taught me far more than syntax.

It taught me how different tools fit together in an actual workflow.

I learned that data science isn't just about training models.

Most of the work happens before machine learning even begins.

I also discovered how much easier quantum computing becomes once you already have clean, structured numerical data.

---

# Future Improvements

There are several directions I'd like to explore next.

* Interactive visualizations
* Feature engineering
* Classical machine learning
* Quantum machine learning
* Quantum kernels
* Variational Quantum Classifiers (VQC)
* QSVC
* Hybrid classical-quantum workflows
* Comparing classical and quantum approaches

---

# Running the Project

Clone the repository.

```bash
git clone https://github.com/Emmanuella-Adams/ufo-analysis.git
```

Move into the project.

```bash
cd ufo-analysis
```

Install dependencies.

```bash
pip install -r requirements.txt
```

Launch Jupyter.

```bash
jupyter notebook
```

Open the notebooks in numerical order.

---

# Repository Goals

This repository is not intended to present groundbreaking scientific discoveries about UFOs.

Its purpose is to document my learning journey through the Python data science ecosystem and my first practical experiments with quantum computing.

Every notebook builds on the previous one, showing how a single dataset can take you from messy raw data to quantum simulations.

---

# A Note from Me

I'm a firm believer that the best way to learn is to build.

This repository is one example of that philosophy.

Rather than collecting certificates or completing isolated exercises, I wanted to work through a complete project from start to finish.

If you're learning Pandas, NumPy, or Qiskit yourself, I hope this repository gives you ideas for building projects that connect multiple skills instead of treating each library as its own separate world.

Learning sticks when everything has a purpose.

---

## License

This project is available under the MIT License.

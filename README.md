# Stats4Cosmology 
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.13614370.svg)](https://doi.org/10.5281/zenodo.13614370)

A curated collection of **Jupyter notebooks** introducing and applying **statistical methods** and **cosmological inference** tools to problems in **cosmology**.  

This repository combines:

- Practical statistical tutorials for students and researchers.  
- Step-by-step **Cobaya tutorials** for Bayesian cosmological parameter estimation and model comparison, now included as a subfolder of the main tutorials.

---

## ✨ Contents

### 1. Stats4Cosmology Notebooks (`tutorials/statistics`)
- **Probability & Statistics Refresher** – Basics of probability distributions, likelihoods, and Bayes’ theorem.  
- **Bayesian Inference in Cosmology** – MCMC, nested sampling, and posterior exploration with toy cosmological models.  
- **Fisher Forecasting** – Deriving Fisher matrices and forecasting cosmological parameter constraints.  
- **Likelihoods for Cosmology** – Building Gaussian and non-Gaussian likelihoods connected to cosmological data vectors.  
- **Applications** – Toy SN & LSS parameter estimation, combining multiple probes, impact of priors and degeneracies.

### 2. Software Tutorials (`tutorials/software/`)
- **Cobaya** – Sampling multi-variate Gaussian and Ring likelihoods; running simple cosmology chains & using the `get_model()` wrapper in Cobaya to access all internal calculations without modifying the source code.   

---

## 🚀 Getting Started

### Clone the Repository
```bash
git clone https://github.com/your-username/Stats4Cosmology.git
cd Stats4Cosmology
```

### Launch Jupyter, or Cloud servers
```bash
jupyter lab
```
Open any notebook under the `tutorials/` folder to explore Stats4Cosmology, or navigate to `tutorials/software/` for software specific exercises.

You can run Cobaya notebooks on [Google Colab](http://colab.research.google.com). For `Cobaya` specific notebooks you will need:
```bash
!pip install cobaya
!cobaya-install cosmo -p .
```

---

## 📚 Dependencies

The notebooks rely on standard scientific Python libraries widely used in astronomy and cosmology:

- [`numpy`](https://numpy.org/) – numerical computing  
- [`scipy`](https://scipy.org/) – scientific routines  
- [`astropy`](https://www.astropy.org/) – astronomy & cosmology utilities  
- [`matplotlib`](https://matplotlib.org/) – plotting  
- [`seaborn`](https://seaborn.pydata.org/) – statistical visualization  
- [`jupyter`](https://jupyter.org/) – interactive notebooks  
- [`cobaya`](https://pypi.org/project/cobaya/) – cosmological Bayesian analysis (for Cobaya tutorials)  

---

## 🧑‍🏫 Who Is This For?

- **Students** in astrophysics, physics, or statistics wanting hands-on cosmological inference training.  
- **Researchers** looking for ready-to-use templates for teaching, lectures, or experimentation.  
- **Educators** needing practical examples for cosmology and data science courses.  
- **Anyone** interested in learning how to use Cobaya for Bayesian cosmological analysis.

---

## 👩‍🚀 Author

Developed and maintained by **Dr. Guadalupe Cañas-Herrera**, inspired by real-world cosmological pipelines in the era of **Euclid**, probably biased by Planck 18 analysis experience.  

---

## 📄 License

This project is licensed under the MIT License – see the [LICENSE](LICENSE) file for details.

---

## ⭐ Citation

If you find these notebooks useful in your research or teaching, please cite:

```bibtex
@misc{stats4cosmology,
  author       = {Cañas Herrera, Guadalupe},
  title        = {Stats4Cosmology: Jupyter notebooks for statistical methods in cosmology, including Cobaya tutorials},
  year         = {2025},
  howpublished = {\url{https://github.com/gcanasherrera/Stats4Cosmology}}
}
```

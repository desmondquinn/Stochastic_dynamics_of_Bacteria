# Stochastic dynamics of bacteria

## Bacterial Taxis Simulation

## Notebook : Bacterial_taxis-animation.ipynb

![Alt text](bacteria_animation_2.gif)


## 📖 About
This notebook simulates the **taxis behavior of bacteria** in a 2D domain under an environmental gradient (e.g., nutrient concentration, temperature).  
It models bacteria as self-propelled particles performing **run-and-tumble motion** with memory-based bias toward favorable conditions. The simulation tracks individual trajectories, distributions, and produces animations of their movement.


## ⚙️ Features
- Agent-based model
- 2D domain simulation with configurable size and number of bacteria
- Customizable concentration/temperature gradients
- Visualisation of dynamics and relevant statistical quantities


## 🧪 Simulation Details

### Bacteria Model
- Propelled with velocity \(v_0\)
- Tumbles occur randomly following a **Poisson process**
- Run durations follow an **exponential distribution**
- **Biochemical memory** affects run duration if moving away from higher concentration


## 📦 Requirements
- Python 3.8+
- NumPy
- Matplotlib
- tqdm
- FFMpeg

Install dependencies:
```bash
# Using pip
pip install numpy matplotlib tqdm ipython ffmpeg
```


## 🔗 References
- Berg, H. C. *E. coli in Motion*, Springer, 2004.
- Tailleur, J., & Cates, M. E. “Statistical Mechanics of Interacting Run-and-Tumble Bacteria”, *Phys. Rev. Lett.*, 100:218103, 2008.

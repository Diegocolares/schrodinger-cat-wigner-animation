# 🐱 Schrödinger Cat State Animation (Cinematic Wigner Visualization)

## 🖼️ Preview

![Schrodinger Cat](cat_state_cinematic_fixed(2).gif)


## 🎬 Overview

This project presents a **cinematic visualization of a Schrödinger cat state** in phase space using Python.

The animation shows the evolution of a quantum superposition through:

* state splitting
* quantum interference
* decoherence
* recombination (looping)

All rendered as a **high-quality animated GIF** using the Wigner quasi-probability distribution.

---

## 🧠 Physical Concept

A Schrödinger cat state is defined as:

`|ψ⟩ ∝ |α⟩ + e^{iφ}|−α⟩`
This superposition leads to:

* two coherent-state lobes in phase space
* interference fringes (signature of non-classicality)
* negative regions in the Wigner function

The animation captures how these features emerge and vanish under decoherence.

---

## 🚀 Features

* 🎨 Cinematic visualization (dark theme + custom colormap)
* 🔬 Optional **QuTiP-based physical Wigner function**
* ⚡ Lightweight fallback (runs without QuTiP)
* 🔁 Smooth looping animation
* 🌌 Highlight of quantum interference and negativity
* 📊 Real-time display of:

  * displacement ( \alpha )
  * coherence
  * phase

---

## 📦 Installation

### Option 1 — Google Colab

```python
!pip install -q qutip pillow imageio
```

### Option 2 — Local Python

```bash
pip install qutip matplotlib pillow imageio numpy
```

---

## ▶️ How to Run

```bash
python cat_state_cinematic.py
```

After execution, the script generates:

```
cat_state_cinematic_fixed.gif
```

---

## 🖼️ Preview

*(Add your GIF here after upload)*

```markdown
![Cat State Animation](cat_state_cinematic_fixed.gif)
```

---

## ⚙️ Configuration

You can tweak the animation via:

```python
ALPHA_TARGET = 2.35   # separation of coherent states
N_FRAMES = 220        # animation length
FPS = 24              # smoothness
GRID = 260            # resolution
```

---

## 🔬 With vs Without QuTiP

| Mode      | Description                         |
| --------- | ----------------------------------- |
| QuTiP ON  | Physically accurate Wigner function |
| QuTiP OFF | High-quality visual approximation   |

For scientific applications, **QuTiP is recommended**.

---

## 📁 Project Structure

```
.
├── cat_state_cinematic.py
├── cat_state_cinematic_fixed.gif
└── README.md
```

---

## 💡 Applications

* Quantum computing education
* Phase-space visualization
* Research presentations
* Scientific communication
* High-impact visual content (LinkedIn / talks)

---

## 🧑‍🔬 Author

**Diego da Mota Colares**
PhD in Teleinformatics Engineering
Researcher in Quantum Systems, AI & Complex Systems

---

## ⭐ Contributing

Feel free to fork, improve visuals, or extend with:

* real decoherence channels
* master equation evolution
* Bloch + Wigner hybrid animations
* quantum circuit integration

---

## 📜 License

MIT License

---


# Reinforcement_Parking
---

# 🚗 Dynamic Programming for Parking Optimization — Georgian College DRL Assignment

This project applies **Dynamic Programming (DP)** techniques like **Policy Evaluation**, **Policy Improvement**, and **Value Iteration** to solve a real-world problem: optimizing parking space usage at Georgian College.

Using a custom environment inspired by **Markov Decision Processes (MDP)**, the system models various pricing strategies to promote better parking availability during winter shortages.

---

## 📘 Table of Contents

* [📌 Overview](#-overview)
* [🧠 Concepts Covered](#-concepts-covered)
* [🧪 Technologies Used](#-technologies-used)
* [🚀 How to Run](#-how-to-run)
* [📊 Results Summary](#-results-summary)
* [📂 Folder Structure](#-folder-structure)
* [📬 Contact](#-contact)

---

## 📌 Overview

During winter, Georgian College experiences a shortage of parking spaces. To improve **social welfare**, the administration wants to ensure:

* Higher parking space usage
* At least one parking spot always remains available

A **Dynamic Pricing Strategy** is proposed and evaluated using **Value Iteration** and **Policy Iteration** algorithms over an MDP environment simulating different price levels and user responses.

---

## 🧠 Concepts Covered

* **Markov Decision Processes (MDP)**
* **Bellman Equations**
* **Policy Evaluation & Improvement**
* **Value Iteration**
* **Stochastic vs Deterministic Policies**
* **Reward Function Engineering**
* **State-Value Function $V(s)$** and **Policy $\pi(s)$**

---

## 🧪 Technologies Used

| Tool/Library      | Purpose                                    |
| ----------------- | ------------------------------------------ |
| Python 3.10+      | Base language                              |
| NumPy             | Array operations & numerical computing     |
| Matplotlib        | Visualizing value functions                |
| Custom `tools.py` | Contains the environment class `GCParking` |
| Pickle            | Saving trained policies and results        |
| Jupyter Notebook  | For experiment design and documentation    |

---

## 🚀 How to Run

1. Clone this repo:

   ```bash
   git clone https://github.com/yourusername/georgian-parking-dp.git
   cd georgian-parking-dp
   ```

2. Make sure `tools.py` is in the correct folder. You may need to change the path in the notebook:

   ```python
   os.chdir(r"path_to_your_folder_containing_tools.py")
   ```

3. Install dependencies (if not already installed):

   ```bash
   pip install numpy matplotlib
   ```

4. Run the notebook:

   ```bash
   jupyter notebook Lec_4_Assignment_1_DRL.ipynb
   ```

---

## 📊 Results Summary

* **Value Iteration** and **Policy Iteration** converge to optimal policies quickly (in 6–10 iterations).
* Optimal pricing schemes tend to favor mid-level pricing to balance demand and spot availability.
* Final learned policies prioritize keeping at least one space open, aligning with college preferences.

Example of Value Function Heatmap:

> *(Add visualization or image if available)*

---



## 📂 Folder Structure

```
📦georgian-parking-dp
 ┣ 📜Lec_4_Assignment_1_DRL.ipynb
 ┣ 📜tools.py
 ┣ 📜README.md
 ┗ 📦outputs/
    ┗ 📜policy_output.pkl
```

---

## 📬 Contact

For any inquiries, contact the project lead:

**Bruce-Arhin Shadrach**
📧 [brucearhin098@gmail.com](mailto:brucearhin098@gmail.com)
📍 Barrie, Ontario, Canada
🔗 [LinkedIn](https://www.linkedin.com/in/bruce-arhin-shadrach/) |

---


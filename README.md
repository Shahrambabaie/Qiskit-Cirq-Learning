<<<<<<< HEAD
# 🧮 QSiM: Quantum Simulator
*A lightweight NumPy-based quantum circuit simulator inspired by Qiskit.*

![QSiM Example](images/top.png)

---

## 📌 Overview

**QSiM** is a custom quantum circuit simulator written entirely from scratch in **Python 3**, using only:

- `numpy`
- `matplotlib`
- `array`
- `cmath`
- `math`
- `random`

It provides a simple, Qiskit-like interface while remaining fully independent of Qiskit.  
This simulator is designed for experimentation, learning, and exploring the fundamentals of quantum circuits without relying on external frameworks.

---

## ⚙️ Features

### 🧱 Quantum Circuit Class
- **`Circuit712()`** — core class for building and simulating multi-qubit circuits.

### 🔹 Single-Qubit Gates
- Hadamard (`H`)
- Pauli gates (`X`, `Y`, `Z`)
- Rotation gates (`Rx`, `Ry`, `Rz`)

### 🔸 Two-Qubit Gates
- Controlled-X (`CX`)
- Controlled-Z (`CZ`)

### 🔺 Three-Qubit Gates
- Toffoli (`CCX`)

### 🔄 Other Operations
- SWAP gate  
- Measurement
- Pre-measurement statevector extraction  

---

## 🧰 Visualization & Simulation Tools

### 🎨 `draw_circuit()`
Generates a 2D visualization of the implemented quantum circuit.  
![Circuit Visualization](images/2D.png)


### ▶️ `simulate(shots)`
Runs the full statevector simulation for a given number of shots.  
![Circuit Visualization](images/out.png)

### 🔍 `simulation_pre_measurement_statevector()`
Returns the statevector of the system immediately before measurement.  
![Circuit Visualization](images/state.png)

### 📊 `draw_histogram()`
Generates a histogram of measurement outcomes.  
![Circuit Visualization](images/his.png)

---

```

## 📁 Project Structure
QSiM/
│── QSim.py # Main simulator file
│── Examples # Notebook to demonstrate implementedcircuits
│ ├── ... # Quantum Circuits, execution results, histograms, and etc.
│── images/
│ ├── ... # Circuit plots, histograms, etc.
│── README.md # Project documentation

```

---

## 🧪 Example Circuits (12 total)

The `examples/` folder contains **twelve quantum circuits** implemented using QSiM.


---

## 🔧 Dependencies

QSiM requires only minimal dependencies:


---

## 📖 Purpose

Developed as a project for the **Quantum Seminar Course at the University at Buffalo.**

---

## 📜 License

This project is released under the **MIT License**.
=======
# Qiskit-Learning
Qiskit Samples
>>>>>>> 3a48350906356ad26c50e190bc97213bec061f2e

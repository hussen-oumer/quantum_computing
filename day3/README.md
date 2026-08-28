# Day 3: Transpilation and pulses 🔧

How code actually runs on hardware: mapping circuits to the chip's qubit layout, then down to the physical pulses and measurements. Three notebooks.

Each notebook runs in Google Colab. When you reach the cell that asks for your IQM Resonance API token, that is where the code starts running on the real quantum hardware.

## 1. Transpilation with a GHZ state

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/hussen-oumer/quantum_computing/blob/main/day3/transpilation_ghz_state.ipynb)
`transpilation_ghz_state.ipynb`

- Connect to a real QPU and look at its qubit layout.
- Build a GHZ state, then rebuild it on different qubits.

## 2. From code to pulses, part 2

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/hussen-oumer/quantum_computing/blob/main/day3/abstract_code_to_physical_pulses_part2.ipynb)
`abstract_code_to_physical_pulses_part2.ipynb`

- Connect to the QPU station control.
- Compile a GHZ circuit into the pulses that drive the qubits.

## 3. From code to pulses, parts 3 and 4

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/hussen-oumer/quantum_computing/blob/main/day3/abstract_code_to_physical_pulses_part3.ipynb)
`abstract_code_to_physical_pulses_part3.ipynb`

- Measure qubits in different states and look at the readout.
- Change calibration settings and see what happens.

Source: [IQM Quantum Summer School](https://schools.iqmacademy.com/).

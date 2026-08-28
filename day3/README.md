# Day 3: Transpilation and pulses

How code actually runs on hardware: mapping circuits to the chip's qubit layout, then down to the physical pulses and measurements. Three notebooks.

## 1. Transpilation with a GHZ state

[Open in Colab](https://colab.research.google.com/github/hussen-oumer/quantum_computing/blob/main/day3/transpilation_ghz_state.ipynb)
`transpilation_ghz_state.ipynb`

- Connect to a real QPU and look at its qubit layout.
- Build a GHZ state, then rebuild it on different qubits.
- Homework: a large GHZ state with good routing, and checking its fidelity.

## 2. From code to pulses, part 2

[Open in Colab](https://colab.research.google.com/github/hussen-oumer/quantum_computing/blob/main/day3/abstract_code_to_physical_pulses_part2.ipynb)
`abstract_code_to_physical_pulses_part2.ipynb`

- Connect to the QPU station control.
- Compile a GHZ circuit into the pulses that drive the qubits.

## 3. From code to pulses, parts 3 and 4

[Open in Colab](https://colab.research.google.com/github/hussen-oumer/quantum_computing/blob/main/day3/abstract_code_to_physical_pulses_part3.ipynb)
`abstract_code_to_physical_pulses_part3.ipynb`

- Measure qubits in different states and look at the readout.
- Change calibration settings and see what happens.
- Homework: the dispersive shift, using calibration sweeps.

Source: IQM Quantum Summer School.

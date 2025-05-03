# IntelliTraffic-FSM-Based-Smart-Traffic-Light-Controller-using-Verilog

## 📝 Overview

**IntelliTraffic** is a Finite State Machine (FSM)-based smart traffic light controller developed using **Verilog Hardware Description Language (HDL)**. This project simulates intelligent traffic signal behavior at a **4-way intersection**, dynamically controlling traffic light transitions based on FSM logic. It serves as a foundational project in digital design and embedded systems coursework, focusing on practical implementation and simulation of real-world traffic management systems.

---

## 🎯 Features

* 🚗 **Supports 4-Way Intersection**: Manages traffic from North-South and East-West directions.
* 💡 **Independent Light Control**: Separate Red, Yellow, and Green light signals for both directions.
* 🔄 **Finite State Machine Design**: Efficient, deterministic control using FSM principles.
* 🔬 **Simulation Ready**: Includes a testbench for behavioral simulation.
* 🧠 **Realistic Timing**: Emulates typical urban traffic light patterns.
* 📁 Well-structured and modular Verilog codebase.

---

## 📂 Repository Structure

```
├── README.md                   # Project overview and documentation
├── Traffic light controller.pdf # Project report or design description
├── Verilog code                # Core FSM Verilog implementation
├── testbench                   # Testbench to verify functionality
```

---

## 🔧 Technologies Used

* **Language**: Verilog HDL
* **Simulation Tools**: ModelSim / Xilinx ISE / Vivado (or any Verilog-compatible simulator)
* **Design Paradigm**: FSM (Moore or Mealy based, depending on your implementation)

---

## 📐 FSM Design Summary

The controller operates based on a finite set of states corresponding to the traffic light phases. Each direction (North-South and East-West) alternates Green, Yellow, and Red lights according to a state transition table. Timing and sequence logic are embedded to ensure smooth and realistic traffic flow.

### Example States:

1. **NS\_Green\_EW\_Red**
2. **NS\_Yellow\_EW\_Red**
3. **NS\_Red\_EW\_Green**
4. **NS\_Red\_EW\_Yellow**

Each state includes output logic for signal lights and transition logic based on timers or counters.

---

## 🧪 Simulation & Testing

The project includes a **testbench** to simulate signal transitions and verify FSM behavior. You can simulate the controller in your preferred Verilog simulator.

### To Run:

1. Load the Verilog files and testbench in ModelSim or equivalent.
2. Compile and simulate the design.
3. Observe the waveform or console output to verify light transitions and timing.

---

## 📘 How to Use

1. Clone the repository:

   ```bash
   git clone https://github.com/YourUsername/IntelliTraffic-FSM-Based-Smart-Traffic-Light-Controller-using-Verilog.git
   ```
2. Open the files in your Verilog development environment.
3. Simulate the testbench to observe FSM behavior.
4. (Optional) Synthesize the design if implementing on FPGA.

---

## 📄 Documentation

Refer to the `Traffic light controller.pdf` file for detailed design explanation, FSM state diagram, timing diagram, and simulation waveforms.

---

## 🔍 Future Improvements

* Add **pedestrian signal** control logic.
* Incorporate **vehicle detection sensors** to dynamically adjust light durations.
* Expand to **multi-lane or T-junction** intersections.
* Implement a **graphical simulation interface**.


## 📝 License

This project is licensed under the MIT License. See the `LICENSE` file for details.

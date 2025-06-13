# Synchronous FIFO Design and UVM-Based Verification

This project implements a synchronous FIFO (First-In-First-Out) buffer in SystemVerilog and verifies its functionality using a modular UVM (Universal Verification Methodology) testbench.

---

## 🔧 Design Features

- Parses standard .vcd files for signal transitions and hierarchy

- Visualizes digital signals using time-domain plots

- Allows filtering signals by name or scope

- Supports exporting parsed signal data to CSV

- Modular architecture for future enhancements like GUI or protocol decoders

---

## 🚀 Getting Started

- **Prerequisites**:
  - Python 3.7 or higher

  - Install dependencies:
      pip install -r requirements.txt

- **Running the Project**:
    python main.py --file test/sample.vcd --signals clk,reset,data[3:0] --time_window 0,1000

---

## ✅ Future Improvements

- GUI-based waveform viewer (Tkinter/PyQt)

- Add protocol decoding for SPI, UART, I2C

- Support compressed .vcd.gz files

- Regression comparison between two VCD files

- Export plots as images or interactive HTML

---

## 💻 Technologies Used

- **Language**: Python 3.x
- matplotlib
- argparse, re, itertools

---

## 🧠 Skills Demonstrated
- Python scripting for EDA tools

- Digital waveform parsing and visualization

- CLI-based tool development

- Modular software design

- Signal debugging and post-processing

---

## 📌 Status

✅ In progress 
🚀 Planned completion by [July, 2025].

---


# 🧬 Pairwise Sequence Alignment Tool

A desktop application built in Java (Swing) for pairwise biological sequence alignment using **Needleman-Wunsch** (global) and **Smith-Waterman** (local) algorithms.

---

## ✨ Features

- **Needleman-Wunsch** — global alignment for full sequence comparison
- **Smith-Waterman** — local alignment for finding best local regions
- Supports **DNA**, **RNA**, and **Protein** sequences
- Customizable **match**, **mismatch**, and **gap** scoring
- Live stats: **alignment score**, **identity %**, **gaps**, **mismatches**
- Clean dark-themed UI with block-formatted alignment output

---

## 📸 Screenshot
<img width="1918" height="993" alt="Screenshot 2026-02-25 065929" src="https://github.com/user-attachments/assets/6fa27f69-804a-40e8-b511-b160b350358c" />


<img width="1918" height="993" alt="Screenshot 2026-02-25 065929" src="https://github.com/user-attachments/assets/2061c79e-3a39-4cc9-a9a8-87632e773c3c" />


---

## 🚀 Getting Started

### Prerequisites
- Java 8 or higher

### Run

```bash
# Compile
javac PairwiseAlignmentTool.java

# Run
java PairwiseAlignmentTool
```

---

## 🛠️ How to Use

1. Enter two sequences in the input boxes (e.g. `AGCTGATCG`)
2. Select algorithm: **Needleman-Wunsch** or **Smith-Waterman**
3. Select sequence type: **DNA**, **RNA**, or **Protein**
4. Set scoring parameters (match, mismatch, gap penalties)
5. Click **▶ ALIGN SEQUENCES**
6. View the alignment result and statistics on the right panel

---

## 📐 Algorithms

### Needleman-Wunsch (Global)
Aligns two sequences end-to-end. Best used when sequences are of similar length and expected to be globally similar.

### Smith-Waterman (Local)
Finds the best local alignment between subsequences. Best used when looking for conserved regions within longer sequences.

---

## 📁 Project Structure

```
PairwiseAlignmentTool.java   # Single-file application
README.md
```

---

## 📜 License

MIT License — free to use, modify, and distribute.

---

## 🙌 Contributing

Pull requests are welcome! Feel free to open an issue for bugs or feature requests.

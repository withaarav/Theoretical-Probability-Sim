# 🎲 Theoretical Probability Simulator

> Watch the law of large numbers prove itself — live, in your browser.

Flip a coin. Roll a dice. Run it 10 times, 100 times, 1000 times — and watch how the actual results inch closer and closer to the theoretical probability. This simulator makes that convergence visible.

---

## 🎯 What It Does

The simulator runs repeated trials of two classic probability experiments — a coin flip (expected: 50%) and a dice roll (expected: ~16.7% per face) — and charts how the observed probability moves toward the theoretical value as trials increase.

It's a hands-on demonstration of the **Law of Large Numbers**.

---

## ✨ Features

- 🪙 Coin flip simulation with live probability tracking
- 🎲 Dice roll simulation across all 6 faces
- 📈 Real-time chart showing convergence to theoretical probability
- 🔁 Run as many trials as you want — watch the line flatten out
- 🌐 Runs entirely in the browser — no install needed

---

## 🛠 Tech Stack

| | |
|---|---|
| Language | HTML + JavaScript |
| Rendering | Browser-native Canvas / DOM |
| Math | Vanilla JS probability logic |

---

## 🚀 How to Run

**Option 1 — Direct:**
Download `Theoretical Probability.html` and open it in any browser.

**Option 2 — Live preview:**
Clone the repo and serve it locally:
```bash
git clone https://github.com/withaarav/Theoretical-Probability-Sim.git
cd Theoretical-Probability-Sim
# Open the .html file in your browser
```

No dependencies. No build step. Just open and run.

---

## 🧠 What I Learned

- Simulating randomness and sampling distributions in JavaScript
- Visualizing statistical convergence with live-updating charts
- Understanding why more data = more reliable probability estimates
- Building interactive browser tools without any frameworks

---

## 📐 The Math

For a fair coin: P(heads) = 0.5

For a fair 6-sided die: P(any face) = 1/6 ≈ 0.1667

After enough trials, your observed frequency will approach these values — the simulator shows exactly when and how.

---

## 🔮 What's Next

- [ ] Add more experiments (card draws, Monty Hall problem)
- [ ] Let users set custom probabilities
- [ ] Export results as CSV
- [ ] Add animated step-by-step mode for teaching

---

## 📬 Contact

Made by [Aarav Porwal](https://github.com/withaarav) · with.aarav@gmail.com


# Congkak-intelligent-agent

This project explores the use of artificial intelligence to play Congkak, a traditional board game with a unique simultaneous start phase. It features a Python-based game engine and GUI, along with intelligent agents such as random, maximising, minimax, reinforcement learning, and Q-learning. The system supports experiments like agent tournaments, heuristic training, and payoff matrix analysis to uncover strategies and Nash Equilibria. Designed as both a research tool and educational platform, it offers valuable insights into AI for simultaneous and sequential games.

---

## Project Overview

This project explores the use of AI agents to play Congkak, including:

* Implementation of Congkak game rules with a GUI
* Support for both sequential and simultaneous move modes
* AI agents: Random, Maximising, Minimax with Alpha-Beta Pruning, Reinforcement Learning, Q-Learning
* Mixed Strategy Nash Equilibrium analysis via brute force
* Built-in training and evaluation tools

---

## How to Run

### Run the Application

To launch the GUI application:

```
Executable/Congkak Experimenter
```

> ⚠️ Only available for systems supporting PyQt6 executable builds.

### Run from Source Code

1. Make sure you have Python 3 installed.
2. Install required dependencies (you can use `pip install -r requirements.txt` if provided).
3. Run the main script:

```
cd FinalYearProject
python main.py
```

---

## Files

* `Executable/` – Contains the prebuilt GUI application (`Congkak Experimenter`)
* `FinalYearProject/` – Contains the full source code
* `moves.txt` – Stores saved move history from previous sessions

---

## Features

* **Human vs Human**, **Human vs AI**, or **AI vs AI**
* Round-robin tournaments for agent evaluation
* Train RL and Q-learning agents
* Brute-force analysis of opening strategies
* Modify evaluation function weights for minimax agents
* Export and view past game moves

---

## User Interface

The application includes a visual representation of the Congkak board with:

* Menus to control game setup, training, saving/loading, and view options
* Tools to adjust game parameters and agents
* Graphical feedback of agent actions and outcomes

---

## ❓ FAQ

**Q: When I close the program, the terminal is still active. Is this normal?**
A: Yes, this is normal. If the program encounters any error, the terminal remains open to display the error message.

**Q: The program crashed and the terminal closed before I could read the error. What can I do?**
A: This may be due to exit code `0xC0000374`, a known issue related to multithreading in PyQt. It is hard to reproduce consistently. To minimize this, we recommend disabling `Update Graphics` in the **View** menu.

---

## Contributing

Contributions are welcome. If you would like to contribute, please fork the repository and submit a pull request. For major changes, open an issue first to discuss the proposal.

---

## Credits

This project was developed as part of a Final Year Project (FYP).

**Student Developer:** Nik Abdul Muhaimin

---

## License

This project is licensed under the **Apache License 2.0**. See the [LICENSE](LICENSE) file for full terms and conditions.

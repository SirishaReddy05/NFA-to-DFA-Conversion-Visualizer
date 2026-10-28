# AutomataCraft: NFA to DFA Visualizer

AutomataCraft is an interactive, educational web application designed to help students and developers visualize the complex process of converting a Non-deterministic Finite Automaton (NFA) into a Deterministic Finite Automaton (DFA) using the Subset Construction algorithm.

🚀 Features

Visual NFA Builder: Define states, alphabets, start/accept states, and transitions (including epsilon/ε transitions) using a clean, intuitive interface.

Automated Subset Construction: Converts your NFA to a DFA instantly, calculating all ε-closures and transition mappings.

Interactive D3.js Graphs: View visually stunning, draggable, and zoomable node-link diagrams for both the original NFA and the generated DFA side-by-side.

Step-by-Step Logging: Inspect a detailed text log of the mathematical subset construction process, showing exactly how the algorithm groups states together.

Live String Simulation: Enter an input string and step through the execution frame-by-frame, watching the active states highlight dynamically on both the NFA and DFA graphs simultaneously.

🛠️ Tech Stack

Frontend: HTML5, Vanilla JavaScript

Styling: Tailwind CSS (via CDN) for modern, responsive UI design

Data Visualization: D3.js (v7) with a custom physics simulation for rendering the state machines

Architecture: Zero-dependency, single-file application for maximum portability and ease of use.

📚 Theory of Computation Concepts Demonstrated

This project serves as a dynamic sandbox for core theoretical computer science concepts:

Non-determinism vs. Determinism: Visualizing how multiple active states in an NFA collapse into a single composite state in a DFA.

Epsilon (ε) Closures: Demonstrating how state boundaries expand without consuming input symbols.

Subset Construction Algorithm: Providing a transparent, mathematical mapping from NFA subsets to DFA states.

String Acceptance: Simulating the exact path a machine takes to either accept or reject a given input string.


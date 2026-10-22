# nfa-to-dfa-java-converter
# NFA to DFA Converter in Java

This repository contains a Java implementation that converts a Non-Deterministic Finite Automaton (NFA) into an equivalent Deterministic Finite Automaton (DFA) using the **Subset Construction method**.

## 🚀 Features
- **Transition Mapping:** Defines NFA state transitions using HashMaps.
- **Subset Construction:** Automatically processes state sets and maps input symbols (0 and 1) to determine new DFA states.
- **Dead State Handling:** Explicitly handles missing transitions by assigning a "Dead State" to preserve determinism.
- **Output Generation:** Displays the generated DFA transition table and identifies accepting (final) states.

## 🛠️ Technologies & Tools
- **Language:** Java
- **Environment:** Compatible with OnlineGDB, Eclipse, IntelliJ IDEA, or VS Code

## 💻 How to Run
1. Clone or download the repository.
2. Open `Main.java` (or your Java file name) in any Java-supported IDE or online editor.
3. Compile and run the code to view the NFA to DFA conversion output.

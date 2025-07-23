

# **Adventure Game Engine**

*A text-based adventure game built with Java, following the MVC design pattern*

## **Overview**

This project is a modular, text-based adventure game engine designed using the **Model-View-Controller (MVC)** paradigm. It supports dynamic game states through JSON-based configuration and save/load functionality.

The game engine allows players to explore rooms, interact with puzzles and items, and battle monsters, with game progression governed by stateful rules and validations.

---

## **Key Features**

* **MVC Architecture**

  * `GameController` handles control flow and user input.
  * `GameModel` manages state (Player, Rooms, Items, Monsters).
  * `GameView` displays dynamic game output.
* **Dynamic Data Handling**

  * JSON parsing for configurable game data and save/load support.
  * Modular architecture for extendable game elements (Rooms, Puzzles, Items, Monsters).
* **Robust Game Logic**

  * Exception handling for invalid actions and state-based rule enforcement.
  * End conditions for game completion, player death, or quitting.

---

## **Tech Stack**

* **Languages:** Java
* **Libraries:** Gson (JSON Parsing)
* **Version Control:** Git (feature-branch workflow)

---

## **Collaboration & Workflow**

* **Team Members:**

  * **Rohan Kumar** 
  * **Daniel Jilek**
  * **Max Zhou**
  * **Tim Jaung**
* **Git Workflow:**

  * `main` branch for production-ready builds.
  * `dev` branch for active development.
  * Feature branches for new additions with peer-reviewed pull requests.

---

## **How to Run**

1. Place the required JSON file in `src/resources/`.
2. Run the `Main` class in `src/`.
3. Save files will be created and stored in `src/resources/`.

---

## **Diagrams & Documentation**

* High-level design diagrams are available in `/Diagrams`.
* Required `.jar` files are provided in `/Library`.





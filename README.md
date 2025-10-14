# Python Programming Lab Exercises
# Teaching Python Programming — A Reflective Learning Portfolio

> A hybrid project where I re-learn Python from a teacher’s perspective — combining code, pedagogy, and reflection.  
> This repository documents not only how Python works, but how *understanding* develops through the process of teaching it.

---

## Vision

When I first learned Python, I could make things work — but I rarely understood *why* they worked.  
Years later, preparing to teach programming has become a mirror: I’m re-learning each concept to explain it clearly, and in doing so, discovering the invisible logic behind it.

This repository grows at the intersection of three dimensions:

1. **Coding practice** — reproducible examples and modular exercises  
2. **Teaching design** — how to structure explanations and anticipate misconceptions  
3. **Reflective thinking** — capturing the “I thought I knew, but I didn’t” moments that shape deeper understanding

---


**File Descriptions:**

* `teaching_thoughts.md`: Course design logic and teaching intentions.
* `reflection.md`: Personal and pedagogical reflections.
* `code_demo.ipynb`: Executable, annotated notebook.

---

## Getting Started

1.  **Clone the repository**

    ```bash
    git clone [https://github.com/JiashuoZh/teaching-python-programming.git](https://github.com/JiashuoZh/teaching-python-programming.git)
    cd teaching-python-programming
    ```

2.  **Create and activate an environment** (Anaconda recommended)

    ```bash
    conda create -n teach_py python=3.10
    conda activate teach_py
    ```

3.  **Install essentials** (if needed)

    ```bash
    pip install jupyter matplotlib pandas
    ```

4.  **Open a notebook**

    ```bash
    jupyter notebook 01_basics/code_demo.ipynb
    ```

> *Run cell by cell, observing both the outputs and the reasoning behind them.*

---

## Pedagogical Approach

This project treats programming as a **cognitive apprenticeship** — where visible code is only the surface of an invisible reasoning process.

* **Make logic visible.** Use prints/plots/turtle to visualize state and flow.
* **Embrace confusion.** “I think I understand but I’m not sure” is a productive signal.
* **Bridge syntax to thought.** Map instructions to mental models and problem-solving.
* **Reflect while coding.** Coding and reflection form one loop.

---

## Example Modules

| Module | Core Focus | Pedagogical Lens | Extension Idea |
| :--- | :--- | :--- | :--- |
| **01\_basics** | Environment; interpreter vs. PATH | Understanding *why* code runs | Visualize the interpreter/bytecode pipeline |
| **02\_turtle** | Graphics; procedural abstraction | Making logic visible through movement | Parameterization; modular drawing functions |
| **03\_data\_types** | Data types and expressions | “Value vs. reference” mental models | Debugging mini-tasks; numeric precision cues |
| **04\_files\_exceptions** | I/O and error handling | Learning through failure and recovery | File-based mini-projects; log parsing exercises |

---

## Sample Reflection Excerpt

> “When I first learned HTML, every tag instantly showed a result.
> Python, by contrast, often feels invisible — code runs in silence until something goes wrong.
> Teaching it now, I realize that this **silence** is part of its depth: Python trains the imagination of invisible processes.”
> (from `01_basics/reflection.md`)

---

## Future Plans

* Extend toward **data analysis**, **algorithms**, and **machine learning**
* Add automated feedback (`pytest`, `nbgrader`) for teaching use
* Publish selected reflections as short essays on computing literacy
* Connect modules with potential **CS-education research** topics

---

## Author

**Jiashuo Zhang** — College instructor and reflective learner.

Exploring how programming can be taught not as mere syntax, but as a language of thought.

* **GitHub**: [https://github.com/JiashuoZh](https://github.com/JiashuoZh)
* **Email/LinkedIn**: (optional)

---

## License

All source code and teaching materials are released under the **MIT License**.

Please attribute this repository when reusing teaching designs or reflection texts.





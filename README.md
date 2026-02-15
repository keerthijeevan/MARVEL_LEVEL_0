# TASK 4: Working with the Command Line on Ubuntu

## Introduction

In this task, I learned a few Ubuntu commands such as pwd, mkdir, cd, ls, cat, touch, which are used to: in this paragraph if you want you can extra line but do not change anything next line.

These commands help users navigate directories, create files and folders, manage file systems, and work efficiently using the terminal interface without a graphical environment.

---

## Commands Used

| Command | Purpose |
|---------|---------|
| mkdir test | Create a folder named test |
| cd test | Enter folder |
| touch blank.txt | Create empty file |
| ls | List files |
| mkdir M{0001..2600} | Create 2600 folders |
| cat file1.txt file2.txt | Concatenate files |

---

## Steps Performed

1. Created a new directory named **test** using the `mkdir` command.
2. Navigated into the directory using `cd`.
3. Created a blank file without using any text editor using the `touch` command.
4. Listed files using the `ls` command.
5. Generated 2600 folders using brace expansion in Ubuntu terminal. by using `mkdir M{0001..2600}` the command 
6. Concatenated two text files using the `cat` command and displayed the output in the terminal.

---

## Screenshot of Execution

---

<img width="1016" height="582" alt="Screenshot 2026-02-15 125444" src="https://github.com/user-attachments/assets/076e73b7-b685-4717-bfcb-aa416cbeba51" />

---

# TASK 3: Working with GitHub

## Introduction

GitHub is a collaborative platform for version control and project hosting. It is a very great place to work and collaborate on a project or any work.

Here I have forked a repository and after correcting the code I have send pull request to the main branch in repository.

In this task, I learned about the working of GitHub, such as how to create a fork, which essentially means creating a personal copy of a repository, and about pull requests (PR), a feature used to propose changes made in someone else’s repository so that they can review and merge it into the main branch.

---

## Steps Performed

- Opened the given GitHub repository.
- Forked the repository to create a personal copy.
- Cloned the forked repository into local system (optional step if you did).
- Made necessary code corrections/changes.
- Committed the changes.
- Pushed changes to forked repository.
- Created a Pull Request (PR) to the main/original repository.
- Submitted PR for review and merge.

---
<img width="1919" height="1075" alt="Screenshot 2026-02-13 221654" src="https://github.com/user-attachments/assets/3a6e34b4-ee18-4218-aad2-b23a2f9b4022" />

---

## GitHub Repository Link

👉 [Click here to view my GitHub Task Repository](https://github.com/UVCE-Marvel/git-task/pull/245)

---

# TASK 1: 3D Printing

## Introduction

3D printing is an additive manufacturing process where 3D objects are created layer by layer based on a digital model or code. So basically I tried to understand the entire workflow of the printer.

---

## Concepts Learned

- **STL File:** This is the standard file format for 3D printing. I downloaded one from Thingiverse.

- **Slicing:** Before printing, the STL file is processed in slicer software like Cura converting it to G-CODE.

- **Printing Speed:**
  - For better results: keep speed ≤ 55 mm/s.
  - Helps achieve great surface resolution.

---

## Post-Printing Procedures

- **Joining 3D Printed Parts**
  - Use cyanoacrylate glue (superglue) or two-stage epoxies for PLA parts.

- **Painting**
  - Almost all 3D printed parts can be painted (except Nylon and PETG).

- **Sanding**
  - Use progressively finer sandpaper for smooth surface finishes.
  - Sand slowly to avoid breaking parts or melting due to friction.
  ---  
![IMG-20260215-WA0011](https://github.com/user-attachments/assets/2011dea7-1d7f-4223-be6a-18a4b43847e4)

---

# TASK 12: Soldering Prerequisites

## Introduction

Soldering refers to the process of joining metal parts together using a filler material called solder, which has a low melting point. The solder is heated until it liquefies, allowing it to flow over the surfaces and create a connection when it cools and hardens.

---

## Concepts Learned

- Understanding the basics of soldering.
- Learning about soldering tools and safety precautions.
- Proper heating techniques for strong connections.
- Importance of clean surfaces before soldering.
- Maintaining correct temperature during soldering.

---

## Practical Understanding

- Observed the solder melting and flowing over metal surfaces.
- Understood how cooling forms a solid electrical and mechanical connection.
- Learned about careful handling of soldering iron.

---

![IMG-20260215-WA0010](https://github.com/user-attachments/assets/f91ea95a-ae04-402d-93a5-36f128023bc1)

![IMG-20260215-WA0009](https://github.com/user-attachments/assets/8b4fdb49-80e3-4387-a8f6-44539d048110)

---

# TASK 14: Karnaugh Maps and Deriving the Logic Circuit

## Introduction

A Karnaugh map (K-map) is a visual technique used in digital logic design and Boolean algebra to simplify logical expressions and reduce the number of logic gates needed for implementing a digital circuit.

This task focuses on a Burglar Alarm system that identifies unauthorized access when the gate is open while the key remains unpressed.

---

## Concepts Learned

- Understanding Boolean algebra simplification using Karnaugh Maps (K-maps).
- Mapping truth table values into K-map cells.
- Grouping adjacent cells to simplify logical expressions.
- Reducing the number of logic gates for efficient circuit design.
- Deriving simplified Boolean expressions from K-map.

---

## System Description (Burglar Alarm)

- The system monitors the condition of a gate and a key.
- Alarm is triggered when:
  - Gate is open.
  - Key remains unpressed.
- Logical conditions were analyzed and simplified using Karnaugh Map techniques.

---

## Learning Outcomes

- Improved understanding of digital logic simplification.
- Practical application of K-map in real-world problem (alarm system).
- Visualization of logic minimization process.

---
![kmap](https://github.com/user-attachments/assets/4ea24771-8921-45cd-bd98-58e8b6f8bc5a)

---

# TASK 6: The Matrix Puzzle — Decode with NumPy & Reveal the Image

## Introduction

Get hands-on with NumPy and Matplotlib by solving a visual puzzle. In this task, a scrambled matrix was provided, and the goal was to decode it into a hidden image using NumPy operations and visualization techniques.

---

## Steps Performed

- Started by loading the scrambled matrix from the given `.npy` file using NumPy’s `np.load()` function.
- Checked the array’s shape and counted the total elements to decide the correct square dimensions for reshaping.
- Reshaped the array into a 2D square matrix of size **100×100**.
- Observed that the image orientation was incorrect after reshaping.
- Used `np.rot90()` with `k = -1` to rotate the matrix **90 degrees clockwise**.
- Displayed the decoded image using `matplotlib.pyplot.imshow()`.

---

## Learning Outcome

- Practical understanding of NumPy array manipulation.
- Experience in reshaping matrices and image transformation.
- Visualization of data using Matplotlib.
- Successfully decoded and revealed the hidden image.

---
<img width="440" height="424" alt="Task-6" src="https://github.com/user-attachments/assets/86030ed7-a017-4486-9646-05a26c1b7161" />

---
# TASK 20: Notebook Ninja – Getting Started with Jupyter

## Introduction

Familiarize yourself with Jupyter Notebook as a tool for both coding and communication. This task is designed to build confidence in writing clean, readable, and well-structured notebooks using both code and Markdown.

---

## Concepts Learned

- Understanding the Jupyter Notebook interface.
- Using code cells to write and execute programs.
- Using Markdown cells for documentation and explanations.
- Combining code and text for better communication.
- Organizing notebooks in a clean and structured way.

---

## Practical Experience

- Created and worked with Jupyter Notebook files.
- Practiced writing formatted text using Markdown.
- Executed code step-by-step within notebook cells.
- Learned how to present results clearly inside notebooks.

---

## Jupyter Notebook Link

👉 [Click here to view the Jupyter Notebook](https://github.com/keerthijeevan/jupyter_notebook/blob/master/marvel.ipynb)

---















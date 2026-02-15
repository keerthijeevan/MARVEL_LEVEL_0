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
# TASK 18: Sad Servers - "Like LeetCode for Linux"

## Introduction

Sadservers is a platform designed to practice and improve Linux troubleshooting skills. In this task, we explored a murder mystery located in the Clmystery directory and recorded the suspect’s name in the mysolution file.

---

## Commands Used

- `cd [directory_path]`
- `ls [options] [directory_path]`
- `cat [options] [file_name]`
- `grep [options] "pattern" [file_name]`

---

## Practical Experience

- Navigated through directories using Linux commands.
- Listed files and explored folder contents.
- Read file data to analyze clues.
- Used pattern searching to identify the suspect.

---
<img width="1920" height="1080" alt="Screenshot (24)" src="https://github.com/user-attachments/assets/f1f98c01-a160-4c91-8b1f-b246d2e188c7" />

---

# TASK 15: Active Participation

## Introduction

I participated in the event CODEATHON, conducted during the International-Level Annual Technical Symposium, Phase Shift 2024, held at BMSCE on December 5th and 6th, 2024.

---

## Experience

- Participated actively in the CODEATHON event.
- Engaged in technical challenges and collaborative problem-solving.
- Gained exposure to competitive programming and innovation-focused activities.
- Interacted with participants from different backgrounds and enhanced learning experience.

---

<img width="1536" height="1024" alt="ChatGPT Image Feb 15, 2026, 05_07_23 AM" src="https://github.com/user-attachments/assets/35c8917a-54cd-4da4-ad1f-9ed7e5b80433" />

---
# TASK 8: Writing a Resource Article Using Markdown

Markdown is a lightweight markup language used to format text using simple syntax.  
It allows users to create structured documents with headings, lists, links, and images easily.  
Markdown is widely used in GitHub, documentation, and technical writing.  
It helps convert plain text into clean and readable formatted content.  
Markdown files are usually saved with the `.md` extension.

---

## Resource Link for my article 

👉 [Click Here](https://keerthijeevan.github.io/index.md/)

---
# TASK 5: Linear Regression

## Introduction

Linear Regression is a supervised machine learning algorithm used to model the relationship between input features and a continuous output variable. It works by fitting a straight line (best-fit line) through data points to predict values.

---

## Concepts Learned

- Understanding supervised learning.
- Difference between regression and classification.
- Linear relationship between variables.
- Concept of best-fit line.
- Error function and loss minimization.

---

## Steps Performed

- Loaded dataset and explored input features.
- Implemented linear regression without using machine learning libraries.
- Calculated slope and intercept for best-fit line.
- Predicted output values.
- Visualized results using graphs.

---

## Learning Outcome

- Practical understanding of regression models.
- Implemented algorithm using mathematical concepts.
- Visualized prediction results.
---
##  housing price vs feature
<img width="1918" height="1072" alt="Screenshot 2026-02-13 185908" src="https://github.com/user-attachments/assets/ede04af6-52ce-43f2-9eba-7871ab27e848" />

---
## Maths beyond the linear regresion
<img width="1536" height="1024" alt="Linear regression handwritten notes" src="https://github.com/user-attachments/assets/7aeaa08f-4573-4997-9487-b1160e05a327" />
---

# TASK 10: Speed Control of DC Motor

## Introduction

In this experiment, a DC motor was controlled using an Arduino UNO and the L298N H-bridge motor driver. The motor’s speed was varied through PWM signals sent from the Arduino, while the direction was controlled using digital pins.

---

## Components Used

- Arduino UNO
- L298N Motor Driver
- Arduino IDE
- VRPS

---

## Working Principle

- PWM (Pulse Width Modulation) signals were used to control the speed of the DC motor.
- Digital pins were used to change the rotation direction.
- The L298N motor driver acted as an interface between Arduino and the motor.

---

## Learning Outcome

- Understanding of motor speed control using PWM.
- Practical experience with Arduino motor control.
- Learning about H-bridge motor driver functionality.
---
<img width="1003" height="566" alt="Screenshot 2026-02-15 160112" src="https://github.com/user-attachments/assets/9667a916-0882-438e-928d-083f9e5e9912" />

---

# TASK 9: Tinkercad Project

This task focuses on detecting unknown objects using an ultrasonic sensor, a servo motor, and an Arduino Uno board.

---

## Components Used

### Ultrasonic Sensor
The ultrasonic sensor has two main parts: a transmitter and a receiver. The transmitter emits sound waves that travel through the air and reflect back when they hit an object. The receiver detects the returning echo signal.

### Servo Motor
The servo motor rotates the ultrasonic sensor through an angle of 180°, allowing the system to scan a wider area.

### Arduino Uno
The Arduino Uno acts as the main controller of the system and performs the following operations:

- Sends a trigger signal to activate the ultrasonic sensor.
- Calculates the distance based on the time taken for the echo to return.
- Rotates the servo motor step-by-step from 0° to 180°.
- Sends the calculated distance values to the Serial Monitor.

Without the Arduino, the ultrasonic sensor and servo motor cannot function together as a complete system.

---

<img width="999" height="690" alt="Screenshot 2026-02-15 163008" src="https://github.com/user-attachments/assets/8713852d-88a2-4c11-a601-5531d656e34e" />

---

# TASK 11: LED Toggle Using ESP32

## Introduction

In this task, we used an ESP32 microcontroller to create a standalone web server using the Arduino IDE. The ESP32 connects to a Wi-Fi network and hosts a webpage with LED ON/OFF buttons. Clicking these buttons sends HTTP requests to the ESP32, which controls the LEDs connected to its GPIO pins.

---

## Connections

- ESP32 GPIO pin connected to LED (through resistor).
- LED cathode connected to GND.
- ESP32 powered via USB.
- Wi-Fi connection configured inside Arduino IDE.

---

## Working Principle

- ESP32 connects to Wi-Fi network.
- Hosts a local web server.
- Webpage contains ON/OFF buttons.
- Button click sends HTTP request.
- ESP32 reads request and toggles LED state.

---

![IMG-20260215-WA0021](https://github.com/user-attachments/assets/78ad9022-ebe7-431f-a063-91f08abbd5d8)

---

# TASK 7: Create a Portfolio Webpage

## Introduction

A portfolio is a collection of your work, skills, and achievements that showcases your abilities to potential employers, clients, or collaborators. In this task, I created my personal portfolio using HTML and CSS.

---

## Features of the Portfolio

- About Me section containing personal introduction.
- Education details.
- Hobbies and interests.
- Skills section highlighting technical abilities.
- Social media links.
- Responsive layout using HTML and CSS styling.

---

## Learning Outcomes

- Understanding basic webpage structure using HTML.
- Styling webpages using CSS.
- Creating navigation sections.
- Designing a simple personal portfolio layout.

---

## Portfolio Link

👉 [Click here to view my portfolio code](https://github.com/keerthijeevan/onepiece/blob/421a07542581cc7c4be0148293fe5a051a8a4776/jeevan.html)

---








  























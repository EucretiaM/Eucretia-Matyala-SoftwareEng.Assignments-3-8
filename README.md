Assignment 8 outlines the Object State Modeling and Activity Workflow Modeling of the Math Booster App in line with the functional requirements of the system available in [assignment 4](https://github.com/EucretiaM/EucretiaM-Matyala-Assignment-4)
Use Cases as well in [assignment 5](https://github.com/EucretiaM/EucretiaM-Matyala-Assignment-5)
and user stories and sprint tasks available in [assignment 6](https://github.com/EucretiaM/EucretiaM-Matyala-Assignment-6)
Objective
Here is a link to the State Transition diagram and explanations
(https://github.com/EucretiaM/Eucretia-Matyala-SoftwareEng.Assignments-3-8/tree/main/Assignment-8-only/Assignment-8-State%20Transition%20Diagrams)

##  **State Diagrams**  
**Purpose:** Show how an object changes state based on events.  
**Use:** For features with status changes (e.g., quiz session, user login).  
**Key Parts:**  
- **States** (e.g., In Progress, Submitted)  
- **Events** trigger transitions  

** Example – Math Booster (Quiz Session):**  
```
[Idle] → (startQuiz) → [In Progress] → (submit) → [Submitted] → (viewResults) → [Completed]
```
##  **Activity Diagrams**  
**Purpose:** Show the workflow or sequence of steps in a process.  
**Use:** To describe how a feature works from start to finish.  
**Key Parts:**  
- **Activities**, **decisions**, **start/end nodes**

** Example – Math Booster (Taking a Quiz):**  
```
Start → Display Quiz → Receive Answers → Validate → Store Results → Show Score → End
```
## 📌 How They Relate to Functional Requirements:  
- **State diagrams** model object behavior (e.g., user session, quiz state).  
- **Activity diagrams** model process flow (e.g., how a quiz is taken).  

#  Reflection: Assignment 8 – State and Activity Modeling

Assignment 8 focused on Object State Modeling and Activity Workflow Modeling of the **Math Booster App**, aligning with the system's functional requirements documented in:

- [Assignment 4 – Functional Requirements](https://github.com/EucretiaM/EucretiaM-Matyala-Assignment-4)  
- [Assignment 5 – Use Cases](https://github.com/EucretiaM/EucretiaM-Matyala-Assignment-5)  
- [Assignment 6 – User Stories & Sprint Tasks](https://github.com/EucretiaM/EucretiaM-Matyala-Assignment-6)

The main objective was to understand and illustrate how the system behaves internally (via **state diagrams**) and how workflows operate (via **activity diagrams**) for selected features in the app.

##  State Diagrams

**Purpose:**  
State diagrams are used to show how an object transitions between different states in response to events. They are particularly useful for features that involve status changes.

**Use in Math Booster:**  
One key application is modeling the behavior of a **Quiz Session** as it progresses through various stages.

**Key Concepts:**
- **States:** Represent the condition of the object at a given time (e.g., `In Progress`, `Submitted`)  
- **Events:** Trigger transitions between states (e.g., `startQuiz`, `submit`)  

**Example – Quiz Session Flow:**
```
[Idle] → (startQuiz) → [In Progress] → (submit) → [Submitted] → (viewResults) → [Completed]
```

##  Activity Diagrams

**Purpose:**  
Activity diagrams illustrate the flow of actions and decisions in a process. They are ideal for mapping out how a specific functionality is executed from beginning to end.

**Use in Math Booster:**  
Used to describe how a learner completes a quiz, from initiation to result viewing.

**Key Concepts:**
- **Activities:** Tasks or actions performed (e.g., `Display Quiz`, `Validate`)  
- **Decisions:** Points where the flow may branch based on conditions  
- **Start/End Nodes:** Represent the entry and exit points of the process  

**Example – Taking a Quiz:**
```
Start → Display Quiz → Receive Answers → Validate → Store Results → Show Score → End
```

##  Relationship to Functional Requirements

Both modeling approaches directly support the functional needs of the Math Booster app:

- **State Diagrams** provide clarity on how system objects behave in response to user interactions or system events.  
- **Activity Diagrams** clearly describe the end-to-end workflow of user actions within the app.

By referencing previous assignments, these models help ensure consistency between design, development, and implementation phases.

## 🔗 State Diagram Link
For visual references and additional explanations, see the diagrams here:  
[State Transition Diagrams – Assignment 8](https://github.com/EucretiaM/Eucretia-Matyala-SoftwareEng.Assignments-3-8/tree/main/Assignment-8-only/Assignment-8-State%20Transition%20Diagrams)

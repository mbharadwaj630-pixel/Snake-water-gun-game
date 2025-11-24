# Requirements for Snake Water Gun Game (Python Project)

## 1. Functional Requirements

### 1.1 User Input
- The system must allow the user to enter one of the following:
  - `s` for Snake
  - `w` for Water
  - `g` for Gun

### 1.2 Computer Move
- The computer must randomly choose one option from:
  - Snake (`s`)
  - Water (`w`)
  - Gun (`g`)

### 1.3 Result Logic
- The game must determine the winner using predefined rules:
  - Snake defeats Water
  - Water defeats Gun
  - Gun defeats Snake
  - Same choices result in a draw

### 1.4 Output Display
- The system must display:
  - The computer’s choice  
  - Whether the user wins, loses, or draws  
  - Relevant explanation message  

---

## 2. Non-Functional Requirements

### 2.1 Usability
- The interface must be simple and text based.
- Instructions must be easy to understand for beginners.

### 2.2 Performance
- The game must generate results instantly.
- No noticeable delay in processing input or showing output.

### 2.3 Reliability
- The random choice generator must function correctly on every run.
- Invalid inputs must be handled gracefully.

### 2.4 Portability
- The project must run on any system where Python 3 is installed.
- No additional libraries should be required.

---

## 3. System Requirements

### 3.1 Software Requirements
- Python 3.x  
- OS compatibility:
  - Windows
  - macOS
  - Linux

### 3.2 Hardware Requirements
- Any basic computer that can run Python
- Minimum:
  - 1 GB RAM
  - 500 MB free storage

---

## 4. Constraints
- Must be console based only (no GUI required)
- Only Python built in modules allowed (e.g., `random`)
- No external APIs or internet access needed

---

## 5. Assumptions
- The user understands basic English instructions.
- The user has Python installed and knows how to run a `.py` file.
- The user will provide valid inputs (`s`, `w`, `g`).

---

## 6. Dependencies
- Python’s built in `random` module (no external dependencies)

--
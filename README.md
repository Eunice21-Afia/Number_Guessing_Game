

### **Number Guessing Game**  
**A Python-based interactive game to guess a randomly generated number.**  

- **Technologies Used**: Python (Core libraries for logic and random number generation).  

---

#### **Key Features**  
- **Limited Attempts**: Players have 5 chances to guess the correct number.  
- **Dynamic Feedback**:  
  - "Too low!" if the guess is less than the secret number.  
  - "Too high!" if the guess exceeds the secret number.  
  - "Congratulations!" when the correct number is guessed.  
- **Attempt Tracking**: Displays the number of remaining attempts after each guess.  
- **Replay Option**: Prompts players to play again or exit after a game ends.  
- **Correct Answer Display**: Reveals the number if the player exhausts all attempts.  

---

#### **How to Play**  
1. The program selects a random number between 1 and 100.  
2. Players are prompted to guess the number.  
3. The program provides feedback on each guess (too high, too low, or correct).  
4. Players have 5 attempts to guess correctly.  
5. If unsuccessful, the correct number is displayed, and players can replay or quit.  

---

#### **Requirements**  
- Python 3.x  

---

#### **How to Run the Game**  
1. Clone or download the repository.  
2. Navigate to the project folder.  
3. Run the following command in your terminal:  
   ```bash  
   python number_guessing.py  
   ```  
4. Follow the on-screen instructions to enjoy the game!  

---

#### **Customization Options**  
- **Adjust Number of Attempts**: Modify the `max_attempts` variable in the code to allow more or fewer attempts.  
- **Change Number Range**: Edit the `random.randint(1, 100)` part of the code to customize the range.  

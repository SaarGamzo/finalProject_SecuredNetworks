1. **Prerequisites**:
    - **Node.js**: https://nodejs.org/en/download/package-manager
    - **Python**: https://www.python.org/downloads/
    - **MySQLServer**: https://dev.mysql.com/downloads/mysql/
  
2. **RUN MySQL Server**:
    - **Download project zip & extract all code**
    - **On visual studio code - click file -> open folder -> select root directory of the project**
    - **Open cmd on windows - run the commands**:
      - ```mysql -u root -p```
      - Insert your root password
      - ```CREATE DATABASE store;```

3. **Install needed dependencies**:
    - On new terminal run the following commands:
      - ``` npm install``` - to install every nodejs dependency
      - ``` pip install -r requirements.txt``` - to install every python dependency

4. **Update MySql password if needed**:
    - Open file src/back/config.py and replace ```A123456``` with your root password on MySQL.

5. **SETTING .env variables as wanted**:
    - **GMAIL_USER & GMAIL_PASS** are needed in order to send OTP messages on email
    - **SAFE_MODE (true/false)** - true = safe from sqli attacks, false = not safe from sqli attacks
    - **NEXT_PUBLIC_SAFE_MODE (true/false)** - true = safe from xss stored attacks, false = not safe from xss stored attacks 

6. **Running the project**:
    - Split the terminal to 2 terminals
    - On the first terminal - run the command: ```python src/back/main.py``` and verify the server is running as expected
    - On the second terminal - run the command: ```npm run dev``` and verify the frontend is running as expected
    - Press ctrl + click on the URL: ```http://localhost:3000```

7. **Screen Shots**:
![image](https://github.com/user-attachments/assets/44852f18-7457-468d-97be-1a1aedf0a327)

![image](https://github.com/user-attachments/assets/c536e8e9-c330-426a-a2a1-7e14618b8675)

![image](https://github.com/user-attachments/assets/df88bbff-5c34-43cf-9f1a-52210350da11)

![image](https://github.com/user-attachments/assets/874a4e56-6870-4339-9755-9dcc2da0a526)

![image](https://github.com/user-attachments/assets/bd92efb4-1f3c-49e4-8ea8-79f326720b82)

![image](https://github.com/user-attachments/assets/20e82d80-ba5a-4636-9256-c0a3b81fe085)


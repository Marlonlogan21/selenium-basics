# Basic Selenium Test – Wikipedia Homepage

## 📌 Project Overview
This project demonstrates the basics of browser automation using **Selenium WebDriver** with Python.  
The script:
1. Launches Google Chrome
2. Navigates to **[Wikipedia.org](https://www.wikipedia.org)**
3. Validates that the page title contains **"Wikipedia"**
4. Takes a screenshot of the homepage
5. Closes the browser

---

## 🛠 Tools & Environment
- **Python 3.x**
- **Selenium WebDriver**
- **Google Chrome** (latest version)
- **ChromeDriver** (handled automatically by Selenium Manager)
- **MacOS** with VS Code as the IDE

---

## 📂 Project Files
- **basic_selenium_test.py** – Main Selenium automation script
- **homepage.png** – Screenshot captured during execution (linked below)
- **README.md** – Project documentation

---

## 📜 How to Run the Script
1. **Clone or download** this repository to your local machine.
2. Open a terminal in the project folder and install Selenium:
   ```bash
   pip install selenium
Run the script:

bash
Copy
Edit
python basic_selenium_test.py
After execution:

You should see "Test passed ✅" in the terminal.

The screenshot will be saved as homepage.png.

🧠 How the Script Works: 

Launch Chrome: Uses webdriver.Chrome() to start the browser.

Navigate: Goes to https://www.wikipedia.org.

Validate Title: Checks if "Wikipedia" is in the browser title.

Take Screenshot: Saves a PNG image of the homepage.

Close Browser: Ends the automation session with quit().

🚧 Challenges Faced
Ensuring the correct ChromeDriver version was used.

Allowing Selenium Manager to automatically fetch the correct driver.

Managing browser permissions on MacOS.

✅ Test Result
Status: PASSED

Screenshot saved successfully.










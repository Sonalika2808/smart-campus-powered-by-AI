<p align="center">
  <img src="./img.png" alt="Project Banner" width="100%">
</p>

# Smart Campus powered by AI🎯

## Student friendly app

### Team Name: hacktech

### Team Members
- Member 1: M.Sonalika - College of Engineering Munnar
- Member 2: Akshaya.S - College of Engineering Munnar

### Hosted Project Link
https://github.com/Sonalika2808/smart-campus-powered-by-AI/edit/main/README.md

### Project Description
The Smart Campus Issue Reporter is an AI-based web application designed to simplify and modernize the process of reporting and managing campus-related issues. In many institutions, problems such as damaged infrastructure, electrical faults, water leakage, and cleanliness concerns are often reported manually, leading to delays and lack of transparency. This system provides a digital platform where students can submit complaints through text or images, which are then automatically analyzed and categorized using artificial intelligence. The admin dashboard enables authorities to monitor, assign, and update the status of each issue in real time. By improving efficiency, ensuring accountability, and enabling faster resolution, the Smart Campus Issue Reporter contributes to a more organized, responsive, and technology-driven campus environment.

### The Problem statement
Campuses often rely on manual complaint systems that are slow, unorganized, and lack transparency. Students cannot easily track issues, and delays in resolution affect campus efficiency. There is a need for a smart, centralized system to streamline and monitor issue reporting effectively.

### The Solution
The Smart Campus powered by AI is a web-based AI-powered system that allows students to digitally report campus issues through text or images. The system automatically categorizes complaints, assigns priority, and enables real-time tracking through an admin dashboard. This ensures faster resolution, transparency, and efficient campus management.

### Technologies/Components Used

**For Software:**
- Languages used: JavaScript, Python, CSS3,HTML5,SQL
- Frameworks used:Django,Frontend ,Bootstrap
- Libraries used: Pandas ,NumPy ,Scikit-learn ,NLTK ,OpenCV 
- Tools used:VS Code, Git, Docker

## Features

List the key features of your project:
Feature 1: Smart Complaint Submission
Feature 2: AI-Based Automatic Categorization
Feature 3: Real-Time Status Tracking
Feature 4: Admin Dashboard & Analytics

## Implementation

### For Software:

#### Installation
# 1. Create virtual environment (recommended)
python -m venv venv

# 2. Activate virtual environment
# Windows:
venv\Scripts\activate
# Mac/Linux:
source venv/bin/activate

# 3. Install required libraries
pip install flask pandas numpy scikit-learn

# 4. (If using MySQL)
pip install mysql-connector-python

# 5. Run the project
python app.py

#### Run

python manage.py runserver
flask run
python app.py

### For Software:

#### Screenshots (Add at least 3)

<img width="1147" height="865" alt="Screenshot 2026-02-21 102306" src="https://github.com/user-attachments/assets/825977c6-cf78-488d-a2b5-fb2b1d1fc160" />
<img width="1708" height="859" alt="Screenshot 2026-02-21 102423" src="https://github.com/user-attachments/assets/e246243c-0502-4cec-8548-633ce444f8f1" />
<img width="1779" height="832" alt="Screenshot 2026-02-21 102524" src="https://github.com/user-attachments/assets/43fb48b8-6e27-491a-baf1-8bcd69051ee5" />


**System Architecture:**
Frontend Layer – Built using HTML, CSS, and JavaScript for complaint submission and tracking.
Backend Layer – Developed with Python (Flask/Django) to handle logic and AI-based issue categorization.
Database Layer – Uses SQLite/MySQL to store user data and complaint records.


**Application Workflow:**
User Login/Register – Student logs into the system.
Issue Submission – Student submits complaint with description and optional image.
AI Processing – System analyzes and categorizes the issue automatically.
Database Storage – Complaint details are saved in the database.
Admin Review – Admin views and assigns the issue for resolution.
Status Update – Issue status is updated (Pending/In Progress/Resolved).
User Notification – Student tracks and receives updates on the complaint.


**Base URL:** `https://api.yourproject.com`

##### Endpoints

**GET /api/endpoint**
- **Description:** [What it does]
- **Parameters:**
  - `param1` (string): [Description]
  - `param2` (integer): [Description]
- **Response:**
```json
{
  "status": "success",
  "data": {}
}
```

**POST /api/endpoint**
- **Description:** [What it does]
- **Request Body:**
```json
{
  "field1": "value1",
  "field2": "value2"
}
```
- **Response:**
```json
{
  "status": "success",
  "message": "Operation completed"
}
```

[Add more endpoints as needed...]

---

### For Mobile Apps:

#### App Flow Diagram

![App Flow](docs/app-flow.png)
*Explain the user flow through your application*

#### Installation Guide

**For Android (APK):**
1. Download the APK from [Release Link]
2. Enable "Install from Unknown Sources" in your device settings:
   - Go to Settings > Security
   - Enable "Unknown Sources"
3. Open the downloaded APK file
4. Follow the installation prompts
5. Open the app and enjoy!

**For iOS (IPA) - TestFlight:**
1. Download TestFlight from the App Store
2. Open this TestFlight link: [Your TestFlight Link]
3. Click "Install" or "Accept"
4. Wait for the app to install
5. Open the app from your home screen

**Building from Source:**
```bash
# For Android
flutter build apk
# or
./gradlew assembleDebug

# For iOS
flutter build ios
# or
xcodebuild -workspace App.xcworkspace -scheme App -configuration Debug
```

---

### For Hardware Projects:

#### Bill of Materials (BOM)

| Component | Quantity | Specifications | Price | Link/Source |
|-----------|----------|----------------|-------|-------------|
| Arduino Uno | 1 | ATmega328P, 16MHz | ₹450 | [Link] |
| LED | 5 | Red, 5mm, 20mA | ₹5 each | [Link] |
| Resistor | 5 | 220Ω, 1/4W | ₹1 each | [Link] |
| Breadboard | 1 | 830 points | ₹100 | [Link] |
| Jumper Wires | 20 | Male-to-Male | ₹50 | [Link] |
| [Add more...] | | | | |

**Total Estimated Cost:** ₹[Amount]

#### Assembly Instructions

**Step 1: Prepare Components**
1. Gather all components listed in the BOM
2. Check component specifications
3. Prepare your workspace
![Step 1](images/assembly-step1.jpg)
*Caption: All components laid out*

**Step 2: Build the Power Supply**
1. Connect the power rails on the breadboard
2. Connect Arduino 5V to breadboard positive rail
3. Connect Arduino GND to breadboard negative rail
![Step 2](images/assembly-step2.jpg)
*Caption: Power connections completed*

**Step 3: Add Components**
1. Place LEDs on breadboard
2. Connect resistors in series with LEDs
3. Connect LED cathodes to GND
4. Connect LED anodes to Arduino digital pins (2-6)
![Step 3](images/assembly-step3.jpg)
*Caption: LED circuit assembled*

**Step 4: [Continue for all steps...]**

**Final Assembly:**
![Final Build](images/final-build.jpg)
*Caption: Completed project ready for testing*

---

### For Scripts/CLI Tools:

#### Command Reference

**Basic Usage:**
```bash
python script.py [options] [arguments]
```

**Available Commands:**
- `command1 [args]` - Description of what command1 does
- `command2 [args]` - Description of what command2 does
- `command3 [args]` - Description of what command3 does

**Options:**
- `-h, --help` - Show help message and exit
- `-v, --verbose` - Enable verbose output
- `-o, --output FILE` - Specify output file path
- `-c, --config FILE` - Specify configuration file
- `--version` - Show version information

**Examples:**

```bash
# Example 1: Basic usage
python script.py input.txt

# Example 2: With verbose output
python script.py -v input.txt

# Example 3: Specify output file
python script.py -o output.txt input.txt

# Example 4: Using configuration
python script.py -c config.json --verbose input.txt
```

#### Demo Output

**Example 1: Basic Processing**

**Input:**
```
This is a sample input file
with multiple lines of text
for demonstration purposes
```

**Command:**
```bash
python script.py sample.txt
```

**Output:**
```
Processing: sample.txt
Lines processed: 3
Characters counted: 86
Status: Success
Output saved to: output.txt
```

**Example 2: Advanced Usage**

**Input:**
```json
{
  "name": "test",
  "value": 123
}
```

**Command:**
```bash
python script.py -v --format json data.json
```

**Output:**
```
[VERBOSE] Loading configuration...
[VERBOSE] Parsing JSON input...
[VERBOSE] Processing data...
{
  "status": "success",
  "processed": true,
  "result": {
    "name": "test",
    "value": 123,
    "timestamp": "2024-02-07T10:30:00"
  }
}
[VERBOSE] Operation completed in 0.23s
```

---

## Project Demo

### Video
[Add your demo video link here - YouTube, Google Drive, etc.]

*Explain what the video demonstrates - key features, user flow, technical highlights*

### Additional Demos
[Add any extra demo materials/links - Live site, APK download, online demo, etc.]

---

## AI Tools Used (Optional - For Transparency Bonus)

If you used AI tools during development, document them here for transparency:

**Tool Used:** [e.g., GitHub Copilot, v0.dev, Cursor, ChatGPT, Claude]

**Purpose:** [What you used it for]
- Example: "Generated boilerplate React components"
- Example: "Debugging assistance for async functions"
- Example: "Code review and optimization suggestions"

**Key Prompts Used:**
- "Create a REST API endpoint for user authentication"
- "Debug this async function that's causing race conditions"
- "Optimize this database query for better performance"

**Percentage of AI-generated code:** [Approximately X%]

**Human Contributions:**
- Architecture design and planning
- Custom business logic implementation
- Integration and testing
- UI/UX design decisions

*Note: Proper documentation of AI usage demonstrates transparency and earns bonus points in evaluation!*

---

## Team Contributions
M.Sonalika-Frontend 
Akshaya.S-UI/UX designs

## License

This project is licensed under the [LICENSE_NAME] License - see the [LICENSE](LICENSE) file for details.

**Common License Options:**
- MIT License (Permissive, widely used)
- Apache 2.0 (Permissive with patent grant)
- GPL v3 (Copyleft, requires derivative works to be open source)

---

Made with ❤️ at TinkerHub

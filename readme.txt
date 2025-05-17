How to Run the Attendance Management System

Prerequisites

1. Python Installation:
   - Ensure you have Python 3.6 or higher installed on your system.
   - You can download Python from [python.org](https://www.python.org/downloads/).

2. Install Required Libraries:
   - Open the project folder in your IDE (VS Code).
   - Open the terminal in the IDE and run the following command to install the required Python libraries:

     pip install -r requirements.txt

Project Setup

1. Update Paths:
   - Update Line No. 14 in `AMS.py` to the path where you have this project folder on your system.

Running the Project

1. Start the Application:
   - Run the main Python file `AMS.py`:

    python AMS.py

Presentation Guidelines

> You will need to record a video demonstrating how this application works. Each team member should explain specific parts of the application.
> If you explain the PPT, there are 19 slides (I believe), so if you are 6 people, divide 3 slides for each person. Afterward, each person should demonstrate a feature of the application. It should work as follows:

1. **First Person (Vinay)**:
   - Explain slides 1-3.
   - After explaining the slides, switch to the IDE and demonstrate how the source code looks, what the main file is, where the images are stored, how student details are saved, how attendance is recorded, the model, how to install dependencies, and how to run the project. Show the home page to confirm the application is running successfully.

2. **Second Person**:
   - Explain slides 4-6.
   - After explaining the slides, demonstrate the running application. Walk through the UI and explain the function of each button. Show how the instructor would use the buttons. Then, register one student by providing their ID, name, and capturing images to register the student.

3. **Third Person**:
   - Explain slides 7-9.
   - Continue the demonstration by registering the remaining 5 students. For each student, provide the ID, name, and take their images.

4. **Fourth Person**:
   - Explain slides 10-12.
   - Demonstrate how to check the registered students using the `Check Registered Students` button. This will open an admin login UI (admin login: username: admin, password: nimda). Once logged in, show the list of registered students. Then, demonstrate training the model by clicking the `Train Images` button. This will display the success message when the model is trained.

5. **Fifth Person**:
   - Explain slides 13-15.
   - Demonstrate the automated attendance system by entering the subject name. As each person comes in front of the camera, it automatically recognizes and marks their attendance. Finally, it saves this information to both the local system and the database.

6. **Sixth Person**:
   - Explain the remaining slides.
   - Demonstrate the manual attendance feature and conclude the presentation.



Notes

- Ensure your webcam is functional for capturing images and recognizing faces.
- The application creates attendance records in the `Attendance/` folder.
- For manual attendance, records are stored in the `Attendance/Manually Attendance/` folder.
- If you encounter any issues, ensure all dependencies are installed and paths are correctly configured.

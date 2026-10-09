# Securing AI Certification
## Student Guide: Accessing and Completing Modules Using GitHub and Google Colab

### Overview

Welcome to the Securing AI Certification!

This certification introduces students to artificial intelligence security through instructional readings, interactive demonstrations, knowledge checks, and hands-on laboratory activities.

All certification modules are hosted on GitHub and completed using Google Colab. Students will access the certification through their assigned campus cyber range environment.

**You do not need to install Python, JupyterLab, or download the entire GitHub repository to complete the certification.**

### Before You Begin

Make sure you have:

- Access to your assigned campus cyber range environment.
- A web browser within the cyber range that can access GitHub and Google Colab.
- A Google account for accessing Colab and saving your completed work.
- The GitHub repository link provided by your instructor.
- A stable internet connection.

**Important:** These instructions assume the cyber range permits access to external websites and Google Colab. Notebook code will run on Google's hosted servers unless your instructor has configured a different runtime.

---

## Step 1 — Log In to the Campus Cyber Range

1. Navigate to the campus cyber range login page provided by your instructor.
2. Sign in using your assigned credentials.
3. Open your assigned virtual machine or desktop environment.
4. Launch the web browser available inside the cyber range.

You will use this browser to access the certification modules on GitHub and complete them in Google Colab.

**Checkpoint:** You should now have access to a web browser within your cyber range environment.

---

## Step 2 — Access the Certification GitHub Repository

1. Open a new browser tab.
2. Navigate to the GitHub repository link provided by your instructor:

   `https://github.com/nmccloud42/Securing-AI-Certification`

3. Locate the repository's main page.
4. Review the `README.md` file for an introduction to the certification.
5. Locate the folder containing the module you have been assigned.

The repository contains modules organized into individual folders. Each folder contains instructional material and hands-on activities.

**Note:** You do not need to download the repository or use Git commands. The notebooks can be opened directly in Google Colab.

---

## Step 3 — Open Your Module in Google Colab

1. Select the folder corresponding to your assigned module.
2. Locate the notebook file ending in `.ipynb`.
3. Open the notebook using its **Open in Colab** link, if one is provided.

If an Open in Colab link is not available:

1. Open [Google Colab](https://colab.research.google.com).
2. Select **File → Open notebook**.
3. Select the **GitHub** tab.
4. Enter the GitHub repository URL provided by your instructor.
5. Locate and select the appropriate notebook.

The notebook should now open in Google Colab.

**Checkpoint:** You should see the module's title, instructional content, and interactive code cells.

---

## Step 4 — Save Your Own Copy of the Module

**You must save a personal copy before beginning your work.**

1. In Google Colab, select **File → Save a copy in Drive**.
2. A new copy of the notebook will open.
3. Rename your copy using the following naming convention:

   `Module_1_YourName.ipynb`

4. Verify that the notebook is saved in your Google Drive.

You may create a Google Drive folder named `Securing_AI_Certification` to organize your completed modules.

Your copy is independent of the original GitHub notebook. Changes you make will not affect the instructor's course materials or other students' work.

**Checkpoint:** The notebook you are editing should be your personal Google Drive copy.

---

## Step 5 — Connect to a Google Colab Runtime

Before running Python code, you must connect to a runtime.

1. Locate the **Connect** button in the upper-right corner of Google Colab.
2. Click **Connect**.
3. Wait for Colab to establish a connection.
4. Confirm that a runtime is connected.

Google Colab provides access to a Python execution environment.

Most certification activities can use the standard CPU runtime unless otherwise specified.

**Important:** The runtime may disconnect after periods of inactivity. If this occurs, reconnect and rerun the necessary setup cells. Runtime files and variables may not persist after disconnection.

---

## Step 6 — Work Through the Instructional Material

Each module contains instructional readings, demonstrations, knowledge checks, and hands-on activities.

### Reading Sections

All reading sections are collapsible.

To view the material:

1. Locate the section heading.
2. Click the heading or expansion arrow.
3. Read the instructional content.
4. Collapse the section when finished, if desired.

Complete the instructional readings before attempting the associated activities.

### Code Demonstrations

Some code cells contain instructional demonstrations.

To run a code cell:

1. Locate the cell.
2. Click the **Play** button on the left side.
3. Wait for execution to finish.
4. Review the output, graphs, or explanations.

Some code cells may have hidden source code. You do not need to expand or modify these cells unless instructed.

### Hands-On Activities

Hands-on activities allow you to experiment with AI security concepts.

For each activity:

1. Read the activity instructions.
2. Review any variables or settings that you are permitted to change.
3. Modify the requested values.
4. Run the code cell.
5. Examine the results.
6. Complete any required questions or observations.

Only modify the code or parameters identified in the activity instructions.

### Knowledge Checks

Knowledge checks help assess your understanding of the material.

When completing a knowledge check:

1. Read each question carefully.
2. Select or enter your answer.
3. Run the grading or verification cell when provided.
4. Review the feedback.
5. Revisit the relevant instructional section if necessary.

---

## Step 7 — Save Your Progress

Google Colab generally saves changes to notebooks stored in Google Drive automatically.

However, students should regularly verify that their changes have been saved.

Before ending a study session:

1. Confirm that the notebook is saved in Google Drive.
2. Verify that your activity answers and code changes are present.
3. Allow any important running cells to finish.
4. Close the notebook when you are ready to leave.

**Important:** Saving a notebook preserves its code, text, and saved outputs, but it does not preserve the live Python runtime. You may need to rerun cells when returning later.

---

## Step 8 — Continue Your Work in a Later Session

To resume a module:

1. Log back into the campus cyber range.
2. Open the web browser.
3. Navigate to [Google Drive](https://drive.google.com).
4. Sign in using the Google account used previously.
5. Locate your `Securing_AI_Certification` folder.
6. Open your saved notebook in Google Colab.
7. Reconnect to a runtime if necessary.
8. Continue from your previous stopping point.

**Do not start over from the original GitHub notebook if you already have a saved copy.**

Always reopen your personal copy to preserve your previous work.

---

## Step 9 — Complete the Module

Before considering a module complete, verify that you have:

- [ ] Read all required instructional sections.
- [ ] Executed the required code demonstrations.
- [ ] Completed the hands-on activities.
- [ ] Answered the knowledge checks.
- [ ] Completed the end-of-module laboratory, if assigned.
- [ ] Reviewed your results and observations.
- [ ] Saved the completed notebook to Google Drive.

Some modules may include additional requirements. Follow the instructions provided within each module.

---

## Step 10 — Download and Submit Your Completed Module

When you finish a module:

1. Open your completed notebook in Google Colab.
2. Select **File → Download → Download .ipynb**.
3. Save the notebook using the required naming convention:

   `Module_1_YourName_Completed.ipynb`

4. Submit the downloaded notebook through the submission method specified by your instructor.

This may be a cyber range submission portal, learning management system, or another instructor-approved platform.

Do not submit your work to the instructor's master GitHub repository unless explicitly instructed.

---

## Troubleshooting

**Problem: The GitHub notebook will not open.**

Verify that you are using the correct repository URL and that you have permission to access the repository.

**Problem: Google Colab asks me to sign in.**

Sign in with your Google account. If campus restrictions prevent access, contact your instructor.

**Problem: My code cell is not running.**

Confirm that your Colab runtime is connected. Run any required setup or installation cells before executing later activities.

**Problem: My notebook lost variables or temporary files.**

Your runtime may have disconnected or restarted. Reconnect and rerun the necessary cells. Files saved only in the temporary runtime may need to be downloaded again.

**Problem: I cannot find my previous work.**

Open Google Drive and locate your personal notebook copy. Avoid reopening the original GitHub notebook when resuming work.

**Problem: A dataset cannot be downloaded.**

Check the activity instructions and verify that the dataset URL is accessible. If the cyber range blocks the required resource, contact your instructor.

---

## Final Reminders

The GitHub repository contains the official certification materials. Google Colab is the environment used to complete the modules, and Google Drive stores your personal notebook copies.

Always work from your personal copy, save your progress, and follow the instructions for each activity.

**Your goal is not simply to run the provided code, but to understand the AI security concepts, observe the results, and explain what those results demonstrate.**

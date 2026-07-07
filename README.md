# Intro to Data Structure Lab

## Course Information
* **Course:** CPAN 211
* **Topic:** Introduction to Data Structures (Lists, Sets, Maps, Queues)

## Getting Started
This is a starter template for your lab assignments. Follow the GitHub setup below before beginning your work.

---

## GitHub Setup

### Fork the Repository
1. Go to the repository on GitHub.
2. Click the **Fork** button in the top-right corner (VERY IMPORTANT!!!!).
3. This creates your own copy of the project.

### Clone Your Fork
```bash
git clone https://github.com/YOUR-USERNAME/IntroToDataStructure_Lab.git
cd IntroToDataStructure_Lab
```

### Add Upstream Remote
```bash
git remote add upstream https://github.com/ChristinHumber/IntroToDataStructure_Lab.git
```

### Pull Latest Changes
```bash
git pull upstream main
```

### Create a Feature Branch
```bash
git checkout -b feature/lab-yourname
```
*Replace `yourname` with your actual name (e.g., `feature/lab1-john-doe` or `feature/lab-john-doe`).*

---

## Data Structures Lab Assignment

### Overview
This lab assignment will help you practice working with fundamental data structures in Java. You will work with 4 different data structure implementations by fixing compilation errors and completing missing code.

### Lab Structure
The lab contains 4 packages/folders, each focusing on a different data structure:
1. **List Package (`src/List`)** - Working with `ArrayList` operations to build a to-do list functionality.
2. **Set Package (`src/Set`)** - Student exam results analysis using `HashSet` operations.
3. **Map Package (`src/Map`)** - Word frequency counter using `HashMap` operations.
4. **Queue Package (`src/Queue`)** - Customer Service Queue System: Basic queue operations and problem-solving.

### Instructions

#### Step 1: Open the Project
* Open the project in your Java IDE (Eclipse, IntelliJ, NetBeans, etc.).

#### Step 2: Complete the Lab
* Navigate through each package/folder.
* Follow the comments carefully - they contain specific instructions for what you need to implement.
* Fix all compilation errors by completing the missing code.
* Each file has `TODO` comments that guide you through the required implementations.
* Test your implementations by running the main methods in each class. Ensure all code compiles and runs without errors.

### Submission Requirements
To submit your lab, you must push your changes to your GitHub fork and submit a Pull Request (PR link) on blackboard.

#### Step 1: Commit and Push Your Changes
Run the following commands in your terminal:
```bash
# Add all changes
git add .

# Commit changes with a descriptive message
git commit -m "Completed lab assignment"

# Push the feature branch to your fork
git push origin feature/lab-yourname
```
*Note: Replace `feature/lab-yourname` with the actual name of your feature branch.*

#### Step 2: Open a Pull Request
1. Go to the upstream repository at [ChristinHumber/IntroToDataStructure_Lab](https://github.com/ChristinHumber/IntroToDataStructure_Lab).
2. You should see a prompt banner saying **"Compare & pull request"** for your pushed branch. Click it.
3. If you don't see the banner:
   * Go to your GitHub fork page.
   * Switch to your feature branch using the branch dropdown menu.
   * Click **Contribute** and then select **Open pull request**.
4. Verify the base repository is `ChristinHumber/IntroToDataStructure_Lab` and the base branch is `main`.
5. Set the title of your pull request to: `Lab Submission - [Your Name]` (e.g., `Lab Submission - John Doe`).
6. Click **Create pull request** to complete the submission.

#### Additional Requirements
* **Code Verification:** Make sure all compilation errors are fixed and your code runs successfully before submitting.


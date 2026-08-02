# Jenkins Day 03 - Build Automation

## 🎯 Objective

To understand Build Automation using Jenkins and execute build commands automatically after downloading source code from GitHub.

---

## 📖 Project Description

This project demonstrates how Jenkins automates the build process. Jenkins downloads source code from a GitHub repository, executes Windows batch commands, displays build logs in Console Output, and stores project files in the Workspace.

This is an important step in Continuous Integration (CI).

---

## 🛠 Tools Used

- Windows 11
- Java 25
- Jenkins
- Git
- GitHub
- VS Code

---

## 📚 Topics Covered

- What is a Build?
- What is Build Automation?
- Jenkins Build Process
- Source Code Management (SCM)
- Workspace
- Console Output
- Continuous Integration (CI)

---

## 📂 Project Structure

```
jenkins-day03-build-automation/

│── README.md
│── notes.txt
│── index.html
│── style.css
│
└── screenshots/
```

---

## ⚙ Build Commands

```bat
echo ===========================
echo BUILD STARTED
echo ===========================

dir

echo.

echo Listing Project Files

type README.md

echo.

echo Build Completed Successfully

echo ===========================
```

---

## 📄 Console Output

```
Started by user

Cloning repository

Checking out Revision

README.md
notes.txt
index.html
style.css

BUILD STARTED

Listing Project Files

Build Completed Successfully

Finished: SUCCESS
```

---

## 🎓 What I Learned

- Jenkins automates build tasks.
- A build converts source code into executable output.
- Jenkins downloads source code from GitHub.
- Jenkins executes build commands automatically.
- Console Output displays execution logs.
- Workspace stores project files.
- Build Automation reduces manual work.

---

## 🏢 Real-Time Use Case

In software companies, developers push code to GitHub. Jenkins automatically downloads the latest code, builds the project, runs tests, and prepares it for deployment. This process is called Continuous Integration (CI).

---

## 📸 Screenshots

### New Job Creation
![New Job](screenshots/01-new-job.png)

### Git Configuration
![Git](screenshots/02-git-configuration.png)

### Build Commands
![Build](screenshots/03-build-command.png)

### Build Success
![Success](screenshots/04-build-success.png)

### Console Output
![Console](screenshots/05-console-output.png)

### Workspace
![Workspace](screenshots/06-workspace.png)

---

## 🎯 Outcome

Successfully automated the build process using Jenkins and GitHub integration.

---

## 👩‍💻 Author

**Subalakshmi K**

Cloud & DevOps Learner
# CodeBuddies Collaboration Project

_A monorepo for Java projects by Ashrith and Kavya_

## 👥 Project Overview

This repository is a collaborative workspace managed by **Ashrith** and **Kavya**.
It contains multiple Java-based projects—such as Core Java, Spring Boot, and Spring Security demos—organized in
subfolders.
All work follows a protected, review-driven workflow to ensure quality and teamwork.

---

## 🚀 Prerequisites

- **Java Version:**  
  Both collaborators must use **Java 17** (or your chosen version) for all projects in this repository.  
  _[Download Java 17 here](https://adoptium.net/temurin/releases?version=17&os=any&arch=any)_  
  Always keep your Java version consistent with the team. To check, run: ```java -version```

- **Git:**  
  Ensure Git is installed and configured with your name/email.
  To check, run: ``` git --version ```

- **IntelliJ IDEA:**  
  Recommended IDE for all Java development.

---

## 📝 Common Setup Steps

Follow these instructions **before you start working** on any feature or bug.

### 1. Clone the Repository

```git clone https://github.com/ashrithjetti/java-code-lab.git```

```cd java-code-lab```

### 2. Set Up the Correct Java Version

- Ensure that your local system uses **Java 17**.
- In IntelliJ IDEA:
    - Go to **Project Structure** (Ctrl+Alt+Shift+S) → **Project** → **Project SDK**: Set to Java 17.

### 3. Open the Repository in IntelliJ IDEA

- Open IntelliJ IDEA → **Open** → Select the cloned folder.
- Treat each subfolder as a separate module/project if prompted.

## 🌿 Branching & Collaboration Workflow

_These steps must be followed by **both Ashrith and Kavya**._

### Step-by-Step Workflow

1. **Create a Personal Feature Branch**
    - Always branch from `main`:
      ```
      git checkout main
      git pull origin main    # Make sure you have the latest
      git checkout -b <your-feature-branch>
      ```

2. **Work on Your Module**
    - Only modify relevant project folders.
    - Frequently commit your changes:
      ```
      git add .
      git commit -m "[USERNAME-MACHINE_MODEL]: Meaningful commit message"
      for ex.: git commit -m "[ASHRITH-ENVY]: Initial Commit"
      ```

3. **Push Your Branch**
    - Push to remote:
      ```
      git push origin <your-feature-branch>
      ```

---

## 🔗 Useful Commands Reference

Check Java version

```
java -version
```

List local branches

```
git branch
```

List remote branches

```
git branch -r
```

Fetch latest from remote

```
git fetch
```

Switch branch

```
git checkout <branch-name>
```

Pull latest

```
git pull origin main
```

Push new branch

```
git push -u origin <branch-name>
```

## 🤝 Contact

- For repository access issues or workflow questions, contact Ashrith or Kavya via email or GitHub.

---

**Let’s keep our codebase clean, well-documented, and fun to work with!**
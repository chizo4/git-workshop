# `Git & GitHub Workshop` 📟

> **Note**
This repository covers materials associated with the `Git & GitHub Workshop` authored by Filip J. Cierkosz. The resources found here are designed to help to understand and learn how to effectively use `Git` and `GitHub`. `README.md` of this repo complements the concepts introduced in [the slides](https://github.com/chizo4/git-workshop/tree/main/slides).

---

## Table of Contents 📖
- [What is `Git`?](#what-is-git) 
- [`Git` Installation](#git-installation-%EF%B8%8F)
- [LCL Essentials - Cheatsheet](#lcl-essentials---cheatsheet)
- [Git Essentials - Cheatsheet](#git-essentials---cheatsheet)
- [Further Resources](#further-resources)

---

## What is `Git`? 🧐

`Git` is a distributed version control system (`VCS`) that facilitates better coding efficiency and software maintenance. It is an essential tool for collaboration, allowing multiple people to work on the same project without conflicts. Here are some key points about `Git`:

- **Efficiency and Maintenance**: `Git` optimizes the workflow in development projects, making it easier to track changes and maintain code.
- **Collaboration**: `Git` is designed for team collaboration, enabling developers to work together on software projects seamlessly.
- **Versatility**: It is not just for software development. `Git` is useful in any scenario that requires tracking changes, such as personal, university, and open-source projects.
- **Market Relevance**: Many companies require knowledge of `Git` as part of their development process.
- **Popularity**: Over 100 million developers use `GitHub`, a platform that integrates with Git, indicating the widespread adoption of this system.
- **Branch Management**: `Git` allows the creation of multiple 'branches' which aid in isolated development efforts, thereby keeping the main project stable.
- **Version Control**: It is crucial for managing complex projects. `Git` enables you to track iterations, revert to previous versions, and manage parallel work streams effectively.

> **Note**
`Git` should not be confused with `GitHub`. While `Git` is a version control system, `GitHub` is a platform for hosting and sharing files and managing `Git` repositories online. Other platforms like `GitLab` also use `Git`. Understanding `Git` is crucial for anyone involved in software development, and the number of `Git` users continues to grow exponentially.

---

## `Git` Installation 🛠️

Follow the steps below to setup `Git` and `GitHub` on your machine. Otherwise, you might also use the slides found [here](https://github.com/chizo4/git-workshop/blob/main/slides/Git_GitHub_Installation_Guides.pdf).

#### Step 1️⃣: `Git` Installation
1. **Check for Pre-installed Git**:
   - Open the terminal and type:
     ```shell
     git --version
     ```
   - If a version appears, `Git` is already installed on your machine.

2. **Install `Git` (if not already installed)**:
   - Download `Git` from [this website](https://git-scm.com/download).
   - Ensure to select the correct OS and the latest version.

#### Step 2️⃣: Create a `GitHub` Account
1. **Sign Up**:
   - Go to [github.com](https://github.com) and follow the link to start a free account.
   - Follows the steps, i.e. provide basic information (name, email, etc.).
   - NB: Students can often get a `PRO account` free of charge.

#### Step 3️⃣: Connect `GitHub` to Your Machine
1. **Set `Git` Credentials**:
   - Open your terminal and set your Git credentials:
     ```shell
     git config --global user.name "Your Name"
     ```
     ```shell
     git config --global user.email "your@email.com"
     ```
   - Verify the setup by running:
     ```shell
     git config --list
     ```
2. **SSH Key Setup**:
   - Navigate to your SSH directory with:
     ```shell
     cd ~/.ssh
     ```
   - Check for existing SSH keys (don't worry if some commands look complicated):
     ```shell
     (ls id_rsa && ls id_rsa.pub) && echo yes || echo no
     ```
   - If you don’t have the SSH keys (`id_rsa` and `id_rsa.pub`), generate them with:
     ```shell
     ssh-keygen -t rsa -C "your_email@example.com"
     ```
   - Copy the SSH public key to your clipboard:
     ```shell
     pbcopy < ~/.ssh/id_rsa.pub
     ```
   - Go to [github.com](https://github.com), click on `“Account Settings”` ➡️ `“SSH Keys”`.
   - Add a label for your key (e.g., `“My MacBook”`) and paste the copied key.
   - Confirm the setup by running:
     ```shell
     ssh -T git@github.com
     ```
   - You should see a message confirming that you've successfully authenticated.

> **Note**
This guide covers the basic steps to install Git and set up GitHub on your machine. For more instructions, refer to the official [Git Installation Guides](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git).

---

## LCL Essentials - Cheatsheet
*Content coming soon...*

---

## Git Essentials - Cheatsheet
*Content coming soon...*

---

## Further Resources
*Content coming soon...*

---

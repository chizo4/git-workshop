# `Git & GitHub Workshop` 📟

> **Note**
This repository covers materials associated with the `Git & GitHub Workshop` authored by Filip J. Cierkosz. The resources found here are designed to help to understand and learn how to effectively use `Git` and `GitHub`. `README.md` of this repo complements the concepts introduced in [the slides]().

## Table of Contents
- [What is Git?](#what-is-git)
- [Git Installation](#git-installation)
- [LCL Essentials - Cheatsheet](#lcl-essentials---cheatsheet)
- [Git Essentials - Cheatsheet](#git-essentials---cheatsheet)
- [Further Resources](#further-resources)

---

### What is Git?
*Content coming soon...*

### Git Installation

Follow the steps below to install Git and set up GitHub on your machine. Otherwise, you might use the slides [here]().

#### Step 1: Git Installation
1. **Check for Pre-installed Git**:
   - Open a terminal and type:
     ```shell
     git --version
     ```
   - If a version number appears, Git is already installed on your machine.

2. **Install Git (if not already installed)**:
   - Download Git from [https://git-scm.com/download](https://git-scm.com/download).
   - Ensure to select the correct OS and the latest version.

#### Step 2: Create a GitHub Account
1. **Sign Up**:
   - Go to [github.com](https://github.com) and follow the link to start a free account.
   - Follows the steps, i.e. provide basic information (name, email, etc.).
   - NB: Students can often get a PRO account free of charge.

#### Step 3: Connect GitHub to Your Machine
1. **Set Git Credentials**:
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
     ```
     cd ~/.ssh
     ```
   - Check for existing SSH keys:
     ```
     (ls id_rsa && ls id_rsa.pub) && echo yes || echo no
     ```
   - If you don’t have the SSH keys (`id_rsa` and `id_rsa.pub`), generate them with:
     ```
     ssh-keygen -t rsa -C "your_email@example.com"
     ```
   - Copy the SSH public key to your clipboard:
     ```
     pbcopy < ~/.ssh/id_rsa.pub
     ```
   - Go to [github.com](https://github.com), click on “Account Settings” -> “SSH Keys”.
   - Add a label for your key (e.g., “My MacBook”) and paste the copied key.
   - Confirm the setup by running:
     ```
     ssh -T git@github.com
     ```
   - You should see a message confirming that you've successfully authenticated.

This guide covers the basic steps to install Git and set up GitHub on your machine. For more instructions, refer to the official [Git Installation Guide](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git).

### LCL Essentials - Cheatsheet
*Content coming soon...*

### Git Essentials - Cheatsheet
*Content coming soon...*

### Further Resources
*Content coming soon...*


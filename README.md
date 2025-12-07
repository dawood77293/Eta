# 🐧 Interactive Linux Command Tutor (Basic I & II)

This project is an **interactive Bash-based quiz script** that helps students **practice and test their knowledge of Linux shell commands** taught in **Basic Command I & II**.

The script asks questions one by one, takes the user's input, and checks for **exact command matches**, providing instant feedback and a final score.

---

## 🎯 Project Objectives

- Help students **practice Linux commands interactively**
- Enforce **exact command syntax**
- Strengthen command-line memory through repetition
- Provide a **simple terminal-based learning tool**

---

## 🛠 Tool Used

- **Bash Shell (Linux Terminal)**

## 🖥 Setting Up Kali Linux Using VMware Player (Student Version)

1. First, download **VMware Player** (latest version) from the internet.  
   If you are using **Windows or Linux**, use **VMware Player**.  
   If you are using **Mac**, use **VMware Fusion Player**.

2. After downloading VMware, install it like any normal program on your computer.

3. Now go to the **official Kali Linux website** and download the **Kali VMware file**.  
   Make sure you download the:
   - Latest version  
   - 64-bit version

4. After the download finishes, go to the folder where the file is saved and **extract (unzip)** the Kali file.

5. Open **VMware Player**, then click on:

6. Go to the extracted Kali folder and select the file:

7. Click **Open**, then click **Play** to run the Kali virtual machine.

8. When Kali starts:
- Default username: `kali`
- Default password: `kali`  
(For older versions: username `root`, password `toor`)

9. After logging in, open the terminal and update the system using:

```bash
sudo apt-get update
sudo apt-get upgrade -y

## ✅ Project Steps (Student Version)

1. We installed **Kali Linux using VMware Player** on our computers.  

2. After logging into Kali, we opened the **Terminal** using:  
CTRL + ALT + T  

3. We created a new Bash script file using this command:  
```bash
touch linux_quiz_full.sh
We opened the file using the mousepad editor:

bash
Copy code
mousepad linux_quiz_full.sh
We copied and pasted our full Bash quiz script code into the file.

We saved the file and closed the editor.

We gave the script permission to run using:

bash
Copy code
chmod +x linux_quiz_full.sh
We ran the script using:

bash
Copy code
./linux_quiz_full.sh
The program started showing Linux command questions.

We typed the exact command answers in the terminal.

The program checked each answer and showed whether it was correct or wrong.

At the end, the program showed the final score.

We took screenshots of the program output.

We uploaded the following to GitHub:

The Bash script

The screenshots

The README file

  

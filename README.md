## High Performance Computing Practicals
### Problem Statements - 

1. Practical - 1 : Design and implement Parallel Breadth First Search and Depth First Search based on existing
algorithms using OpenMP. Use a Tree or an undirected graph for BFS and DFS.
2. Practical - 2 : Write a program to implement Parallel Bubble Sort and Merge sort using OpenMP. Use
existing algorithms and measure the performance of sequential and parallel algorithms.
3. Practical - 3 : Implement Min, Max, Sum and Average operations using Parallel Reduction.

## Installation
### 🧱 Step 1: Download and Install MSYS2
Go to the official MSYS2 website:
🔗 https://www.msys2.org

Download the installer and run it.

After installation, open the Start Menu and launch:

🟢 MSYS2 MinGW 64-bit

### ⚙️ Step 2: Update MSYS2
In the MSYS2 terminal:

<pre lang="markdown">pacman -Syu</pre>

### 📦 Step 3: Install G++ with OpenMP Support
In the same terminal:

<pre lang="markdown">pacman -S mingw-w64-x86_64-gcc</pre>

This installs the g++ compiler with OpenMP support.

### 📁 Step 4: Find the bin Path to Add to Environment Variables
Your compiler's path is likely:

<pre lang="markdown">C:\msys64\mingw64\bin</pre>

Open that folder and make sure it contains g++.exe.

### 🔗 Step 5: Add the bin Folder to Your System PATH
Press Windows + S, search for:

Environment Variables

Click:

1. Edit the system environment variables

In the System Properties window, click:

1. Environment Variables…

2. Under System variables, select Path and click Edit.

3. Click New, then paste this:
<pre lang="markdown">C:\msys64\mingw64\bin</pre>
4. Click OK to save everything and close all dialogs.

### ✅ Step 6: Confirm G++ Works in CMD or PowerShell
Close all open terminals. Then open Command Prompt or PowerShell, and run:
<pre lang="markdown">g++ --version</pre>

You should see version info for G++. If so, it’s working!

### ▶️ Step 7: Compile and Run Your File in CMD
1. Navigate to your .cpp file:
<pre lang="markdown">cd "C:\Users\rajpa\OneDrive\Desktop"</pre>

2. Compile your program:
<pre lang="markdown">g++ -fopenmp -o Practical-1 Practical-1.cpp</pre>

3. Run the executable:
<pre lang="markdown">Practical-1.exe</pre>

## Output
Practical-1 :

![Practical-1](https://github.com/user-attachments/assets/623b6323-1bc0-467c-9afa-ee21c50c5e51)

Practical-2 : 

![WhatsApp Image 2025-05-01 at 15 21 00_eba7740f](https://github.com/user-attachments/assets/fb083574-bb16-431e-b6f6-5cae9ae653f1)

Practical-3 :

![WhatsApp Image 2025-05-01 at 15 21 27_73026be9](https://github.com/user-attachments/assets/f5a22773-80f0-4121-bf36-2c26aac02d8b)


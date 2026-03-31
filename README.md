# Auto Commit and GitHub Push using Python

This project automatically:
- Creates or updates a `README.md` file
- Adds files to Git
- Commits changes automatically
- Pushes code to GitHub

It is useful for automating basic Git workflow using Python.

---

## Features

- Auto create `README.md`
- Auto commit changes
- Auto push to GitHub
- Beginner-friendly Python script

---

## Technologies Used

- Python
- Git
- GitHub
- subprocess module

---

## Project Files

- `auto_commit.py` → Main Python script
- `README.md` → Project documentation

---

## How It Works

The Python script performs these steps:

1. Creates or updates the `README.md` file
2. Runs `git add .`
3. Runs `git commit -m "message"`
4. Runs `git push`

---

## Requirements

Before running this project, make sure you have:

- Python installed
- Git installed
- A GitHub repository created
- Your local project connected to GitHub

Check Git installation:

```bash
git --version

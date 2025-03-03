# Getting Started With Docsify

## Prerequisites

Before setting up Docsify, ensure you have:
- Basic familiarity with Markdown and the command line
- Node.js and npm installed 
- A code/text editor(this guide uses VSCode)

> P.S.: Even if you're unsure of your skills, follow each step in this guide, and you'll learn as you go! Docsify is beginner-friendly, and by the end, you'll have a working documentation site.

## Step 1: Create a Project Folder

Before installing Docsify, create a folder for your documentation project. Open your terminal and run:

```bash
mkdir Docsify-demo && cd Docsify-demo
```

This ensures all your files stay in one place, making it easier to manage your documentation.

## Step 2: Installing Docsify

Docsify can be installed globally using npm:

```bash
npm i docsify-cli -g
```
## Step 3: Initialize a new documentation site:

```bash
docsify init ./docs
```

## Step 4: Running Docsify Locally

```bash
docsify serve ./docs
```

Open http://localhost:3000 to see your live docs! Your site should look like this in the browser.

## Project Structure
The docs folder will include:

```bash
/docs
│── index.html     # The entry file for configuration 
│── README.md      # Contains your homepage content (written in Markdown)
│── .nojekyll      # Prevents GitHub Pages from ignoring files with underscores
```
# 🕹️ OGPH (OnyxSoul Game Player Html)

A lightweight web application designed to make source-code games fully playable on **any device**, especially devices with **small screens** and **poor resolutions**. 

We play games to have fun, not to fight with resolution settings! OGPH fixes this by wrapping games in an optimized viewport, giving you tools to hide cluttering interfaces and maximize your actual gameplay screen real estate.

---

## 🚀 Live Demonstration
You can view and test the live application directly on your GitHub Pages deployment:
👉 **[Launch OGPH Live Dashboard](https://github.io)**

---

## 📊 Application Layout Overview

When hosted on GitHub Pages, the interface functions as a responsive desktop-to-mobile wrapper environment:

```text
+-------------------------------------------------------------+

|  OGPH - BY OnyxSoul                                         |
+-------------------------------------------------------------+

|  📝 Game Source Code                                        |
|                                                             |
|  [ 📂 Add File ]    [ 👁 Hide UI / Show UI ]    [ ▶ RUN ]   |
|                                                             |
|  FPS: 60                                                    |
|                                                             |
|  +-------------------------------------------------------+  |
|  |                                                       |  |
|  |                  [ GAME VIEWPORT ]                    |  |
|  |                                                       |  |
|  |         Automatically scaled down to prevent          |  |
|  |         scrolling issues on small displays.           |  |
|  |                                                       |  |
|  +-------------------------------------------------------+  |
|                                                             |
|  OnyxSoul Dev                                               |
+-------------------------------------------------------------+
```

---

## 🎯 The Core Problem & Our Solution

* **The Screen Barrier:** Most modern code configurations assume you are running a large display. When loaded on micro-monitors or smaller handheld screens, layout elements overlap, become unclickable, or crop completely out of view.
* **The OGPH Fix:** This handler strips hardcoded layout scaling constraints. It forces the game canvas to adapt safely inside small mobile or compact display frames, ensuring your layout proportions remain intact.

---

## ⚡ Main Feature Interactions

* **📂 Add File Container:** Upload or reference external game source assets into the environment container execution stack.
* **👁 Hide / Show UI Controls:** Instantly toggle utility panels out of sight to unlock 100% fullscreen canvas visibility when playing on restrictive screen widths.
* **▶ RUN Engine Loop:** Instantly compiles your script hooks and boots up the layout processor.
* **Real-time FPS Indicator:** Live rendering monitor to ensure frame integrity remains steady across low-end mobile hardware.

---

## 🛠️ GitHub Pages Deployment Guide

Follow these steps to host this codebase configuration directly through your personal GitHub profile:

### 1. Structure the Project Directory
Ensure your core workspace files reside cleanly inside the root layer of your remote repository:
```text
ogph/
├── index.html        # Main application file interface
├── styles.css        # Responsive styling sheets
├── script.js         # Core scaling engine logic
└── README.md         # Current file overview documentation
```

### 2. Commit and Push to Main
Initialize your repository locally and dispatch the source to your remote branch:
```bash
git init
git add .
git commit -m "feat: implement initial mobile layout handler"
git branch -M main
git remote add origin https://github.com
git push -u origin main
```

### 3. Activate GitHub Pages Setup
1. Navigate directly to your project page on **GitHub**.
2. Select the top-bar **Settings** navigation element.
3. Locate the **Pages** menu option from the sidebar utility group.
4. Set the *Build and Deployment* source element selection criteria to **Deploy from a branch**.
5. Adjust the target branch to **`main`** and select **`/(root)`** as the folder path.
6. Press the **Save** validation action layout asset block. 

*Your static web gaming interface distribution point will be live online within roughly 1-2 execution tracking cycles.*

---

## 📄 Project Licensing
This engine architecture is distributed openly under the **MIT License**. Maintained and authorized under copyright verification bounds by **OnyxSoul Dev**.

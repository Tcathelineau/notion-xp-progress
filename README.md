# Notion XP Progress Bar

This repository contains a small web project used to display a **visual XP and level progress bar** inside a **Notion page**.

The project is designed for **personal use** and aims to bypass Notion’s lack of native graphical progress bars by embedding a lightweight HTML page.

---

## Purpose

The goal is to turn numeric XP values stored in Notion into a **clear visual indicator** showing:
- the current level
- XP progress within that level
- progress toward the next level

The progress bar is embedded directly into a Notion page using GitHub Pages.

---

## How it works

- XP thresholds define the amount of XP required for each level
- A total XP value is compared against these thresholds
- The current level and progress percentage are calculated in JavaScript
- The result is displayed as an animated horizontal progress bar
- The page is embedded into Notion using an `/embed` block

---

## Features

- Level calculation based on cumulative XP
- XP progress within the current level
- Smooth animated progress bar
- No backend or framework
- Free hosting with GitHub Pages
- Designed specifically for Notion embeds

---

## Usage in Notion

1. Deploy the repository using GitHub Pages
2. Copy the generated public URL
3. Insert an `/embed` block in a Notion page
4. Paste the URL and resize the embed

---

## Customization

You can adjust:
- XP thresholds
- Colors and bar style
- Animation timing
- Text labels

The project is intentionally kept simple and easy to modify.

---

Enjoy 🚀

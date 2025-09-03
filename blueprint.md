
# Blueprint

## Overview

A simple, interactive terminal interface built with HTML, CSS, and JavaScript. This project provides a classic terminal window appearance and allows users to input commands.

## Project Structure

- `terminal.html`: The main HTML file containing the structure of the terminal window.
- `term_style.css`: The CSS file for styling the terminal's appearance.
- `main.js`: The JavaScript file for handling user input and terminal behavior.

## Features

- **Terminal Window**: A styled container that mimics a desktop terminal window, complete with header and control dots.
- **Command Prompt**: A classic `$` prompt for user input.
- **Interactive Input**: An editable field where users can type commands.
- **Line-by-Line Entry**: Pressing "Enter" creates a new line with a fresh prompt, preserving the history.

## Design

- **Theme**: A dark theme with a monospaced green font for a retro terminal look.
- **Layout**: A responsive layout that centers the terminal window.
- **Header**: A simple header with colored dots (red, yellow, green) for a touch of realism.

# Current Task

## Goal

The goal is to fix a styling issue where the `$` prompt and the user input field are on separate lines, making them appear on the same line for a proper terminal look.

## Plan

1. **Modify `term_style.css`**: Add a `display: flex` property to the `.terminal-line` class to align the prompt and input on the same line.
2. **Update `terminal.html`**: Change the wrapping `div` with the class `terminal-line` to a `label` element for better semantic HTML. This associates the prompt text with the input area.

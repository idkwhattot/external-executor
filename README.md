# Roblox External Executor

A lightweight external command-based executor designed for interacting with multiple Roblox clients.

Built with a focus on simplicity, stability, and efficient execution workflows.

---

## Overview

This executor operates externally and provides a command-line style interface for executing scripts.

It supports multi-client attachment and automatically manages required directories for script execution.

---

## Features

- External (no injection-based DLL loading)
- Command-line interface (CMD-style usage)
- Multi-client attach support
- Auto workspace & autoexec folder creation
- Simple execution workflow
- Stable attachment system
- 59 UNC supported

---

## How It Works

The executor attaches to running Roblox processes and establishes a communication layer for script execution.

### Core behavior:

- Detects running Roblox instances
- Allows attaching to one or multiple clients
- Initializes execution environment
- Handles script loading and execution through commands

---

## Folder Structure

On first launch, the executor will automatically create:
workspace/
autoexec/


### Purpose:

- **workspace/** → used for manual script storage  
- **autoexec/** → scripts placed here run automatically on attach  

---

## Usage

### 1. Launch Roblox

Start one or more Roblox clients.

---

### 2. Run Executor

Open the executor application.

---

### 3. Attach to Client

Type: inject

This will attach to available Roblox clients.  
Supports attaching to multiple clients simultaneously.

---

### 4. Select Script

To select a script, provide the full path: select C:\path\to\your\script.lua

Make sure to use the **full file path**.

---

### 5. Execute Script

Run: execute


The selected script will be executed on all attached clients.

---

## Multi-Client Support

The executor supports attaching to multiple Roblox instances.

- Scripts can run across all attached clients  
- Useful for testing and automation scenarios  

---

## Notes

- Ensure Roblox is running before attaching  
- Use valid file paths when selecting scripts  
- Re-attach after Roblox updates if needed  

---

## Disclaimer

This project is intended for educational and research purposes only.  
Do not use it in ways that violate Roblox Terms of Service.

---

## Author

Developed by **CabeFillRoving**

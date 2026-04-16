---
description: Create aiworkshop GitHub repository from ProjectGengar Step-16 branch
auto_execution_mode: 3
---

# Create aiworkshop GitHub Repository

This workflow creates a new GitHub repository called 'aiworkshop' and populates it with content from the ProjectGengar Step-16 branch using the GitHub MCP server.

## Prerequisites

- GitHub MCP server must be configured and authenticated
- Git must be installed and available in PATH
- Current repository must have a Step-16 branch

## Steps

### 1. Get GitHub username
Use the GitHub MCP server to get your username.

### 2. Create the new repository
Create a new public repository called 'aiworkshop'.

### 3. Checkout Step-16 branch
Switch to the Step-16 branch in the current repository.

### 4. Collect and push all files from Step-16 branch
Read all files and push them in batches to the new repository.

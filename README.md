# i2i Academy - Introduction to Cloud

This repository documents the solution for the i2i Academy Introduction to Cloud assignment.

## Objectives
1. Set up a basic Virtual Machine (VM) on a Cloud Service Provider (Hostinger VPS).
2. Perform a Ping Test from the local terminal to verify network connectivity.
3. Establish an SSH connection to the VM.
4. Create a text file (`hello.txt`) with a custom message and verify its content.

## Commands Executed

### 1. Ping Test
From the local terminal:
```bash
ping -c 4 72.62.37.67
```

### 2. File Creation on VM via SSH
Inside the SSH session:
```bash
echo "Hello i2i Academy!" > hello.txt
cat hello.txt
```

# Linux & Docker Research Report

## WSL / Ubuntu

### What is Windows Subsystem for Linux (WSL)?

Windows Subsystem for Linux (WSL) is a Microsoft feature that allows users to run a Linux environment directly on Windows without installing a separate operating system or a virtual machine. It enables developers to use Linux command-line tools, utilities, and applications while working within Windows.

### Why do developers prefer Ubuntu terminal commands instead of Windows PowerShell?

Developers often prefer Ubuntu terminal commands because:

* Most web servers and cloud platforms run Linux.
* Linux provides powerful command-line tools for development.
* Many programming languages and frameworks are designed to work best on Linux.
* Bash scripting is widely used for automation.
* Docker and cloud technologies integrate more naturally with Linux.

PowerShell is excellent for Windows administration, but Ubuntu offers better compatibility with modern software development workflows.

---

## Docker Containers

### What is a Docker Container?

A Docker Container is a lightweight, isolated environment that packages an application together with all of its dependencies, libraries, and configuration files. This allows the application to run consistently on any computer that has Docker installed.

### Why is it better to run Python inside a Docker Container rather than directly on your host operating system?

Running Python inside a Docker Container has several advantages:

* Ensures the same development environment for everyone.
* Prevents dependency and version conflicts.
* Makes applications portable across different operating systems.
* Simplifies deployment to cloud servers.
* Keeps the host operating system clean and unaffected.
* Improves collaboration because the application behaves the same on every machine.

Docker helps developers build, test, and deploy Python applications in a reliable and consistent environment.

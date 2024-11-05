# Requriments-Checker
A Python tool for automated dependency compatibility checks in GitHub repositories

A Python tool for automated dependency compatibility checks in GitHub repositories.

This repository provides a tool to automate the verification of dependency versions for Python projects. By cloning a specified GitHub repository and analyzing the requirements.txt file, it checks each listed dependency for compatibility with the current environment. Any version mismatches or missing dependencies are logged in a report file, making it easier to ensure the repository's requirements are met.

Key Features
Automatic GitHub Repository Cloning: Easily clone any public GitHub repository by specifying the URL.
Dependency Compatibility Check: Parses requirements.txt and checks installed versions against required versions.
Detailed Mismatch Reporting: Saves incompatibilities or missing dependencies in mismatch_report.txt for easy reference.
Usage
Clone the repo.
Replace github_url with your GitHub repository URL.
Run the script to generate a compatibility report in mismatch_report.txt.
Ideal for researchers, developers, and contributors who need to verify dependency compatibility quickly before running a project.

Authors: Atul Sharma and Kirti Singh



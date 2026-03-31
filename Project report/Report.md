# Project report

## Problem Statement
In the current digital landscape, user authentication is often compromised due to weak passwords (e.g., "123456", "password"). Users struggle to create high-entropy passwords manually, making them vulnerable to brute-force and dictionary attacks.

## Scope
The scope of this project is to build a lightweight, desktop-based utility that acts as both an educational tool (showing why a password is weak) and a functional tool (generating strong ones). It focuses on local execution without requiring internet connectivity.

## Target Users
* General internet users who need quick password verification.
* Students learning about basic cybersecurity hygiene.
* System administrators requiring a quick CLI tool for key generation.

## High-Level Features
* **Entropy Check:** Algorithms to calculate password complexity.
* **Randomization:** Cryptographically pseudo-secure number generation (CSPRNG) concepts.
* **Persistence:** File handling to store generated data.
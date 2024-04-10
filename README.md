# Bank Branch Management System

This is a JavaScript implementation of Singleton pattern for managing bank branch information. The code demonstrates how to ensure that only one instance of the "BankBranch" class exists throughout the application, allowing for centralized management of branch-related data.

## Overview

The code consists of the "BankBranch" class that encapsulates branch information and ensures singleton behavior, ensuring that multiple instances of the class refer to the same object. Each instance of 'bankBranch' contains information about a specific bank branch, such as its branch, branchcode, and tradingHours.

## Usage

1. **BankBranch Instances:**
    - Create instances of the 'BankBranch' class by providing branch information as an object to the constructor.

2. **Branch Information:**
    - 'getBranchInfo' method to retrieve branch infomation from the intances.

3. **Singleton:**
    - Verify that multiple instances of the 'BankBranch' refer to the same object by comparing them using '==='.
# Blockchain_project
StudentRegistry Smart Contract
Overview
The StudentRegistry contract is a Solidity-based smart contract designed for managing student information and attendance. It allows students to register, mark their attendance, and receive rewards based on their attendance records.

Features
Student Registration: Allows students to register with their personal details.
Attendance Tracking: Enables students to mark their attendance and track the number of days attended.
Reward System: Automatically rewards students with Ether if their attendance exceeds a predefined threshold.
Contract Management: Allows the contract owner to fund the contract and withdraw funds.
Key Functions
Register Student: Register a student with their name, email, mobile number, and roll number.
Mark Attendance: Increment attendance count for the calling student.
Get Attendance Count: Retrieve the attendance count for a specific student.
Get Student Details: Access all details and attendance count for a specific student.
Fund Contract: Add Ether to the contract to fund rewards.
Withdraw Funds: Withdraw Ether from the contract (restricted to the owner).
Usage
Deploy the Contract: Deploy to an Ethereum network using tools like Remix or Truffle.
Register Students: Use the registerStudent function to add students.
Mark Attendance: Students can call markAttendance to record their attendance.
View Information: Retrieve details and attendance counts with getStudentDetails and getAttendanceCount.
Manage Funds: Fund the contract using fundContract and manage funds with withdrawFunds.

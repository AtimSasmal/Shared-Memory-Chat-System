# Shared-Memory-Chat-System
This is a course work of operating system

Introduction
This document describes the design and implementation of a Shared Memory Chat
System built in C. The system demonstrates core operating systems concepts including
inter-process communication (IPC), process synchronization, shared memory manage
ment, and semaphore-based mutual exclusion.
Project Objectives
• Implement inter-process communication using POSIX shared memory
• Demonstrate mutual exclusion using named semaphores
• Use process creation (fork()) for concurrent read/write operations
• Implement a circular buffer for efficient message storage
• Handle process signals for graceful shutdown
System Requirements
• Linux operating system (POSIX compliant)
• GCC compiler
• POSIX shared memory support (sys/shm.h)
• POSIX semaphore support (semaphore.h)

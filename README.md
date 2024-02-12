# SantaJMS-Project

In this java enterprise application client i practiced Java Message Service, simulating producer/consumer communication through topic and queue

Project manager sends list of sweets through topic for workers.
Each worker take certain type of sweets that they know how to make from topic, and after they make sweets they send it as object message through queue to an elf.
Elf than waits certain amount of time and then collects all sweets from queue, then he goes back to waiting.

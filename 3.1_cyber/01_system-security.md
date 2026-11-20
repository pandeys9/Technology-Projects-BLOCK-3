# Exploring Your System's Security

## Task 1 --- List System Users

Run:

    cat /etc/passwd

### Screenshot

(Add screenshot here)
<img width="1920" height="1200" alt="20261120_150420_grim" src="https://github.com/user-attachments/assets/1f13b246-d08e-42a7-b234-01e2fa1a4a90" />


### Questions

1.  How many users exist on the system?
2.  Which accounts appear to be system accounts?
3.  Why do operating systems create system accounts?

### Reflection

Explain why understanding system users is important for cybersecurity.

------------------------------------------------------------------------

## Task 2 --- Inspect Running Processes

Run:

    ps aux

### Screenshot

(Add screenshot here)
<img width="1920" height="1200" alt="20261120_165437_grim" src="https://github.com/user-attachments/assets/ff56d77a-8fea-46ae-a940-080adf96fdeb" />
<img width="1920" height="1200" alt="20261120_165433_grim" src="https://github.com/user-attachments/assets/058f955b-29e4-4192-82ff-0a0669384f1d" />

### Questions

1.  Which processes are running as `root`?
2.  Why can processes running as root be dangerous?
3.  What could happen if a malicious program ran with root privileges?

### Reflection

What did you learn about system processes and security?

------------------------------------------------------------------------

## Task 3 --- Identify Open Network Ports

Run:

    ss -tuln

### Screenshot

(Add screenshot here)
<img width="1920" height="1200" alt="20261120_165537_grim" src="https://github.com/user-attachments/assets/81330895-1f36-461a-bf0a-d4bb445c7d12" />

### Questions

1.  Which ports are open?
2.  Which services appear to be listening?
3.  Why might open ports represent a security risk?

### Reflection

Explain the relationship between open ports and potential attack
surfaces.

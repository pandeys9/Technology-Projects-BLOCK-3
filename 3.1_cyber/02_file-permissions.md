# Understanding File Permissions

## Task 1 --- Create a File

Run:

    touch secret.txt
    ls -l secret.txt

### Screenshot

(Add screenshot here)
<img width="1920" height="1200" alt="20261120_152939_grim" src="https://github.com/user-attachments/assets/18bc4822-646d-4f71-bc98-30e6c5bc9131" />


### Questions

1.  Who owns the file?
2.  What are the default permissions?

### Reflection

Why is file ownership important in Linux systems?

------------------------------------------------------------------------

## Task 2 --- Restrict File Permissions

Run:

    chmod 600 secret.txt
    ls -l secret.txt

### Screenshot

(Add screenshot here)
<img width="1920" height="1200" alt="20261120_153145_grim" src="https://github.com/user-attachments/assets/f0f52426-2068-4f95-a5be-ac36179e80a0" />

### Questions

1.  Who can read the file now?
2.  Who cannot access it?


------------------------------------------------------------------------

## Task 3 --- Open Permissions (Security Risk)

Run:

    chmod 777 secret.txt
    ls -l secret.txt

### Screenshot

(Add screenshot here)
<img width="1920" height="1200" alt="20261120_153220_grim" src="https://github.com/user-attachments/assets/f30a07d4-ca27-4c64-a0d7-c4ed9aa8a5d5" />


### Questions

1.  Who can access the file now?
2.  Why might this configuration be dangerous?


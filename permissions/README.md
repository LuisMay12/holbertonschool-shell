# Permissions Scripts

## **Description**
This repository contains scripts related to file permissions, ownership, and user management in Linux.

---

## **Scripts Descriptions**

### **0. My name is Betty**
- **File:** `0-iam_betty`
- **Description:** Switches the current user to `betty`.

---

### **1. Who am I**
- **File:** `1-who_am_i`
- **Description:** Prints the **effective username** of the current user.

---

### **2. Groups**
- **File:** `2-groups`
- **Description:** Prints all groups the current user belongs to.

---

### **3. New owner**
- **File:** `3-new_owner`
- **Description:** Changes the owner of the file `hello` to `betty`.

---

### **4. Empty!**
- **File:** `4-empty`
- **Description:** Creates an empty file called `hello`.

---

### **5. Execute**
- **File:** `5-execute`
- **Description:** Adds **execute permission** to the **owner** of the file `hello`.

---

### **6. Multiple permissions**
- **File:** `6-multiple_permissions`
- **Description:** Adds:
  - **Execute permission** to **owner** and **group owner**.
  - **Read permission** to **others** for the file `hello`.

---

### **7. Everybody!**
- **File:** `7-everybody`
- **Description:** Adds **execute permission** to:
  - **Owner**
  - **Group owner**
  - **Other users**
  - The file `hello`.

> 🚨 **Note:** You are not allowed to use commas in the script.

---

### **8. James Bond**
- **File:** `8-James_Bond`
- **Description:** Sets the permissions of `hello` to:
  - **Owner:** No permissions (`---`).
  - **Group:** No permissions (`---`).
  - **Others:** Full permissions (`rwx`).

> 🚨 **Note:** You are not allowed to use commas in the script.

---

### **9. John Doe**
- **File:** `9-John_Doe`
- **Description:** Sets the mode of the file `hello` to: rwxr-x-wx

> 🚨 **Note:** You are not allowed to use commas in the script.

---

### **10. Look in the mirror**
- **File:** `10-mirror_permissions`
- **Description:** Sets the permissions of `hello` **to match** those of `olleh`.

---

### **11. Directories**
- **File:** `11-directories_permissions`
- **Description:** Adds **execute permission** to all **subdirectories** in the current directory **for all users**.
- **Regular files are not modified.**

---

### **12. More directories**
- **File:** `12-directory_permissions`
- **Description:** Creates a directory called `my_dir` with **permissions `751`**.

---

### **13. Change group**
- **File:** `13-change_group`
- **Description:** Changes the **group owner** of the file `hello` to `school`.

---

### **14. Owner and group**
- **File:** `14-change_owner_and_group`
- **Description:** Changes:
- **Owner** to `vincent`.
- **Group owner** to `staff`.
- **For all files and directories in the current directory**.

---

### **15. Symbolic links**
- **File:** `15-symbolic_link_permissions`
- **Description:** Changes:
- **Owner** to `vincent`
- **Group owner** to `staff`
- **For the symbolic link `_hello`**.

---

### **16. If only**
- **File:** `16-if_only`
- **Description:** Changes the **owner of `hello` to `vincent`** **only if** the current owner is `guillaume`.

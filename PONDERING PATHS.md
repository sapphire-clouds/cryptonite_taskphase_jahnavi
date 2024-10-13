# Pondering Paths

**Objective:** Learning the basics of Linux file paths

## The Root
**Challenge:** Invoke the `pwn` program using its absolute path.

![The Root](https://github.com/user-attachments/assets/7d2525dc-3c57-4c0a-bd0d-301773d2faef)  
**Flag acquired:** `pwn.college{AXrbplOEbpCTP_IlplE761PEIv8.dhzN5QDL2gzM2czW}`  

**Learned:** A path that starts with the root directory is referred to as an **absolute path**.



## Program and Absolute Paths
**Challenge:** Execute the `run` program located in the `/challenge` directory using its absolute path.

![Program and Absolute Paths](https://github.com/user-attachments/assets/99df1ecb-c0af-4d9e-8ed5-d3006c06d894)  
**Flag acquired:** `pwn.college{Qsb74jkLU7sYQjHeuwluqDBplA6.dVDN1QDL2gzM2czW}`



## Position Thyself
**Challenge:** Execute the `run` program in the `/challenge` directory after changing the working directory.

![Position Thyself](https://github.com/user-attachments/assets/b71381b1-b6c0-49f2-9203-0011e10a1841)  
**Flag acquired:** `pwn.college{AaqozDBrrffzy2rRkzXHRIvRRy1.dZDN1QDL2gzM2czW}`  
**Learned:** You can navigate around directories by using the `cd` (change directory) command and passing a path to it as an argument.



## Position Elsewhere
**Challenge:** Execute the `run` program in the `/challenge` directory after changing the working directory.

![Position Elsewhere](https://github.com/user-attachments/assets/3c90be63-e4e3-4ecc-af4f-a7295cd49378)  
**Flag acquired:** `pwn.college{k7VfRVYM8Nx2TsHBstGh_J1BkXT.ddDN1QDL2gzM2czW}`



## Position Yet Elsewhere
**Challenge:**Execute the `run` program in the `/challenge` directory after changing the working directory.

![Position Yet Elsewhere](https://github.com/user-attachments/assets/e5d7d53b-d790-48de-be0f-5f2cd4f82b11)  
**Flag acquired:** `pwn.college{kjkXAjFTcfc-fPxANVWLpo1mv_9.dhDN1QDL2gzM2czW}`



## Implicit Relative Paths, From /
**Challenge:**Execute the `run` program using relative path.

![Implicit Relative Paths, From /](https://github.com/user-attachments/assets/e6e18df2-c6ab-40c3-a546-932cfb74fe12)  
**Flag acquired:** `pwn.college{s9ysDyf95Pp7e6aIeMqIE5COPI7.dlDN1QDL2gzM2czW}`  
**Learned:** 
- A **relative path** does not start at root (i.e., it does not start with `/`).
- It is interpreted relative to your current working directory (**cwd**).
- Your **cwd** is the directory where your prompt is currently located.



## Explicit Relative Paths, From /
**Challenge:** Execute the `run` program using relative path.

![Explicit Relative Paths, From /](https://github.com/user-attachments/assets/c4fcf06b-8c50-4055-9fc6-d99e3efd64c8)  
**Flag acquired:** `pwn.college{gPJfDViicC3toDPwov3KCdxjDtW.dBTN1QDL2gzM2czW}`



## Implicit Relative Path
**Challenge:** Execute the `run` program using relative path.

![Implicit Relative Path](https://github.com/user-attachments/assets/583e8475-6d9d-4be6-841c-94d14660265b)  
**Flag acquired:** `pwn.college{goTwhtr6M-ddJ0tVdM6jaC1dEYr.dFTN1QDL2gzM2czW}`



## Home Sweet Home
**Challenge:** Use the `/challenge/run` program to write a copy of the flag to a specified file, ensuring the absolute path is inside your home directory and that the argument is three characters or less before expansion.


![Home Sweet Home](https://github.com/user-attachments/assets/19216396-84a6-452e-9d28-2f5cea115657)  
**Flag acquired:** `pwn.college{g3AncEnKjtXwZ4xctLq_6LWWsH1.dNzM4QDL2gzM2czW}`




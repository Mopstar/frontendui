# Timeline of the project and the hurdles encountered on the way

This markdown file will be an attempt to document the process of the creation **Subject Page (guarantor view)**.

___

## Timeline of commits and problems encountered

### 1. Initial Setup
**March 28 2025**
**Commits:** [`33d9ca6`](https://github.com/Mopstar/frontendui/commit/33d9ca6), [`271c43e`](https://github.com/Mopstarfrontendui/commit/271c43e), [`ed7e9ec`](https://github.com/Mopstar/frontendui/commit/ed7e9ec), [`8a16fe5`](https://github.com/Mopstar/frontendui/commit/8a16fe5), [`30d4dac`](https://github.com/Mopstar/frontendui/commit/30d4dac)

In the beginning we started with preparing the project for the future implemetation of it's functions and trying to get a feel of how some things work.

**Problems:**
The first problem with this project started with setting up **Docker Desktop** on my notebook. 

**Solutions:**
After searching online on multiple forums my partner for this project was able to find the cause of the problem in the UEFI settings of my notebook.

___

### 2. Application startup
**April 3 2025**
**Commits:** [`3771c7c`](https://github.com/Mopstar/frontendui/commit/3771c7c), [`13a585f`](https://github.com/Mopstar/frontendui/commit/13a585f), [`829a2a4`](https://github.com/Mopstar/frontendui/commit/829a2a4)

These commits were created during the first attempts to try and run the application.

**Problems:**
My partner was having problems with the functioning of a **CUDButton** component and couldn't figure out the reason for a while

**Solution:**
After consulting with our professor my colleague was able to identify the source of the problem and fix it.

___

### 3. First attempts at rendering the subject
**April 4 2025**
**Commits:** [`12a1592`](https://github.com/Mopstar/frontendui/commit/12a1592), [`035964b`](https://github.com/Mopstar/frontendui/commit/035964b), [`70faeb1`](https://github.com/Mopstar/frontendui/commit/70faeb1)

One of the problems we encountered in these commits was trying to figure out what fragments and queries are and how they accept and what they don't.

**Problems:**
We didn't know how the structure of GraphQL (queries) really work and how they are written.

**Solutions:**
After further studying the problem and reading the documentation we were able to make some progress.

___

### 4. Success at rendering contents of subject 
**April 9 2025**
**Commits:** [`717d75f`](https://github.com/Mopstar/frontendui/commit/717d75f), [`27dca59`](https://github.com/Mopstar/frontendui/commit/27dca59)

The commits on this day contain the successful outputs of the parameters of a **Subject** entity.

___

### 6. Removal of some contents in subject 
**April 15 2025**
**Commits:** [`fd6fe5c`](https://github.com/Mopstar/frontendui/commit/fd6fe5c), [`12e4ed4`](https://github.com/Mopstar/frontendui/commit/12e4ed4)

After consulting with my project partner and being told that some contents that are output are unnecessary I removed them from **SubjectMediumContent**.

___

### 7. Topics card logic and graphic output
**May 2, 15, 16, 28 2025**
**Commits:** [`0d0210f`](https://github.com/Mopstar/frontendui/commit/0d0210f), [`377630f`](https://github.com/Mopstar/frontendui/commit/377630f), [`88bf2d3`](https://github.com/Mopstar/frontendui/commit/88bf2d3), [`bb01e73`](https://github.com/Mopstar/frontendui/commit/bb01e73)

These commits represent the implementation of the logic for **Topic cards** and its graphic output.

**Problems:**
Figuring out what everything a semester contains.

**Solutions:**
After consluting our issue with some of our colleagues we were finally able to deal with the problem that happened.

___

### 8. Major issues in our team
**May 27 2025**

After receiving the news that my project partner is leaving the project and institution all together I had to deal from then on all by myself (with help from my other colleagues) with the project.

___

### 9. Modification of **SubjectMediumContent** and it's related files
**July 16 2025**
**Commits:** [`f6159b7`](https://github.com/Mopstar/frontendui/commit/f6159b7)

Through a lot of trail and lots of errors I was somewhat able to begin implementing mutations into the project.

**Problems:**
Unable to figure out the logic of GraphQL mutations and the functioning of **GraphiQL**

**Solutions:**
After consulting my colleague/roommate who has already successfully implemented mutations in his project I was able to make some progress.

___

### 10. Guarrant add/remove
**July 22 2025**
**Commits:**[`0fac384`](https://github.com/Mopstar/frontendui/commit/0fac384)

With lots of help from my roommate who also implemented **Guarrantor adding/removing** in his project I was finally able to assigne **Guarrantors** to a subject. Without the help of my roommate I would have been unable to implement it.

**Problem 1:**
The structure of the project started to become a mess and needed to be somewhat cleaned-up

**Problem 2:**
After updating my stack to the newest version to be able to create a needed mutation I found out that for an unknown reason all the mutations stopped functioning.

**Solution 1:**
I attempted to somewhat clean up the structure of the program that my partner left me with.

**Solution 2:**
Through a lot of nerves and almost ripping my hair out my roommate helped me by rolling back the **docker-compose** to a previous version that had functioning mutations.

___

### 10. Semester add/remove
**July 25 2025**
**Commits:**[`70733bc`](https://github.com/Mopstar/frontendui/commit/70733bc)

With lots of help from my roommate and another colleague I was able to implement **Semester adding/removing**.

**Problems:**
Once more I attempted to fix up the project structure left behind by my project partner.

**Solutions:**
After a lot of time I was able to make some order in the file names and their contents.

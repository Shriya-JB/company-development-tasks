# company-development-tasks

All the development and tasks performed at SpanIdea





\# Traceroute Source Code Analysis and Modification



\## Overview



This project focuses on exploring, compiling, executing, and modifying the Linux `traceroute` utility source code to understand low-level networking concepts, routing behavior, and system-level programming workflows.



The project also includes practical Git and GitHub workflow exercises such as branching, committing, pushing updates, and maintaining professional project documentation.



\---



\## Objectives



\- Understand how traceroute works internally

\- Explore TTL-based packet routing behavior

\- Compile and execute traceroute from source code

\- Modify runtime output behavior

\- Practice Linux build systems and Makefiles

\- Learn Git and GitHub version control workflows



\---



\## Technologies and Tools Used



\- Linux / Ubuntu (WSL)

\- Windows PowerShell

\- Git and GitHub

\- GCC Compiler

\- Makefiles

\- C Programming Language



\---



\## Project Structure



```text

company-development-tasks/

│

├── traceroute-2.1.5/

│   ├── include/

│   ├── libsupp/

│   ├── traceroute/

│   └── wrappers/

│

├── screenshots/

│

└── README.md

```



\---



\## Work Completed



\### 1. Environment Setup



\- Configured Linux environment using WSL/Ubuntu

\- Downloaded and extracted `traceroute-2.1.5`

\- Explored project directory structure and dependencies



\### 2. Source Code Exploration



Analyzed important directories including:



\- `include/`

\- `libsupp/`

\- `traceroute/`

\- `wrappers/`



Located the main traceroute implementation and studied packet routing logic.



\### 3. Compilation and Build Process



Compiled the project successfully using:



```bash

make

```



Generated a working traceroute executable from source code.



\### 4. Program Execution



Executed traceroute using:



```bash

./traceroute/traceroute google.com

```



Observed:

\- hop-by-hop routing

\- TTL decrement behavior

\- ICMP timeout responses

\- network path discovery



\### 5. Source Code Modification



Modified timeout output behavior inside the traceroute source code.



Original timeout output:



```text

\*

```



Modified timeout output:



```text

retrying

```



Recompiled the project to observe runtime behavior changes.



\### 6. Git and GitHub Workflow Practice



Practiced:

\- repository initialization

\- branch creation

\- commits and pushes

\- project documentation

\- screenshot uploads

\- branch-based development workflow



Commands used:



```bash

git init

git add .

git commit -m "message"

git push

git checkout -b branch-name

```



\---



\## Screenshots



\### Before Modification



!\[Before](screenshots/before.png)



\### After Modification



!\[After](screenshots/after.png)



\---



\## Key Concepts Learned



\- Traceroute packet flow

\- TTL (Time To Live)

\- ICMP responses

\- Linux compilation workflow

\- Source-level debugging

\- Git version control

\- GitHub branch workflow

\- System-level networking concepts



\---



\## References



Original traceroute source code was downloaded from the official SourceForge repository:



\- Traceroute 2.1.5 Source Archive  

&#x20; https://sourceforge.net/projects/traceroute/files/traceroute/traceroute-2.1.5/traceroute-2.1.5.tar.gz



Additional documentation:



\- Linux traceroute manual  

&#x20; https://linux.die.net/man/8/traceroute



\---



\## Disclaimer



This project was created for educational and learning purposes only.



The original traceroute source code belongs to its respective maintainers and contributors.



\---



\## Author



Shriya JB


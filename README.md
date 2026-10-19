<div align="center">

# ⚙️ Ansible for DevOps Automation

**Automate servers the way DevOps teams do: 32 hands-on topics taking you from agentless SSH setup and ad-hoc commands to playbooks, facts, conditions, loops, tags, Vault, roles, AWS EC2 and Windows hosts.**

![Ansible](https://img.shields.io/badge/Ansible-Automation-EE0000?logo=ansible&logoColor=white)
![YAML](https://img.shields.io/badge/YAML-Playbooks-CB171E?logo=yaml&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-Ubuntu%20%7C%20CentOS%20%7C%20RHEL-FCC624?logo=linux&logoColor=black)
![AWS](https://img.shields.io/badge/AWS-EC2-FF9900?logo=amazonwebservices&logoColor=white)
![Level](https://img.shields.io/badge/Level-Beginner%20to%20Advanced-6D4AE0)

</div>

---

## 🎯 About this course

Practical Ansible notes written while running every command and playbook on a real lab: a CentOS master node managing an Ubuntu worker on AWS EC2. Each topic shows the playbook, the command and the real output, in the order you should learn them.

---

## 📚 Course contents

### 🚀 Getting Started

| # | Topic |
|---|---|
| 01 | [Introduction to Ansible and Its Architecture](01.%20Introduction%20to%20Ansible%20and%20Its%20Architecture.md) |
| 02 | [Installing Ansible](02.%20Installing%20Ansible.md) |
| 03 | [Setting Up the Master and Worker Nodes](03.%20Setting%20Up%20the%20Master%20and%20Worker%20Nodes.md) |
| 04 | [Understanding the ansible.cfg File](04.%20Understanding%20the%20ansible.cfg%20File.md) |
| 05 | [Ad-Hoc Commands](05.%20Ad-Hoc%20Commands.md) |

### 📊 Facts and Variables

| # | Topic |
|---|---|
| 06 | [Ansible Facts and Custom Facts](06.%20Ansible%20Facts%20and%20Custom%20Facts.md) |
| 07 | [Ansible Variables](07.%20Ansible%20Variables.md) |

### 📜 Playbook Fundamentals

| # | Topic |
|---|---|
| 08 | [Understanding Ansible Playbooks](08.%20Understanding%20Ansible%20Playbooks.md) |
| 09 | [Printing Messages with Playbooks](09.%20Printing%20Messages%20with%20Playbooks.md) |
| 10 | [Copy and Fetch Modules in Playbooks](10.%20Copy%20and%20Fetch%20Modules%20in%20Playbooks.md) |
| 11 | [Understanding Inventory](11.%20Understanding%20Inventory.md) |

### 🛠️ Scripts and Remote Reporting

| # | Topic |
|---|---|
| 12 | [Running Bash Scripts on Remote Nodes](12.%20Running%20Bash%20Scripts%20on%20Remote%20Nodes.md) |
| 13 | [Checking Processes with Bash and Python Scripts](13.%20Checking%20Processes%20with%20Bash%20and%20Python%20Scripts.md) |
| 14 | [Collecting System Reports with Python, JSON and CSV](14.%20Collecting%20System%20Reports%20with%20Python%2C%20JSON%20and%20CSV.md) |
| 15 | [Collecting Remote Output with Playbooks](15.%20Collecting%20Remote%20Output%20with%20Playbooks.md) |

### 🔀 Conditions and Data Types

| # | Topic |
|---|---|
| 16 | [when Conditions](16.%20when%20Conditions.md) |
| 17 | [Installing Packages with when Conditions](17.%20Installing%20Packages%20with%20when%20Conditions.md) |
| 18 | [Managing Services with when Conditions](18.%20Managing%20Services%20with%20when%20Conditions.md) |
| 19 | [Data Types in Ansible](19.%20Data%20Types%20in%20Ansible.md) |
| 20 | [Variables, Type Checking and set_fact](20.%20Variables%2C%20Type%20Checking%20and%20set_fact.md) |
| 21 | [Installing Packages from a List Variable](21.%20Installing%20Packages%20from%20a%20List%20Variable.md) |

### ⌨️ Inputs, Operators and Loops

| # | Topic |
|---|---|
| 22 | [Taking User Input with vars_prompt](22.%20Taking%20User%20Input%20with%20vars_prompt.md) |
| 23 | [Reading Variables from JSON and YAML Files](23.%20Reading%20Variables%20from%20JSON%20and%20YAML%20Files.md) |
| 24 | [Passing Command-Line Arguments with extra-vars](24.%20Passing%20Command-Line%20Arguments%20with%20extra-vars.md) |
| 25 | [Operators and Filters](25.%20Operators%20and%20Filters.md) |
| 26 | [Loops in Playbooks](26.%20Loops%20in%20Playbooks.md) |

### 🧩 Organizing and Securing Automation

| # | Topic |
|---|---|
| 27 | [Running Specific Tasks with Tags](27.%20Running%20Specific%20Tasks%20with%20Tags.md) |
| 28 | [Ansible Vault](28.%20Ansible%20Vault.md) |
| 29 | [Ansible Roles](29.%20Ansible%20Roles.md) |

### ☁️ Cloud and Windows

| # | Topic |
|---|---|
| 30 | [Managing AWS EC2 Servers with Ansible](30.%20Managing%20AWS%20EC2%20Servers%20with%20Ansible.md) |
| 31 | [Connecting a Windows Machine with Ansible](31.%20Connecting%20a%20Windows%20Machine%20with%20Ansible.md) |

### 🧪 Practice

| # | Topic |
|---|---|
| 32 | [Ansible Practical Tasks with Solutions](32.%20Ansible%20Practical%20Tasks%20with%20Solutions.md) |
---

## 🚀 How to use it

1. Set up two machines: a Linux master (CentOS/RHEL or Ubuntu) and at least one worker node (a local VM or an AWS EC2 instance).
2. Follow topics 02 to 04 to install Ansible, create the Ansible user, set up SSH keys and point `ansible.cfg` to your inventory.
3. Work through the topics in order. Write each playbook with `vim <name>.yml`, check it with `ansible-playbook <name>.yml --syntax-check`, then run it with `ansible-playbook <name>.yml`.
4. Test yourself with the practical tasks in topic 32.

> Topic 30 needs an AWS account with an access key, and topic 31 needs a Windows machine.

---

## 👨‍🏫 About the author

**Ahmad Hassan** | AI/ML Engineer & Instructor with 5+ years of experience
1,500+ hours of live teaching, 100+ students mentored from medicine, business and engineering into data and DevOps roles.

[![Portfolio](https://img.shields.io/badge/Portfolio-ahmadhassan--aiops.github.io-0EA5A4)](https://ahmadhassan-aiops.github.io)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Ahmad%20Hassan-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ahmad-hassan-79a44b1a3)
[![GitHub](https://img.shields.io/badge/GitHub-ahmadhassan--aiops-181717?logo=github&logoColor=white)](https://github.com/ahmadhassan-aiops)

⭐ If these notes help you learn Ansible, please star the repo. It helps other students find it!

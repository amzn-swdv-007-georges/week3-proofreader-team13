# Code Hieroglyphics

## Mission Control

Communicate with your partner **only through Git**.

---

## Team Roles

Each team consists of **two students**.

|  Student  |         Role        | File                      |
| :-------: | :-----------------: | :------------------------ |
| Student A |       ✈️ Pilot      | `pilot_log.txt`           |
| Student B | 🛰️ Mission Control | `mission_control_log.txt` |

Each student edits **only** their assigned file.

---

## Setup

Open the **Codio Terminal**.

Clone the repository.

```bash
git clone https://github.com/amzn-swdv-007-georges/outback-comms-sat.git
```

Enter the repository.

```bash
cd outback-comms-sat
```

Navigate to your assigned team directory.

Example:

```bash
cd mission/team_01
```

Verify your location.

```bash
pwd
ls
```

Expected output:

```text
mission_control_log.txt
pilot_log.txt
```

---

## Repository Structure

```text
outback-comms-sat/
└── mission/
    ├── team_01/
    │   ├── mission_control_log.txt
    │   └── pilot_log.txt
    ├── team_02/
    │   ├── mission_control_log.txt
    │   └── pilot_log.txt
    ├── team_03/
    │   ├── mission_control_log.txt
    │   └── pilot_log.txt
    ├── team_04/
    │   ├── mission_control_log.txt
    │   └── pilot_log.txt
    ├── team_05/
    │   ├── mission_control_log.txt
    │   └── pilot_log.txt
    ├── team_06/
    │   ├── mission_control_log.txt
    │   └── pilot_log.txt
    ├── team_07/
    │   ├── mission_control_log.txt
    │   └── pilot_log.txt
    ├── team_08/
    │   ├── mission_control_log.txt
    │   └── pilot_log.txt
    ├── team_09/
    │   ├── mission_control_log.txt
    │   └── pilot_log.txt
    └── team_10/
        ├── mission_control_log.txt
        └── pilot_log.txt
```

Work **only** inside your assigned team directory.

---

## Git Workflow

Before editing your file, synchronize your local repository.

```bash
git pull
```

Downloads the latest changes from GitHub made by your partner.

After editing your file:

```bash
git status
git add .
git commit -m "message"
git push
```

---

## GitHub Authentication

The first time you run `git push`, Codio may request GitHub credentials.

Use your GitHub credentials.

```text
Username: Your GitHub username
Password: Your GitHub Personal Access Token (PAT)
```

---

## Communication Rules

* Work only inside your assigned team directory.
* Edit only your assigned file.
* Run `git pull` before making changes.
* No verbal communication.
* No chat or direct messages.
* Communicate only through Git.

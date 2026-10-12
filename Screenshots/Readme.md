# ShadowFox Cyber Security Internship: Level 1 (Beginner) Report

**Intern:** Bithin Krishna Radhakrishnan
**Batch:** October 04 (confirm; the original note read "October G4")
**Report date:** October 12, 2026

## Files

| File | Format | Purpose |
|------|--------|---------|
| `Cyber_Security_Intern_Report.pdf` | 

## What the report covers

The report follows the ShadowFox template: cover page, table of contents, list of figures, introduction and background, then one section per task with attack name, severity, steps with screenshots, impact, and mitigation. It ends with resources used and references.

| Task | Topic | Severity | Evidence |
|------|-------|----------|----------|
| 1 | Port scanning with `nmap -sV` (ports 25 and 80 open) | High (7.0 to 8.9) | Nmap screenshot |
| 2 | Directory enumeration with Gobuster, complete run (4613 of 4613 words) | Medium (4.0 to 6.9) | Gobuster screenshot |
| 3 | Plaintext credentials captured in Wireshark (`tfUName=User&tfUPass=` with password masked) | High (7.0 to 8.9) | Wireshark HTTP stream |

## Items to confirm before submitting

- **Batch:** The date was read as October 04. Change it if that is wrong.
- **Severity ratings:** Task 2 is rated Medium, because the directories found did not expose sensitive content. The other two tasks follow the sample reports and are rated High.
- **Table of contents and list of figures:** Page numbers are blank in the file. In Word, right-click the table of contents and choose "Update Field." Add figure page numbers by hand.
- **Task 1 port results:** The plain `nmap` run showed all 1000 ports as filtered, which conflicts with the `-sV` run. The report uses the `-sV` result, as you requested.
- **Gobuster timeout:** The scan logged one timeout at word 953. It then finished all words. The report notes this.
- **Task 3 login:** The page was `Login.asp` and the login failed ("Invalid login!"). The report says this.
- **References:** Check the links before submitting. I have not opened them.

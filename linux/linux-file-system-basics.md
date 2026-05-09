Puedes poner algo así en `linux/linux-file-system-basics.md`:

````md
# Linux File System Basics for SOC Investigations

## Overview

Linux navigation commands are essential during security investigations.  
SOC analysts use them to move through directories, inspect files, review logs, and organize investigation evidence during incident response activities.

---

# pwd

## Purpose

The `pwd` command shows the current working directory.

## Operational Use

During an investigation, analysts often work across multiple log directories.  
Knowing the exact location helps avoid modifying or analyzing the wrong files.

## Example

```bash
pwd
```

Example output:

```bash
/var/log
```

---

# ls

## Purpose

The `ls` command lists files and directories.

## Operational Use

SOC analysts use `ls` to identify available logs, scripts, suspicious files, or evidence collected during an investigation.

## Example

```bash
ls
```

Example output:

```bash
auth.log
syslog
apache2/
```

---

# cd

## Purpose

The `cd` command changes directories.

## Operational Use

Analysts move between system locations to inspect logs, review configurations, or analyze malware artifacts.

## Example

```bash
cd /var/log
```

---

# cat

## Purpose

The `cat` command displays file contents.

## Operational Use

SOC analysts use `cat` to quickly review logs, alerts, scripts, or configuration files during investigations.

## Example

```bash
cat auth.log
```

---

# mkdir

## Purpose

The `mkdir` command creates directories.

## Operational Use

Analysts create folders to organize collected evidence, exported logs, screenshots, and incident documentation.

## Example

```bash
mkdir incident-notes
```

---

# touch

## Purpose

The `touch` command creates empty files.

## Operational Use

SOC analysts use `touch` to create investigation notes, timelines, or evidence tracking files during incident response.

## Example

```bash
touch timeline.txt
```

---

# Conclusion

Basic Linux navigation commands are fundamental for SOC operations.  
Even simple commands help analysts efficiently navigate systems, review evidence, and maintain organized investigation workflows.
````

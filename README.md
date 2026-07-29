# HubSpot-Property-History-Cleaner
A Python script, built to "stack" the historical data of the HubSpot field values to make it easier to sort chronologically and trace changes.

Issue: HubSpot Property History exports come in a strange format. Where the list received would show you the list of objects and their IDs, but all the information is displayed to the right.
i.e. The columns would look something like Object ID, Email, Current Value, Changed By, Value (1), Changed By (1), Value (2), Changed By (2), and so on.
This makes it difficult to read if there had been multiple changes over time to one field.

```markdown
# HubSpot Property History Cleaner

Python script to transform messy HubSpot property history exports into readable, chronologically sorted data.

---

## 📌 Overview

HubSpot's property history exports are difficult to read—changes are scattered across rows without clear chronological ordering. This script parses the raw CSV, stacks historical changes by property, and outputs a clean, human-readable file for auditing and analysis.

---

## 🎯 Problem Statement

I regularly needed to audit HubSpot property changes for client reporting. The default export was a mess—multiple rows per property, unsorted timestamps, and hard-to-track changes. Manually sorting and reading this data took too long and was error-prone.

---

## 🛠️ Tech Stack

- Language: Python 3.x
- Libraries: Pandas
- Input/Output: CSV

---

## ✨ Key Features

- Parses raw HubSpot property history CSV exports
- Stacks changes chronologically by property
- Outputs a clean, readable CSV for auditing

---

## 🚀 Getting Started

### Prerequisites
- Python 3.6+
- Pandas (`pip install pandas`)

### Installation
```bash

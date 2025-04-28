# Automated Vulnerability Scanning and Reporting Using OpenVAS

## Project Overview

This project demonstrates how to automate the process of vulnerability scanning and reporting using OpenVAS. The goal was to create a working prototype that schedules scans, generates security reports, and emails them automatically without manual intervention. Tools used include OpenVAS, Linux bash scripting, Python automation, and cron scheduling.

---

## Project Objectives

- Install and configure OpenVAS for vulnerability scanning.
- Create and schedule automated scanning tasks.
- Generate vulnerability reports in PDF format.
- Automate emailing of scan reports to a designated recipient.
- Schedule the full automation pipeline using crontab.

---

## Project Features

- Full OpenVAS setup automation (installation and configuration).
- Manual setup of targets and tasks through the OpenVAS dashboard.
- Automatic scan execution on a schedule.
- PDF report generation after each scan.
- Automated email delivery of reports with file attachments.
- Scheduled execution using Linux cron jobs.

---

## Environment Setup

### Prerequisites

- Ubuntu or Debian-based Linux OS
- Administrative (sudo) privileges
- Internet connection
- Mail utilities (`mailutils` installed)

### Installation Steps

1. Update system packages and install OpenVAS:
   ```bash
   sudo apt update
   sudo apt install openvas -y

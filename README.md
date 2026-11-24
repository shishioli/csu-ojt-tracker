# CSU OJT Tracker

Student-facing internship monitoring website prototype for Cagayan State University.

## Demo access
- Student ID: `22-20872`
- Password: `student123`

## Features
- 350-hour internship progress tracker
- Pre-assigned current and previous company placements
- Company-specific QR codes
- Camera QR scanning and demo-scan fallback
- Time-in / time-out attendance flow
- Attendance history and CSV export
- Responsive student-only interface

## GitHub Pages
The repository includes a GitHub Actions workflow at `.github/workflows/deploy.yml`.
Open the **Actions** tab and manually run **Deploy CSU OJT Tracker to GitHub Pages** once. The workflow is configured to enable Pages and deploy the site. After a successful run, the site URL is:

https://shishioli.github.io/csu-ojt-tracker/

## Prototype limitations
This is a front-end demonstration. Login credentials, company assignments, QR validation, attendance records, and hour calculations are handled in the browser. Data is saved in localStorage on the current browser/device and does not synchronize across devices. It is not suitable for official attendance or production use without a secure backend, database, server-side identity verification, and trusted timestamps.

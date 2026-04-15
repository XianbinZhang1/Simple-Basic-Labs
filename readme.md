# Simple Basic Labs

This repository contains 8 simple, beginner-friendly labs that teach fundamental web browser operations. No Azure Portal or complex tools required.

## Labs Included

1. **Lab 01: Open Browser and Navigate to Websites** - Learn to open a browser and use the address bar to visit websites
2. **Lab 02: Search on a Website** - Learn how to use a website search box to find information
3. **Lab 03: Open and Manage Multiple Browser Tabs** - Work with multiple tabs and switch between them
4. **Lab 04: Use Browser History and Navigation Buttons** - Learn to use back/forward buttons and browser history
5. **Lab 05: Bookmark Your Favorite Websites** - Save websites for quick access later
6. **Lab 06: Explore Browser Settings and Homepage** - Customize your browser preferences
7. **Lab 07: Download Files from the Internet** - Download files from websites to your computer
8. **Lab 08: Refresh and Reload Pages** - Learn different ways to refresh web pages

## Lab Location

All lab files are located in:

- `Instructions/Labs/`

## Target Audience

These labs are designed for:
- UI drift detection testing (using tools like lab-drift-runner)
- QA teams testing browser consistency  
- Beginners learning web browser basics
- Visual regression testing

## ⚠️ Important: Optimized for Stable Testing

These labs have been **specifically optimized for UI drift detection** by using only static, non-changing websites:

✓ **Static websites used:**
- example.com, example.org, example.net  (completely unchanging)
- Wikipedia search structure (stable layout, searchable content)
- W3.org documentation (stable, non-dynamic)
- Browser settings pages (no dynamic content)

✓ **Why this matters for lab-drift-runner:**
- Same test run multiple times = same visual result
- No false positives from content changing
- Consistent page layouts
- No ads or real-time updates causing flakiness
- Reliable visual regression baseline

❌ **NOT used (they cause inconsistent results):**
- News sites (headlines/images change daily)
- Social media feeds (content updates constantly)
- Stock/weather dashboards (real-time data)
- Ad-heavy sites (ad rotation causes layout changes)

## Permission Popup Rule

If a browser permission popup appears (Location, Notifications, Camera, or Microphone), always click **Block** or **Not now** during these labs.

This keeps test runs consistent and prevents popups from blocking page steps.

## Lab Runner Note

To keep `labrunner scan` stable, start each lab with a browser window already open.

Avoid relying on **Start menu search** inside the lab steps, because some environments fall back to direct application launch when WinAppDriver is unavailable.

## Estimated Completion Time

Each lab takes approximately 5 minutes, so the entire series can be completed in about 40 minutes total.

## Getting Started

1. Navigate to the `Instructions/Labs/` folder
2. Open any lab file (markdown format)
3. Follow the step-by-step instructions
4. Each lab is independent - you can complete them in any order

## What You Will Learn

- Opening and navigating between websites
- Using search engines effectively
- Managing browser tabs and windows
- Using browser navigation controls
- Finding and downloading files
- Customizing browser settings
- Refreshing and troubleshooting pages

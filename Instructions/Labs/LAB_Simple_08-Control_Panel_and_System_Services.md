---
lab:
  title: 'Simple Lab 08: Control Panel and System Services'
  module: Basic Computer Skills
  description: Learn to access Control Panel and manage system services and devices
  duration: 15 minutes
  level: 100
  islab: true
  primarytopics:
    - Control Panel
    - System Services
    - Device Management
    - System Administration
---

# Simple Lab 08 - Control Panel and System Services

## Lab introduction

In this lab, you will learn how to access and use the Control Panel to manage system settings, devices, and services. The Control Panel provides access to essential system management tools that allow you to customize your computer and troubleshoot hardware and software issues.

## Estimated timing: 15 minutes

## Lab scenario

You need to manage various system settings and understand how your computer's devices and services are configured. In this exercise, you will explore the Control Panel and learn about system services and device management.

## Job skills

+ Task 1: Access Control Panel and explore system settings
+ Task 2: Manage devices and view system services

## Task 1: Access Control Panel and explore system settings

In this task, you will open the Control Panel and explore various system settings.

1. Click on the **Start menu** at the bottom left of the screen.

2. Type `Control Panel` in the search box and press **Enter**.

3. The Control Panel window will open. By default, it shows **Category** view with the following main categories:
   - System and Security
   - Network and Internet
   - Hardware and Sound
   - Programs
   - User Accounts and Family Safety
   - Appearance and Personalization
   - Clock and Region
   - Ease of Access

4. Click on **System and Security** to explore system-related settings.

5. In this section, you'll find options for:
   - **System** - View computer information
   - **Windows Defender Firewall** - Security settings
   - **Device Manager** - Hardware management
   - **Administrative Tools** - Advanced system tools
   - **Power Options** - Battery and power settings

6. Click on **System** to verify computer information (similar to Lab 04).

7. Return to the Control Panel main page by clicking **Control Panel** in the address bar.

8. Click on **Hardware and Sound** to explore:
   - **Devices and Printers** - View connected devices
   - **Sound** - Audio settings
   - **Power Options** - Battery and sleep settings
   - **Display** - Screen resolution and scaling

9. Click on **Devices and Printers**:
   - View connected printers (if any)
   - View installed mice, keyboards, and other peripherals
   - Note any unrecognized devices that may need drivers

10. Return to Control Panel and explore **Programs** to see:
    - **Programs and Features** - Installed applications
    - **Default Programs** - File associations
    - **Windows Update** - System updates

11. Close the Control Panel window.

## Task 2: Manage devices and view system services

In this task, you will access Device Manager and view system services.

1. Open the **Start menu** and search for `Device Manager` and press **Enter**.

2. The Device Manager window will open, showing various categories of devices:
   - **Disk drives** - Your storage devices
   - **Display adapters** - Graphics cards/video adapters
   - **Network adapters** - Ethernet and wireless network devices
   - **Sound, video and game controllers** - Audio devices
   - **Universal Serial Bus (USB) controllers** - USB devices
   - **System devices** - Core system components

3. Expand **Display adapters** by clicking the **+** symbol next to it:
   - Note your graphics card/video adapter name
   - For example: "NVIDIA GeForce GTX 1050" or "Intel UHD Graphics"

4. Expand **Network adapters**:
   - View your network adapter (Ethernet or Wi-Fi)
   - Note if the adapter is currently enabled or disabled

5. Expand **System devices**:
   - Explore the core system components

6. **Optional:** Right-click on a device and select **Properties** to view:
   - Device driver version
   - Device status
   - Driver details

7. Close Device Manager.

8. Now access **Services** to view system services:
   - Click the **Start menu**
   - Type `Services` and press **Enter**
   - Or use: Click **Start** > **Settings** > **Control Panel** > **System and Security** > **Administrative Tools** > **Services**

9. The Services window will show multiple system services such as:
   - **Windows Update** - System update service
   - **Windows Defender** - Security service
   - **Print Spooler** - Printing service
   - **Networking services** - Network connectivity

10. Observe the following columns for each service:
    - **Name** - Service name
    - **Status** - Running or Stopped
    - **Startup Type** - Automatic, Manual, or Disabled

11. **Do not modify any services** in this lab, just observe their current status.

12. Close the Services window.

## Summary

In this lab, you have successfully:
- Accessed the Control Panel and explored its main categories
- Located system settings and computer information
- Accessed Device Manager to view computer hardware
- Identified display adapters, network adapters, and other hardware devices
- Viewed device drivers and device properties
- Accessed Services to view system services and their startup status
- Understood the relationship between Control Panel, Device Manager, and Services

These system management skills are essential for troubleshooting hardware issues, managing devices, and maintaining system health.

---

**Important Note:** Always be cautious when modifying services or device drivers. Disabling critical system services or uninstalling drivers can cause system instability. In a real-world scenario, only make changes when you fully understand the consequences.

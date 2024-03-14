# VNC Installation Script for RHEL / CentOS 

This script automates the installation and configuration of a VNC (Virtual Network Computing) server on a CentOS/RHEL system. Follow the steps below to set up VNC:

## Step 1: Ensure Desktop Packages Installation
Make sure GNOME Desktop packages are installed. If not installed, the script will install them.

## Step 2: Install and Configure VNC
Installs the TigerVNC server and necessary fonts required for VNC.

## Step 3: Copy the VNC Configuration File
Copies the VNC template configuration file to the appropriate location.

## Step 4: Configure VNC Service
Appends necessary configuration lines to the VNC service file for systemd.

## Additional Configuration
Remember to set up a VNC password for users. You can use the `vncpasswd` command to set passwords for VNC users.

## Usage
1. Execute the script.
    ```bash
    ./vnc_installation.sh
    ```

2. Follow the prompts for installation and configuration.

3. Start using VNC to remotely access the system's desktop environment.

## Notes
- This script assumes a CentOS/RHEL system.
- Ensure proper permissions and security measures are in place when using VNC for remote access.

## Disclaimer
Use this script at your own risk. The author takes no responsibility for any damages caused by the use of this script. Always review and understand the scripts before execution.

For more information and troubleshooting, refer to the [TigerVNC documentation](https://tigervnc.org/doc/).

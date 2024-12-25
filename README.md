# FAQ

## **work still in progress i'll keep adding more each day contributions are always welcome**

## **What happens when you turn on your pc?**

When you turn on a PC, several steps occur in sequence as the system initializes. Here's a breakdown of the process:

1. **Power-On Self-Test (POST):**
    The **POST** is the first thing that happens when you power on the computer. It's a diagnostic process performed by the system's **BIOS** or **UEFI** firmware.
    - **Role:** The **POST** ensures that the hardware components required to run the system are working properly before the operating system (OS) is loaded.
    - **What is checked?**
        - **CPU:** Verifies that the central processing unit (CPU) is functional.
        - **RAM:** Checks if the system's memory (RAM) is present and functional.
        - **Storage Devices:** Ensures that devices like the hard drive (HDD) or solid-state drive (SSD) are connected and operational.
        - **Graphics:** Checks if the video card or integrated graphics is functioning.
        - **Peripherals:** Tests other components like the keyboard, mouse, and sometimes network adapters.
        - **Basic I/O:** Ensures that the basic input/output systems (keyboard, display, etc.) are working and ready to interact with the user.
    If any critical hardware fails during ==POST==, the system may display an error message or series of beeps (known as 'beep codes') indicating the problem. If everything passes, the system continues to the next stage.
2. **UEFI/BIOS Initialization**
    Once the **POST** is complete, the **BIOS (Basic Input/Output System)** or **UEFI (Unified Extensible Firmware Interface)** comes into play. **BIOS** is the traditional firmware that was used in older systems, but it has largely been replaced by **UEFI** in modern systems.
    - **What BIOS/UEFI does:**
        - **System Configuration:** The **BIOS/UEFI** loads configuration data stored in a non-volatile memory chip (often on the motherboard). This includes settings like **boot order**, **hardware configurations**, **system time**, and **password protection**.
            1. **Boot Order:**
                - **Definition:** The boot order refers to the sequence in which the BIOS/UEFI looks for devices to boot the operating system from when the computer is powered on.
                - **What it does:** The system checks each device in the specified order to find a bootable medium (e.g., hard drive, SSD, CD/DVD, USB flash drive). If the first device in the list doesn’t have a bootable OS, it moves to the next device in the order, and so on.
                - **Example:** If the boot order is set to "USB > CD/DVD > Hard Drive", the BIOS will first attempt to boot from a USB device. If none is found, it will try the CD/DVD drive before finally checking the hard drive.
            2. **Hardware Configurations:**
                - **Definition:** Hardware configurations refer to the settings and parameters that control how the computer’s hardware components (like CPU, RAM, storage devices, and graphics card) are recognized and initialized.
                - **What it does:** The BIOS/UEFI can be used to configure various hardware settings, including:
                    - Enabling or disabling certain hardware components (e.g., integrated graphics, Wi-Fi, USB ports).
                    - Setting parameters like memory timings, processor settings, and storage modes (e.g., AHCI or RAID for hard drives).
                - **Example:** If you want to enable or disable the integrated graphics card or adjust the amount of system RAM allocated to the integrated GPU, you can change these settings in the BIOS/UEFI.
            3. **System Time:**
                - **Definition:** System time refers to the date and time stored in the BIOS/UEFI, which helps the system track and maintain accurate time.
                - **What it does:** The BIOS/UEFI keeps track of the current time and date, which is important for logging events, scheduling tasks, and timestamping files. It also ensures that the system's clock starts at the correct time when the computer is powered on.
                - **Example:** When you turn on the computer, the BIOS/UEFI ensures that the date and time are correct. If the system time is incorrect, you can change it in the BIOS/UEFI settings.
            4. **Password Protection:**
                - **Definition:** Password protection in BIOS/UEFI refers to security settings that restrict access to certain system configurations or the entire computer.
                - **What it does:** It allows users to set passwords to prevent unauthorized access to the BIOS/UEFI settings or to the system itself during startup. Common options include:
                    - **Administrator password:** Prevents unauthorized users from accessing and changing the BIOS/UEFI settings.
                    - **User password:** Requires a password to boot the system, providing an additional layer of security.
                - **Example:** Setting a supervisor (admin) password ensures that no one can change critical settings in the BIOS/UEFI, while a system password can be used to prevent unauthorized access to the computer.
            These features, together, help configure how a system behaves at startup and ensure security and customization for the user.
        - **Hardware Initialization:** It initializes hardware like the CPU, chipset, memory controllers, and input/output systems. This step ensures that all the system's hardware can communicate properly with the operating system once it loads.
        - **Boot Process:** The **BIOS/UEFI** determines the sequence of devices it will check to find an operating system. This could be a hard drive, SSD, optical drive, USB drive, or network location.
        - **Secure Boot (UEFI only):** **UEFI** also has a security feature called Secure Boot, which ensures that only trusted software (such as an OS loader that is signed by a recognized certificate) can be loaded, preventing malware from interfering with the boot process.
After all the necessary initialization is complete, the BIOS/UEFI will look for a bootloader (the program that will load the operating system) on the boot device, and hand over control to it.
    - **Where is the BIOS/UEFI stored?**
    The **BIOS/UEFI** firmware is typically stored in a non-volatile memory chip on the motherboard, often referred to as a flash memory chip or EEPROM (Electrically Erasable Programmable Read-Only Memory).
        - **BIOS:** In older systems, it was usually stored in ROM (Read-Only Memory) chips, which are non-volatile and could not be easily updated.
        - **UEFI:** Modern systems with UEFI often store the firmware in a flash chip, which can be updated (or "flashed") as needed. This allows for firmware updates, bug fixes, and new features.
    The storage location is physically on the motherboard, and the firmware is loaded into system memory (RAM) when the computer powers on to begin the boot process.

## **Is it the same as running a virtual machine?**

## Other uses for Bios apart from the above

# Boot Menu Access without Keyboards

If your keyboard is not connected to your PC after restarting, you can still access the boot menu using a simple script. This readme provides a quick tutorial on using the following script:

```bash
shutdown /r /fw /t 1
```

## How It Works

- **shutdown:** Initiates a system shutdown or restart.
- **/r:** Specifies that the computer should restart after shutdown.
- **/fw:** Initiates the restart in the firmware user interface (UEFI/BIOS) to access the boot menu.
- **/t 1:** Sets the time delay before restarting to 1 second.

## Instructions

1. Open a text editor (e.g., Notepad) and paste the script:

    ```bash
    shutdown /r /fw /t 1
    ```

2. Save the file with a ".bat" extension, e.g., `boot_menu.bat`.

3. Double-click the saved file to execute the script.

4. Your computer will restart, and it should automatically open the boot menu during the restart.

**Note:** Ensure that your computer supports UEFI/BIOS access via the `/fw` option.

## Troubleshooting

- If the script doesn't work, check your system documentation to confirm UEFI/BIOS access via command-line options.
- Make sure that your system supports automatic boot into the firmware interface.
- If issues persist, consider connecting a keyboard temporarily to troubleshoot the underlying problem.

Now you can conveniently access the boot menu without the need for a connected keyboard after restarting your PC.

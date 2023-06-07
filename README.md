# Lenovo Tab M10 Debloat

This repository provides a list of safe commands to debloat a Lenovo Tab M10 tablet. Debloating refers to the process of uninstalling or disabling pre-installed system apps that are not necessary or desired by the user. By debloating your device, you can free up storage space and potentially improve device performance.

## Disclaimer

**Warning**: Modifying system apps or uninstalling them can have unintended consequences and may affect the normal functioning of your device. Proceed at your own risk, and make sure to create a backup of your data before making any changes.

## Table of Contents

- [Prerequisites](#prerequisites)
- [Instructions](#instructions)
- [Contributing](#contributing)
- [License](#license)

## Prerequisites

To use the debloating commands, you'll need the following:

1. A Lenovo Tab M10 tablet.
2. A computer with ADB (Android Debug Bridge) installed. ADB is a command-line tool that allows you to communicate with Android devices.

## Instructions

Follow the steps below to debloat your Lenovo Tab M10 using the provided commands:

1. Connect your Lenovo Tab M10 to your computer using a USB cable.
2. Enable USB debugging on your tablet by going to `Settings > About tablet > Build number` and tapping on it 7 times to enable Developer options. Then, go to `Settings > Developer options` and enable USB debugging.
3. Open a terminal or command prompt on your computer and navigate to the directory where ADB is installed.
4. Run the following command to verify that your tablet is connected and recognized by ADB:

    ```
    adb devices
    ```
    You should see your device listed as a connected device.

5. Now, you can use the provided debloat commands from the [debloat.md](debloat.md) file to uninstall or disable specific system apps. Refer to the debloat.md file for the list of commands.

**Note**: Make sure to read the comments in the debloat.md file for each command to understand the implications and potential effects of disabling or uninstalling specific apps.

## Contributing

Contributions to this repository are welcome. If you have additional safe commands or improvements, please feel free to submit a pull request.

## License

This repository is licensed under the [MIT License](LICENSE).

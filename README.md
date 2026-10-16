# Campus Management

Installers for **Campus Management**, the desktop app for managing campus operations: schedules, lecturers, attendance and payroll, and more. This repository holds releases only.

**[Download the latest version →](https://github.com/elioth-coder/campus-management-releases/releases/latest)**

| System | File |
|---|---|
| Windows 10 or 11 (64-bit) | `Campus-Management-<version>-windows-x64-setup.exe` |
| macOS on Apple silicon (M1 and later) | `Campus-Management-<version>-mac-arm64.dmg` |

Intel Macs are not supported.

## Installing

The installers are not signed yet, so your computer asks once before the first launch.

- **Windows:** run the `.exe`. If Windows says *Windows protected your PC*, click **More info → Run anyway**. It installs for your account only; no administrator rights needed.
- **macOS:** open the `.dmg` and drag **Campus Management** to **Applications**. If macOS blocks the first launch, open **System Settings → Privacy & Security** and click **Open Anyway**.

## Activating

Campus Management is activated once on each computer:

1. Open Campus Management. The activation page shows this computer's **Machine ID**.
2. Click **Copy** and send it to the person who manages your Campus Management licenses.
3. Paste the activation key you receive (or open the `.license` file) and click **Activate**.

On a new installation you then create the administrator account; the administrator adds accounts for the rest of the staff. Your data is not touched while Campus Management waits for activation, and **File → Back Up…** always works. After replacing a computer's main board or disk, Campus Management may ask again: send the new Machine ID for a new key.

## Updating

Campus Management checks once a day for a newer version (or use **Help → Check for Updates…**).

1. Click **Download**: the new version downloads in the background with a progress bar. You can keep working.
2. Click **Install now** when it is ready. The installer starts and Campus Management closes itself 5 seconds later.
   - **Windows:** follow the installer's steps.
   - **macOS:** in the window that opens, drag **Campus Management** onto **Applications** and choose **Replace**.

Your data and backups stay where they are; uninstalling never deletes them either. For extra safety, use **File → Back Up…** before updating.

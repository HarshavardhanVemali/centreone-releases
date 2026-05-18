# CentreOne Application Releases

Official distribution repository for the CentreOne mobile application. This repository hosts pre-compiled, standalone Android application packages (APK) for staff directory, attendance tracking, leave requests, and task management.

The source code for CentreOne is hosted in a secure, private repository. Standalone builds are published here to allow convenient direct download and installation for active personnel.

---

## Direct Download

To download the most recent, ready-to-install standalone build of the application:

* **[Download Latest Android APK](https://github.com/HarshavardhanVemali/centreone-releases/releases/latest)**

---

## Installation Instructions

Follow these step-by-step instructions to install or update the application on your Android device:

### 1. Download the Package
* Click the download link above.
* Select the `.apk` file under the **Assets** section of the latest release.
* Confirm any browser prompts asking to download the file.

### 2. Configure Device Permissions (First-Time Only)
Android operating systems restrict installation of applications directly from browsers or file managers by default. To allow the installation:
* Open your device **Settings**.
* Navigate to **Apps** > **Special app access** > **Install unknown apps** (this path may vary slightly depending on your Android version or device manufacturer).
* Select the app you used to download the package (e.g., Google Chrome, Firefox, or your system Files app) and enable **Allow from this source**.

### 3. Complete the Installation
* Locate the downloaded file in your browser's download history or use a file manager app to open the **Downloads** directory.
* Tap the `CentreOne-v[version].apk` file.
* Select **Install** (or **Update** if you are replacing an existing version).
* Once the installation completes, tap **Open** to launch the application.

---

## Automated In-App Update Checks

The application is configured to perform an automated check against this repository every time it is opened:
* If a newer standalone APK is published here, the app will display a notification prompt.
* Tapping the update button will take you directly to the latest download, making it easy to remain on the most current version.

---

## Technical Details

* **Target OS:** Android 5.0 (API 21) or higher
* **Architecture:** Supported on modern ARM and x86 architectures
* **Release Type:** Standalone APK build (Production Mode, offline JS bundle embedded)

# FebilTV Android TV APK

This project is configured to build automatically with GitHub Actions.

## Automatic APK build

1. Upload this project to a GitHub repository.
2. Open the repository's **Actions** tab.
3. Select **Build FebilTV APK**.
4. Click **Run workflow** (or push to `main`/`master`).
5. When the workflow finishes, open the run and download the **FebilTV-APK** artifact.
6. Extract the downloaded ZIP and install the APK on your Android TV / Google TV.

The workflow builds both debug and release APKs. The release APK is currently unsigned, so for normal sideload testing the debug APK is the easiest choice.

## App URL

The app opens the existing FebilTV website:
https://febilcp.github.io/febiltv/

## Important

Only use channels/streams you are authorized to access and redistribute. Public availability of a stream does not by itself establish redistribution rights.

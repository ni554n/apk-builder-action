# APK Builder GitHub Action

I've often wanted to test an app from an Android repository, but the developers didn't provide a downloadable APK.
While we could always clone the source code and build it ourselves, that often means downloading gigabytes of dependencies for what's typically a one-time use.

This GitHub action completely automates the _release_ or _debug_ APK building process, similar to a build server.

## Usage

1. [Fork](https://github.com/ni554n/apk-builder-action/fork) this repo on GitHub
2. Go to the [Build Android APK Workflow](/../../actions/workflows/build-apk.yaml) and select `Run workflow` dropdown menu
3. Enter the Git repository URL of the Android project
4. Run the workflow and wait
5. If the build is successful, the `apk-archive` artifact will appear at the bottom of the **Summary** tab (refresh the page if it does not). If the build fails, check the **build** logs under the **Jobs** section to determine the cause.

## Information

**Author:** Nissan Ahmed ([@ni554n](https://x.com/ni554n))

**Website:** [anissan.com](https://anissan.com)
<img src="https://ping.anissan.com/?repo=apk-builder-action" width="0" height="0" align="right">

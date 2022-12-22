# APK Builder

There are numerous times I wanted to run a sample APK from an Android app repo, but the author didn't provide an easy way to download the APK.

We can always clone the source and build the APK ourselves, but that entails potentially downloading gigabytes worth of dependencies for a one-time use.

This action can completely automate the _debug_ APK building process using GitHub Action.

## Usage

1. Fork this repo on GitHub.
2. Go to the [Build Android APK Workflow](/../../actions/workflows/build-apk.yaml) and select `Run workflow` dropdown menu.
3. Enter the Git repository URL of the Android project.
4. Run the workflow and wait for the `apk-archive` artifact to appear at the bottom of the **_Summary_** tab on that run.

## Acknowledgements

Based on the action from [this repo](https://github.com/Wsine/android_builder).

## Information

**Author:** [Nissan Ahmed](https://ni554n.github.io) ([@ni554n](https://twitter.com/ni554n))

**Donate:** [PayPal](https://paypal.me/ni554n)

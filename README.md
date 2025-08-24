# APK Builder GitHub Action

I've often wanted to test an app from an Android repository, but the developers didn't provide a downloadable APK.
While we could always clone the source code and build it ourselves, that often means downloading gigabytes of dependencies for what's typically a one-time use.

This GitHub action completely automates the _release_ or _debug_ APK building process, similar to a build server.

## Usage

1. [Fork](https://github.com/ni554n/apk-builder-action/fork) this repo on GitHub
2. Go to the [Build Android APK Workflow](/../../actions/workflows/build-apk.yaml) and select `Run workflow` dropdown menu
3. Enter the Git repository URL of the Android project
4. Run the workflow and wait for the `apk-archive` zip artifact to appear at the bottom of the **_Summary_** tab on that run

> [!TIP]
> If the gradle build fails, check the **_build_** logs under the **Jobs** section to determine the cause.

## Information

**Author:** [Nissan Ahmed](https://anissan.com) ([@ni554n](https://twitter.com/ni554n))

**Donate:** [PayPal](https://paypal.me/ni554n)
<img src="https://ping.anissan.com/?repo=apk-builder-action" width="0" height="0" align="right">

#  Mobile SDK UI Tests for Android

These tests are designed to validate the functionality of Android apps created using the MobileSDK CLI tools.  Unless otherwise specified each test should run against apps generated using native Java/Kotlin, Cordova, or React Native code.

## Running Tests

**For standard testing workflows**, use the Test Orchestrator CLI documented in the [main README](../README.md):

```bash
./test android <template>
```

See the main README for all available options including Firebase Test Lab execution, SDK version overrides, upgrade testing, and more.

## Development/Debugging

For development purposes, tests can be run directly in Android Studio by hardcoding the `packageName` variable in `TestApplication.kt` and running against an emulator or device that has the app associated with that package name installed. 

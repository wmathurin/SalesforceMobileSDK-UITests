#  Mobile SDK UI Tests for iOS

These tests are designed to validate the functionality of iOS apps created using the MobileSDK CLI tools.  Unless otherwise specified each test should run against apps generated using native Objective-C/Swift, Cordova, or React Native code.

## Running Tests

**For standard testing workflows**, use the Test Orchestrator CLI documented in the [main README](../README.md):

```bash
./test ios <template>
```

See the main README for all available options including iOS version selection, SDK version overrides, upgrade testing, and more.

## Development/Debugging

For development purposes, tests can be run directly in Xcode by hardcoding the `bundleString` variable in `TestApplication.swift` and running against a simulator that has the app associated with that bundle ID installed. 

# Expo CLI Build Errors: Native Module Linking Issues

This repository demonstrates a common, yet often cryptic, error encountered when using the Expo CLI: build failures due to problems linking native modules.  These issues frequently arise when integrating third-party libraries that require native code (e.g., camera access, geolocation).  The error messages themselves can be vague, requiring careful investigation.

The `bug.js` file contains an example demonstrating how native module integration can go wrong. The `bugSolution.js` file provides a solution demonstrating how to resolve the issue.

## Reproducing the Bug

1.  Clone this repository.
2.  Follow the setup instructions to install dependencies.
3.  Attempt to run the project using the Expo CLI (`expo start`).  Observe the build failure.

## Solution

The solution involves ensuring the native modules are correctly installed and linked.  See `bugSolution.js` for the corrected code and implementation steps.  Refer to the library documentation of the modules used for precise instructions.
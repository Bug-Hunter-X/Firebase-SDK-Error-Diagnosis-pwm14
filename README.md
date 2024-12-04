# Firebase SDK Errors: Project Misconfiguration and Missing APIs

This repository demonstrates a common error encountered when using the Firebase SDK: errors stemming from incorrect project configuration or missing enabled APIs.  The `bug.js` file showcases the faulty code, while `bugSolution.js` provides the corrected implementation.

## Bug Description
Attempting to use Firebase services (e.g., Authentication, Realtime Database) without proper setup in the Firebase console can lead to cryptic error messages and application crashes.  The root cause is usually a missing API enablement or an incorrect Firebase configuration in the client-side application.

## How to Reproduce
1. Clone this repository.
2. Run `bug.js`. Observe the error.
3. Run `bugSolution.js` to see the corrected behavior.

## Solution
Ensure that:
* The correct Firebase project is selected in your code.
* The necessary APIs (Authentication, Database, etc.) are enabled in the Firebase console.
* All configuration settings (database URLs, API keys) are accurate.

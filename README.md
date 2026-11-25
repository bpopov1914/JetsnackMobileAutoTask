
# Mobile Automation – Jetsnack Filters

## Overview

This project contains a mobile UI automation test created using **Maestro** for the Jetsnack Android application.

The automated test verifies that all expected category filter options are available in the Filters functionality.

## Automated Test

- **Test file:** `VerifyCategoryOptions.yaml`
- **Test case:** FIL-015 – Verify available category options

**Objective:** Verify that the category filter section displays all expected options:

- Chips & crackers
- Fruit snacks
- Desserts
- Nuts

## How to Run the Test

### Prerequisites

Before running the test, make sure you have:

- [Maestro](https://maestro.mobile.dev/) installed.
- An Android emulator or physical Android device connected.
- The Jetsnack application installed on the device.
- The project repository cloned locally.

### Execution

1. Start your Android emulator or connect your physical device.
2. Make sure the Jetsnack application is installed on the device.
3. Open Maestro and open the directory containing the YAML test file.
4. Run the test from the yaml file



Maestro will execute the defined UI interactions and verify the expected category options.

## Why I Chose This Scenario

I chose this scenario because category filtering is one of the core functionalities of the new Filters feature.

Verifying that all expected categories are available is a good starting point for mobile UI automation because:

- It validates that the required filter options are displayed.
- It covers an important part of the acceptance criteria.
- It is a relatively independent scenario that can be automated without complex test data.
- It provides a foundation for more advanced filtering tests.

## What I Learned

While working on this test, I gained practical experience with Maestro and its YAML-based approach to mobile UI automation.

In particular, I learned:

- How to structure and organize Maestro test flows.
- How to interact with Android application elements.
- How to verify that expected UI elements are displayed.

## What I Would Automate Next

As a next step, I would expand the automation coverage to include more functional scenarios:

| Priority | Test scenario | Purpose |
|---|---|---|
| High | Verify lifestyle filter options | Ensure all lifestyle options are displayed correctly. |
| High | Apply a single filter | Verify that results match the selected criteria. |
| High | Apply multiple filters | Verify that combined filtering works correctly. |
| High | Return without applying filters | Verify that unapplied changes are discarded. |
| Medium | Verify price range options | Ensure all price ranges are displayed correctly. |
| Medium | Verify sorting options | Validate the available sorting functionality. |
| Medium | Verify filter persistence | Check whether previously applied filters remain selected. |

I would also consider adding negative scenarios, such as verifying the behaviour when no products match the selected filters.


---

**Tools:** Maestro | YAML | Android UI Automation

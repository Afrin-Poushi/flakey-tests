# Flakey-tests
Flakey means “unreliable”.
Imagine running a test on your codebase that should consistently pass or fail based on the logic you've implemented. However, sometimes this test passes, and other times it fails—without any changes to the underlying code. Flaky tests—have non-deterministic outcomes.

Tests that should consistently pass or fail may sometimes pass and sometimes fail, depending on various factors such as the environment, timing, or even the order in which tests are run despite exercising unchanged code. 

# Description
The repository hosts a Node.js script designed for identifying flaky tests that are dependent on implementation details using the NonDex tool, along with those that are influenced by the order of execution via the iDFlakies tool.


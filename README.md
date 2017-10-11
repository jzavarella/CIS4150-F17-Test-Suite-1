# Test Suite 1
## Jackson Zavarella
###### 0929350
#### CIS4150
#### F17
#### University of Guelph

## Running the Suite:

To run the test suite simply copy the executable ``` cmulookup ``` into ``` testcases/bin/ ``` then run the command below. This command will run a shell script for testing and recording results. Each test will be printed to the screen with a 'PASS' or 'FAIL' as well as an identifier for what test was run. When all tests have executed, a summary of the results will be printed. If the suite is run as is, all tests will be executed with the full CMU dictionary that was provided in the zip folder with the project with the Disney words removed. If you wish to change which dictionary the tests use, replace ``` testcases/includes/full-dictionary ``` with whatever file you choose but be sure to name it ``` full-dictionary ```. Please note that this can cause my tests to perform unpredictably because they are written based on the dictionary I have provided.

``` shell
$	./runtests
```

**Be sure to place the executable in the ``` testcases/bin/ ``` folder. It MUST be named ``` cmulookup ```.**
(Side note. In order for the permissions tests to run correctly, you must remove the permissions on the file ``` testcases/includes/external_files/no-permissions.txt ```)

## File Structure

```
- Test_Suite
--| CIS4150-F17-TS1 // All files that were provided for cmulookup
--| testcases // Folder containing all test files
----| bin // Contains the 'cmulookup' executable
----| expected // Contains the expected result of all of the tests
----| includes // Contains the dictionary file and all test word files
------| external_files // Contains all test word files
----| output // Output of all tests will be recorded here in their own file
----| tests // Each test case has its own shell script that resides here
--| runtests // Shell script for running tests

```

## Completion
This assignment is fully complete. I have included 19 test cases which follows the guidelines the professor has specified in his email which states we should have no more than 20. Obviously this is not a complete test suite for the application so please refer to ``` QUESTIONS.md ``` for the complete list of test cases.

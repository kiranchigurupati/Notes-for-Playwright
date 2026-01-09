Playwright Automation Notes JS/TS: 1/8/26
NodeJS Platforms

1)Reliable E2E Testing-->Auto wait capability
2)Cross Browser Compatability-Chrome,firefox, safari
3)Multiplatform support--> Windows, linux, os
4)Multilingual flexibility-- JS,TS,JAVA,Python.


Advanced Features
1)Tracing and debuggings, takes screenshots and recordings
2)Network interception
3)Browser Context Management
4)Codegen Tool


Course Structure and approach
1)JS/TS Focus --Lanaguge bindings
TS-->Extension to JS-->JS+Additional Features
First write on JS as base on frame work level
2)Comprehensive coverage
3)Beginner friendly approach
4)Practical and Hands-On

Installation

we are using JS libraries to write Code
1)Node.js is platform engine for to run JS

1)Install Node.Js from website and install it
2)Add the Path in the environmental variable --NODE_HOME-->C/PGFiles/Nodejs
3) We need Visual Studio for editing the code
4)Install Playwright dependencies


Writing a Code
init-->initialize the project
1)Create a folder for the project in desktop
	1A)File-->Open Folder-->Folder will open
	1B)Install Playwright dependencies from Terminal by typing
	npm init playwright--->create a project/skeleton structure
	
2)Playwright.config.js is Test Runner for test cases
3)node_modules is ts for Jars
4)Tests folder is very IMP


Creating a test case always end with.spec.js as it is Javascript
1)UIBasisTest.spec.js
Check out the following files in terminal for Tests and config.js for E2E and Test Configuration

import annotation test from playwright module
1))))))))
const {test} = require('@playwright/test')

test takes(2 arguments)
test('testcase name',function()--->Test case
{
we write code here
JS is asynchronus
step1
step2
step3
await--->Hold on until another step completes and add async function
});

# sauce-espresso-test-android-app

Project that outputs the appApk (sauceapp-debug.apk) used in the bitrise-step-sauce-espresso-test.
The sauceapp-debug.apk is an empty app containing only espresso-accessibility, fragment, and fragmentn-test libraries. Those are needed if you are testing, through saucelabs, a library module that runs tests with "launchFragmentInContainer" function.

Read more here:
https://github.com/Backbase/bitrise-step-sauce-espresso-test

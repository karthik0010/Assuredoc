
# Self Healing


AssureQA leverages AI to identify and resolve script failures caused by unexpected errors. It employs a method based on script healing and character recognition principles, while also offering traditional element identification through locators. By enabling the script healing method, AssureQA provides flexibility during script execution.

To demonstrate this, let's take a dynamic site in which the elements inside this site are keep changing. Assume that we need to make a click on a button called "search and find dates" and it's locator is changing after some time.

![Enable Script healing toggle button](/images/Enable%20Script%20healing%20toggle%20button.png)
script1

1. Copy the url of this site and paste it on the recorder page.
2. Start recording the events like click on the "search and find dates" button.
3. Save the recordings and form a testcase
4. Goto the testcase page and select the created testcase
5. Open Config and Enable Self Healing Option marked in the picture.

![Saving with single id xpath](/images/Id%20adding%20in%20helenium.png)

6. The test case should be executed after saving.

![Changing the ID name](/images/Red%20border%20of%20helenium.png)

At this time, the test case will be passed. Assume that now that locator value has been changed.

But without making any changes to the saved locators, we just rerun the testcase. Due to script healing feature, the step with changed locator will be executed successfully by our AI. If script healing had happened, then the element on which the action performed will be marked with a red rectangular box.

The id name should change and click on save button again. Goto testcase again the and run the test case .

![Red border of helenium](/images/Saving%20with%20single%20id%20xpath.png)

A red border is displayed where script healing is performed; it contains the changed id name where the script healing is worked.

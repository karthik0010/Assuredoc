
# Self Healing


AssureQA leverages AI to identify and resolve script failures caused by unexpected errors. It employs a method based on script healing and character recognition principles, while also offering traditional element identification through locators. By enabling the script healing method, AssureQA provides flexibility during script execution.

![Id adding in helenium](/images/Changing%20the%20ID%20name.png)

First the user should give an Id name in the action of the picture eg :button click then click on save button and then copy the URL from right top.

![Enable Script healing toggle button](/images/Enable%20Script%20healing%20toggle%20button.png)

Create a test case with a copied URL containing a click action of which contains an Id name.
Open Config and Enable Self Healing Option marked in the picture.

![Saving with single id xpath](/images/Id%20adding%20in%20helenium.png)

Remove the other locators identified by the UI sensor and the ID should remain and save the test case. The test case should run after saving.

![Changing the ID name](/images/Red%20border%20of%20helenium.png)

The id name should change and click on save button again. Goto testcase again the and run the test case .

![Red border of helenium](/images/Saving%20with%20single%20id%20xpath.png)

A red border is displayed where script healing is performed; it contains the changed id name where the script healing is worked.
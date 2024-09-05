## Drive
Drive is the file storage system for Assure QA, where users can upload and store files.

On this page, users can attach small files and use their path in test steps.

Files are listed with details such as the file name (with a copy button), last modified date, and size. Users can also download, rename, and delete files by clicking the three dots.

![D-1](/images/D-1.png)

**Upload a file**

To upload a file to Drive, follow these steps:

1. Click on **Upload File**.

![D-2](/images/D-2.png)

2. Click on the **Upload File** button, then select the required/desired file.

![D-3](/images/D-3.png)

Then, a prefix can be assigned to the file being uploaded if desired, but it is not mandatory.

3.Click on the **Upload** option

![D-4](/images/D-4.png)

Now, the uploaded data will appear in the list on the Drive page.

![D-5](/images/D-5.png)

User can **download**, **Rename**,  and **delete** the uploaded file by clicking on kebab menu

![D-6](/images/D-6.png)

**Create folder**

User can create folders on this drive page.

1. Click on the **Create folder** option
![D-7](/images/D-7.png)

2. Enter the desired folder name in the dialog box that appears when the user clicks ‘Create folder’

![D-8](/images/D-8.png)

3. Click on **Create** button

![D-9](/images/D-9.png)

Created folder will be displayed on the drive page.

![D-10](/images/D-10.png)

Also, it is possible to upload files and create additional subfolders inside the created folder.

![D-11](/images/D-11.png)

User created folder can be renamed and deleted by clicking on the kebab menu.

![D-12](images/D-12.png)

Deleted file will disappear from the page.

![D-13](/images/D-13.png)

**Create Test step for Downloading File**

Inorder to automate the file download action in AssureQA, the drive acts as storage for the downloaded file user need to mention the file path at the definition field of "download file" keyword. User should be able to download this uploaded file, follow these steps:

**D.s-1**

Create a new folder in the drive.

**D.s-2**

Enter the folder name ('Drive-2') and click ‘Save.’

**D.s-3**

The new folder will be listed on the drive.

**D.s-4**

Then, go to the test case page and select ‘Download file.’

**D.s-5**

Click the ‘Download File’ step, enter the path including the new folder name ('Drive-2') and the file name in the definition field, then click ‘Save’.

Here, the folder name is **'Drive-2**' and the file name is **'1.1-MB-1.jpg**', the path will be

**'Drive-2/1.1-MB-1.jpg**'.

**D.s-6**

Click ‘Run’ to execute the test case and click the download button to download the file.

**D.s-7**

Return to the drive page, and click on the ‘Drive-2’ folder to verify that the downloaded file is stored correctly.

**D.s-8**

The downloaded file should be correctly stored in the ‘Drive-2’ folder.

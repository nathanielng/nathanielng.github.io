## Google Drive API Access

These are screenshots showing the procedure to create a project and service account
for API access to Google Drive

### 1. Create a new project

Go to [console.developers.google.com/project](https://console.developers.google.com/project).
To create a new project, click "+Create Project". Key in a project name and click "Create".

![Create a new project]({{ BASE_PATH }}/images/google_drive/01 Create new project.png)

Refresh the screen and the new project will appear:

![New project created]({{ BASE_PATH }}/images/google_drive/02 New project created.png)

### 2. Create a service account

Go to the credentials section (under APIs & Services)

![Go to credentials section]({{ BASE_PATH }}/images/google_drive/03 APIs & Services - Credentials.png)

Click the "+Create Credentials" button and choose the "Service account" option:

![Create credentials - service account]({{ BASE_PATH }}/images/google_drive/04 Create credentials - service account.png)

Enter a service account name & ID and click "Create"

![Enter service account details.png]({{ BASE_PATH }}/images/google_drive/05 Enter service account details.png)

Optionally, additional project access permissions may be added to the service account.
However, this is not necessary for accessing files on Google Drive.

![Give service account project access (optional)]({{ BASE_PATH }}/images/google_drive/06 GIve service account project access (optional).png)

### 3. Create a private key for the service account

![Create a private key for the service account]({{ BASE_PATH }}/images/google_drive/07 Create a private key for the service account.png)

![Choose the JSON key type]({{ BASE_PATH }}/images/google_drive/08 Choose the JSON key type.png)

![JSON key is saved to your computer]({{ BASE_PATH }}/images/google_drive/09 JSON key is saved to your computer.png)

![Service account JSON key is displayed]({{ BASE_PATH }}/images/google_drive/10 Service account JSON key is displayed.png)

﻿# Procore Integration with Docusign Documentation

This is the documentation for the Procore integration with Docusign.

## How to Install and Configure

### Installing the App on Docusign

*For more detailed instructions, please follow the [Docusign guide](https://support.docusign.com/s/document-item?language=en_US&bundleId=ous1698169987748&topicId=ctg1698170340729.html&_LANG=enus)*

**Step 1.** Go to [Docusign App Center](https://apps-d.docusign.com/app-center/extensionapps)

**Step 2.** Make sure you have Admin rights to install the Procore app from the Docusign App Center.
<img width="2560" height="1204" alt="image" src="https://github.com/user-attachments/assets/77249799-c3e9-41bf-a15f-3fc231221ef1" />


**Step 3.** Find the app and press "Install App", then press "Continue".

<img width="1920" height="875" alt="image" src="https://github.com/user-attachments/assets/3ab0ac11-e738-48c9-9451-4aa2571562aa" />

<img width="1920" height="877" alt="image" src="https://github.com/user-attachments/assets/dfa8ef04-3d1a-4ad8-9cab-1344dd8ce619" />

**Step 4.** After the app is installed, you'll be asked to link it to your Procore workspace. Choose the connection type — Private or Shared.

**Step 5.** Continue by pressing the "Login" button.

**Step 6.** Select Procore company, project, then click "Continue to Docusign".

<img width="2560" height="1157" alt="image" src="https://github.com/user-attachments/assets/a1444aaf-2399-4d98-9b8f-650bf12ea5b3" />


<img width="2560" height="1158" alt="image" src="https://github.com/user-attachments/assets/d6c5db82-41e8-45df-b207-5a07fa613f5e" />



If connected successfully, you can go to [Docusign App Center Manage](https://apps-d.docusign.com/app-center/manage). To manage connections or uninstall the app, please press the three dots next to the app name.

## How to Use the App

The Procore extension app bridges Docusign with your project data - automatically syncing signed documents, updating custom fields, and triggering workflows based on document events.

Whether you're managing subcontractor agreements, change orders, or insurance documents, this extension ensures project teams always have access to the latest version and status - without leaving Procore. After installation, Procore options appear in the Workflow Builder.

You can start by creating a new workflow by following [this link](https://apps-d.docusign.com/send/workflows) or pressing Agreements → Maestro Workflows → Create Workflow.

<img width="1920" height="889" alt="image" src="https://github.com/user-attachments/assets/ce8abf6d-53f6-4ec0-a6a5-c0786e2cb7c8" />

In the workflow, when adding a new step, you'll see three Procore options:

- **File Upload** – Upload the file from Procore to use it later for Workflow.
- **Writeback to Procore** – Update or create new data directly in your Procore workspace.
- **Read from Procore** – Retrieve row data (such as IDs or values) for use in other steps.

<img width="1204" height="404" alt="image" src="https://github.com/user-attachments/assets/b88edcab-1e76-4f9f-a855-84bd313e9633" />

### ℹ️ Configuring "Writeback" to Procore

- Select "Writeback to Procore" from the app available options.

<img width="626" height="408" alt="image" src="https://github.com/user-attachments/assets/d061f5b3-9e42-45a4-b614-eb26f60995d8" />


- Select your connection, as well as the Procore object.

<img width="1226" height="666" alt="image" src="https://github.com/user-attachments/assets/8a2d9671-d006-48ec-bb10-4f4969e69e83" />

<img width="1262" height="748" alt="image" src="https://github.com/user-attachments/assets/8a0bda4a-f69a-42aa-a9c6-14a68b74c8ea" />

- When you select Update or Create in the "Write setting," the system will either update an existing value or create a new one. Ensure that you select the appropriate option based on your needs.

<img width="1302" height="682" alt="image" src="https://github.com/user-attachments/assets/4f9812cc-a6b4-4952-9c5e-02a9b87d1413" />

- Add or remove fields that you are willing to write to. **Be aware that "Fields" in this case are field names inside your Procore workspace.**

<img width="1920" height="890" alt="image" src="https://github.com/user-attachments/assets/0ca868e9-2aa2-49fa-b964-fbddc0fc271d" />

- After selecting fields, choose which Docusign fields to write to Procore.

<img width="1236" height="1074" alt="image" src="https://github.com/user-attachments/assets/ceabbd96-b95a-4591-a39d-88ce3b09736b" />

- Finally, select conditions for comparison and write back to Procore.

- In the end, press Apply and proceed to the next Maestro steps.

### ℹ️ Configuring "Read" from Procore

- Select "Read from Procore" from the app available options.

<img width="1232" height="882" alt="image" src="https://github.com/user-attachments/assets/afd7146d-45de-487c-8c02-24b43eeb70db" />

- Select your connection, as well as the Procore object.

<img width="1224" height="798" alt="image" src="https://github.com/user-attachments/assets/42f4dfee-7097-4bbe-8c61-6b44b473afef" />

- Select your fields from which to read.

<img width="1230" height="1142" alt="image" src="https://github.com/user-attachments/assets/f730c875-4008-4151-9579-22b574a373ef" />

- After pressing Apply, the "Read" step is successfully added to your workflow. You can now use the retrieved Procore data in the following steps.

### Supported Field Types

You can use the following Procore field types in Maestro workflows:

- string
- boolean

<img width="1286" height="1038" alt="image" src="https://github.com/user-attachments/assets/8849eb7d-ba59-42e6-9a4c-0809784a78bb" />

## How to Reconnect the App

You can connect a Procore account to Docusign Maestro. When you connect to Maestro, you can build workflows that read from and write to your Procore data. If you experience problems with your Procore connection, you can reconnect Maestro and Procore.

Use this procedure to reconnect the application:

- Log in to your Docusign eSignature account with account administrator credentials.

- In a new browser window, go to the appropriate environment for your account ([Production](https://apps.docusign.com/app-center) or [Demo](https://apps-d.docusign.com/app-center)).

- Select the Procore icon and click "Manage Connections".

- Select the three-dot menu icon next to a connection and choose "Reconnect".

The page refreshes.

<img width="1920" height="913" alt="image" src="https://github.com/user-attachments/assets/cf06babb-6466-48fa-98c1-ec06b37858fd" />

<img width="1920" height="645" alt="image" src="https://github.com/user-attachments/assets/c53bfdf0-a0f2-4e17-9e0d-8957bb7faf3e" />


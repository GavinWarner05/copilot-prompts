# Create a Patch Function to Update a record in Powerapps using Github Copilot

!["GitHub Copilot interface in Visual Studio Code showing a suggestion prompt. The prompt says: 'Make a patch function to update data in PowerApps using PowerFx.' There are options to accept, discard, or view changes. The 'Accept' button is highlighted in blue, along with discard and other options for interacting with the Copilot suggestion."](./assets/Github_Copilot_Patch_Function_Image.png)

## Summary

The Patch function in Power Fx is used to update or modify records in a data source. It works by specifying three main components: the data source you want to update, the specific record you wish to modify, and the new values for the fields you want to change. To identify the record, you typically use a function like "LookUp" based on a unique identifier or condition. Once the target record is found, the Patch function allows you to update specific fields without affecting the rest of the data. This is a powerful method for making updates to individual records within a data source while keeping the other data intact.

## Prompt💡

Make a patch function to update data in powerapps using powerfx

### Descriptionℹ️

The Patch function in Power Fx allows you to update specific fields in a record from a data source without affecting the rest of the data. 

## Contributors 👨‍💻

[Gavin Warner](https://github.com/GavinWarner05)

## Version history

Version|Date|Comments
-------|----|--------
1.0|October 03, 2024|Initial release

## Instructions 📝

### Install Github Copilot Extension
1. Open Visual Studio Code.
2. Go to the Extensions panel(you can open it by clicking on the Extensions icon on the left toolbar or pressing Ctrl+Shift+X).
3. Search for "Github Copilot" and install the extension.

### Sign in to GitHub
1. Once the extension is installed, you will need to sign in with your GitHub account.
2. After installation, Visual Studio Code will prompt you to authenticate. Follow the steps to sign in.

### Create File for Github Copilot Prompt
1. Click on **File** in the top menu and select **New File**.
(Alternatively, you can use the shortcut **Ctrl+N**(Windows) or **Cmd+N**(Mac) to create a new file.)
2. Name the file whatever you'd like.(Make sure to give the file the appropriate extension for the language e.g., **.txt**)
3. Start writing your prompt by pressing **Ctrl+i** and entering the desired prompt.

## Prerequisites

* [Copilot for Microsoft 365](https://developer.microsoft.com/microsoft-365/dev-program)
* [Microsoft Word](https://www.office.com/)

## Help

We do not support samples, but this community is always willing to help, and we want to improve these samples. We use GitHub to track issues, which makes it easy for  community members to volunteer their time and help resolve issues.

You can try looking at [issues related to this sample](https://github.com/pnp/copilot-prompts/issues?q=label%3A%22sample%3A%20word-write-prompt-guidance-best-practices-prompt%22) to see if anybody else is having the same issues.

If you encounter any issues using this sample, [create a new issue](https://github.com/pnp/copilot-prompts/issues/new).

Finally, if you have an idea for improvement, [make a suggestion](https://github.com/pnp/copilot-prompts/issues/new).

## Disclaimer

**THIS CODE IS PROVIDED *AS IS* WITHOUT WARRANTY OF ANY KIND, EITHER EXPRESS OR IMPLIED, INCLUDING ANY IMPLIED WARRANTIES OF FITNESS FOR A PARTICULAR PURPOSE, MERCHANTABILITY, OR NON-INFRINGEMENT.**

![](https://m365-visitor-stats.azurewebsites.net/SamplesGallery/copilotprompts-m365-my-name-mentioned-prompt)

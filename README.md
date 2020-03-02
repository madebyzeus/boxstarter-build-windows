# Boxstarter Script for Windows
<a href="http://boxstarter.org/">Boxstarter</a> lets you automate multiple Windows builds by using Chocolatey. It will also let you configure Windows system settings such as always showing hidden file/folders etc.

1. Verify that Chocolatey is installed on your local machine by running ```choco --version```. If Chocolatey is not installed, download and run the choco-install.ps1 file from this repo.
2. Once the Chocolatey install is compete, install the Boxstarter software package by running ```CINST Boxstarter``` from an elevated command prompt. This will allow you to run the Boxstarter Shell. If you know Powershell then use Powershell otherwise the Boxstarter Shell is sufficient enough to use to deploy your installs.
3. You can use and run the default ```chocolatey-recipe.txt``` file if a simple install of the already committed packages is what you need. Otherwise feel free to fork this project and modify as needed.

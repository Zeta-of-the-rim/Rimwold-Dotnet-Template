# Rimworld Dotnet Template
A dotnet template for quickly making Rimworld mods via Command line or your favorite IDE.


## Getting Started
[Download Git](https://git-scm.com/)

Open Git Bash to where you want to download the files to. 

Clone this project
```bash
git clone https://github.com/Zeta-of-the-rim/Rimwold-Dotnet-Template.git "RimMod"
```

Enter directory
```bash
cd RimMod
```

Add the template
```bash
dotnet new --install .
```
## Usage
In your Rimworld mod folder, run the following commands:
```bash
mkdir "Your Mod Name"
cd "Your Mod Name"
dotnet new RimMod
```
This will create a new mod with the name you specified.
After that, you can open the project in your favorite IDE and start coding.
I recommend staring by changing the name and author of the mod in the About.xml file.

## Adding to Rider
If you are using Rider, you can add the template to the list of available templates.
To do this, open Rider, go to File -> New -> New Solution.
under the "More Templates" tab, click the "Install Template..." button, then navigate to the folder where you cloned the repo and select the folder.
click "Reload" and scroll down to the Other section.
You should see Rimworld Mod Template there.

## Uninstalling
To uninstall the template, run the following command:
```bash
dotnet new --uninstall RimMod
```
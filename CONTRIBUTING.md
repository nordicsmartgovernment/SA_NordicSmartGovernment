# Contribute to Nordic Smart Government arkitecture

## Instructions
To publish you changes to github, you have to be a member of the team arkitektur-teamet. Then you can follow this reciepe:

First you have to install tools and plugin as described in [README.md](README.md)

### Work with the model in Archi
So far branching is unsupported in Archi, therefore you have to follow a certain pattern when updating the model

#### Update HTML-report
When you have done substantial changes in the model, you have to update the HTML-report. (This is a read-only html-version of the model, where stake holders can click around)
1. Select File->Report->HTML...
2. Select docs-folder in the project.
3. Press OK

The Docs-folder you will most easily find by finding the Main->File in Properties-tab for the model. Replace ".git\temp.archimate" with "docs". You will get a warning that you are replacing existing content. This is ok, so press "Yes" in the dialog.

#### Commit
1.  After you have done changes, store this in normal way in Archi, e.g. CTRL+s
2.  Select Collaboration->Commit Changes.
3.  Fill out the fileds, use a understandable Commit message
4.  Press Ok

#### Publish changes to Github
1.  After you have comitted the changes, you will publish these on Github
2.  Select Collaboration->Publish Changes
The change will then be published on Github.

### What standards and methods have we been using?
*   Methodology is baserd on [TOGAF 9](http://pubs.opengroup.org/architecture/togaf9-doc/arch/)
*   Meta modell is [Archimate 3](http://pubs.opengroup.org/architecture/archimate3-doc/)

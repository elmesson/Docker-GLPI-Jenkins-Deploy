# Gitlab Integration

Gitlab Integration is a plugin to use into GLPI - Gestionnaire Libre de Parc Informatique when the tickets needs to integrate with Gitlab.

## Installation

Clone this repository inside the folder plugins of GLPI

Configure parameters to use Gitlab Integration:
  - Rename the file ```gitlabintegration.ini.example``` to ```gitlabintegration.ini```
  - Change values of variables ```GITLAB_URL``` and ```GITLAB_TOKEN```.
    - ```GITLAB_URL```: receive the url to access gitlab repository
    - ```GITLAB_TOKEN```: receive the token to access gitlab repository

After this, is necessary install the plugin and enabled this.

## Giving permissions to users profiles

For give permission is necessary access the option ```Permissions Gitlab``` located at ```Administration``.

Then it's possible adds any available profile.

## Creating an Issue

To create an Issue, a ticket must be opened. 
After located the open ticket, on the end of the ticket form has a field called of ```Gitlab Project```. In this field must be selected the project of Gitlab respository and then click on ```Create Issue```.

After did this, the Issue was been created with successfully!
This playbook notifies a Microsoft Teams user that a Microsoft Sentinel Incident has been assigned to them.
It is designed for hybrid SOCs to enable assignment of incidents to employees other than core SOC analysts.

The user is given a prompt as seen below.

![MicrosoftTeams-image](https://user-images.githubusercontent.com/71527532/221387660-bc742008-773b-4c5c-8ae7-5452b637cc52.png)

The user can enter a email address of another user and the incident will be assigned to them (with another invocation of this playbook.

Should the user reject the assignment, a new Sentinel Incident will be created.


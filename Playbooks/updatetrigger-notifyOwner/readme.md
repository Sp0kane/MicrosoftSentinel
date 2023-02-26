This playbook notifies a Microsoft Teams user that a Microsoft Sentinel Incident has been assigned to them.
It is designed for hybrid SOCs to enable assignment of incidents to employees other than core SOC analysts.

The user is given a prompt as seen below.

![MicrosoftTeams-image](https://user-images.githubusercontent.com/71527532/221387660-bc742008-773b-4c5c-8ae7-5452b637cc52.png)

The user can enter an email address of another user and the incident will be assigned to them (with another invocation of this playbook.

Should the user reject the assignment, a new Sentinel Incident will be created.

![MicrosoftTeams-image (2)](https://user-images.githubusercontent.com/71527532/221387993-926cb866-f3fe-440b-bcf5-51c07f3fadbc.png)

![MicrosoftTeams-image (3)](https://user-images.githubusercontent.com/71527532/221387995-5dd3a2c5-a152-4f92-be49-4ca7b65bceb7.png)

You shold exempt core SOC personnel from these notifications by listing them in the initial boolean.

Hope it helps.

[![image](https://user-images.githubusercontent.com/71527532/221388116-3dfff954-fe6a-47ed-af08-13d7d4486c7b.png)](https://portal.azure.com/#create/Microsoft.Template/uri/https://raw.githubusercontent.com/Sp0kane/MicrosoftSentinel/main/Playbooks/updatetrigger-notifyOwner/azuredeploy.json)

This is an improved version of the built-in Reset-AADPassword-TncidentTrigger playbook found in Microsoft Sentinel.
It will find a "trusted" phone number belonging to the user in need of a temporary password, then SMS that password to them.

It depends upon Azure Communications and a bunch of other stuff that should be obvious when looking over the logic app.


![MicrosoftTeams-image (7)](https://user-images.githubusercontent.com/71527532/221435904-8c0ccc11-6e5a-4f95-ab1c-013bccf8e297.png)

![MicrosoftTeams-image (8)](https://user-images.githubusercontent.com/71527532/221435908-e55ca1ab-22cf-4d0b-af45-9ac603198bef.png)


Praise to and inspiration from the Microsoft Sentinel templates.

[![image](https://user-images.githubusercontent.com/71527532/221388116-3dfff954-fe6a-47ed-af08-13d7d4486c7b.png)](https://portal.azure.com/#create/Microsoft.Template/uri/[https://raw.githubusercontent.com/Sp0kane/MicrosoftSentinel/main/Playbooks/Reset-AADPassword-Send-SMS-TncidentTrigger/azuredeploy.json)

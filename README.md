# Home Assistant Local Add-on: Aeroh Cloud

Integrate your Aeroh devices with Home Assistant.

## About

[Aeroh](https://aeroh.org/) is working on a smart home product line inspired by open source.

Use this integration to integrate [Aeroh Link](https://aeroh.org/link) with Home Assistant, and control any infrared remote controlled appliance from Home Assistant.

Aeroh also provides an [Open API](https://apidocs.aeroh.org/docs/cloud/v1/) if you wish to build a custom integration with a programming language of your choice.

## Setup Instructions

This add-on is currently under development, and it's not part of [Home Assistant Core](https://www.home-assistant.io/integrations/) or [Community Add-ons](https://addons.community/) yet. Once we determine that the add-on is ready for prime time, we will work with the Home Assistant Team to publish this integration into their core or community add-on repository. In this meantime, if you are interested in trying out this add-on, follow these steps:

### Step 1

Enable network file sharing on Home Assistant by setting up **Samba Share** add-on from the official add-on repository.

Official instructions to setup Samba Share can be found in the add-on documentation page within Home Assistant, or from the add-on [github repo](https://github.com/home-assistant/addons/blob/master/samba/DOCS.md).

### Step 2

With Samba Share, Home Assistant will expose following directories: `addons`, `backup`, `config`, `media`, `share`, `ssl`. You will need to mount `addons` directory on your computer.

Your sambda share link should be `smb://homeassistant.local`, but if that doesn't work, use the IP address instead: `smb://IP_ADDRESS`

Use the following instructions to mount the network file system:

[Windows](https://www.techrepublic.com/article/how-to-connect-to-linux-samba-shares-from-windows-10/)<br>
[MacOS](https://ag.montana.edu/it/support/smb-macs.html)<br>
[Ubuntu](https://askubuntu.com/questions/486450/how-to-connect-to-smb)

### Step 3

Copy this respository to the addon directory.

In Home Assistant web interface, go to **Settings** > **Add-ons** > **Add-on Store**

If you don't see **Aeroh Cloud** under **Local add-ons** section, click on **Check for updates** from the **3-dot menu** on the top right corner, and then refresh the page. **Aeroh Cloud** add-on should now show up.

You can now click on the **Aeroh Cloud** add-on and click on **INSTALL** button to install the add-on.


If you run into any challenges or need any support, feel free to reach out to us by [filling this contact form](https://aeroh.org/contact).




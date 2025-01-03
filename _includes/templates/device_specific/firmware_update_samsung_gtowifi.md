### For all devices

1. Download the latest firmware for your model [here](https://github.com/lifehackerhansol/gto-fw/releases) (All `.tar.md5` files)
    {% include alerts/note.html content="You can find your model number on the back of your device!" %}
1. Flash the just downloaded files using Odin. You can have a look at the [recovery installation instructions]({{ device | device_link: "/install" | append: "#installing-lineage-recovery-using-odin" | relative_url }}) if you forgot how to do that.
    {% include alerts/note.html content="The filename will give you a hint on which slot to flash each file to!" %}

### If you already installed a custom recovery

{% include alerts/warning.html content="The following steps only apply if you have a custom recovery installed! You MUST follow this section if you installed a custom recovery. Do NOT flash if you haven't yet!" %}

1. Download [this](https://sourceforge.net/projects/lifehackerhansol-android/files/gto-unlock/1-unlocked-aboot.tar) package.
    {% include alerts/warning.html content="If you skip this step, your device will not boot!" %}
1. Flash this file via Odin using the BL option.
    * After this step, your bootloader version will display as `T290XXS3ATF1`.

{% include snippets/fw_update_success.md %}

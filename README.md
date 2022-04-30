# [![Onix Client Logo](https://raw.githubusercontent.com/HugoNotHere/OnixClientFaq/main/onixlogosmall.png)](https://discord.gg/OnixClient) Onix Client FAQ

Onix Client is a legit modification for Minecraft Bedrock Edition. Sometimes, you may need help setting it up, and this is what the FAQ is for. This has all of the common questions about Onix Client, installation, and usage. If you have any suggestions for this page, please fork this repository, edit it, and then create a pull request. Finally, if you have any other questions please join the Discord server and create a ticket there. **Note: Before using the client make sure you agree with the Onix Client License which is found at the bottom of this page or [here](https://ocwebsite.github.io/license.html).** 

## 📪 Where can I download Onix Client?

To download Onix Client, go to the [#download](https://discord.com/channels/814195071356370977/852334369061863464) channel. Once you do this, you have a few options:

### Launcher (recommended option)
- Download the launcher and open it. Once you click launch, after a few seconds, it will automatically open your game and inject Onix Client.

### Injector & DLL
- Use the Onix Injector and download the DLL. Select the DLL. Then, open Minecraft and go back into the injector. Once Minecraft loads, click Inject.
- You CAN use a third-party injector, but we can't ensure that it will work properly and if it's safe for public use.

## 🔒 Is Onix Client safe?

Yes, we can assure you that Onix Client is 100% safe for use. Your antivirus might flag it because it injects a DLL into the game. However, due note these things:
- Our injector can only inject into Minecraft, other viruses attack other applications, if not all.
- If you use any third-party program along with our DLL, we are **NOT** ensuring functionality or the fact that this is safe. However, any Onix Client file used is 100% safe.
-  Minecraft is a UWP app, which means it is sandboxed. Meaning even if the DLL was malicious, it wouldn't be able to do very much when injected into the minecraft process. More info about UWP sandboxing [Here](https://labs.sogeti.com/windows-store-apps-live-sandbox).
- If you ever feel like anything is not safe, **DON'T** use it.

## 📱 What devices does Onix Client support?

### You have to use Windows 10/11. You also need the 64-bit operating system with an x64-based processor.

This shouldn't be a problem if you have Windows 11, as an x64-based processor is required to use it.

### How do I check?
Right click the Start button and click "System", which takes you to this screen:

![](https://user-images.githubusercontent.com/64127681/140582244-70a847bf-a2fb-41dc-ae0c-320090bbf23e.png)
- If it says "64-bit operating system, x64-based processor", you can use Onix Client.
- If it says "32-bit operating system, x64-based processor", you need to install the 64-bit version of Windows. We will not be showing you how to do that here, so go do your research.
- If it says "32-bit operating system, ***x86***-based processor", unfortunately, you can't use Onix Client.
- If your PC is ARM or Qualcomm based, you can't use Onix Client either.

### We have no plans to support any devices other than Windows PCs. Don't ask for it.

## 🔄 The launcher didn't auto update. How do I fix this?
Press the Windows Key + R and paste the following:

`cmd.exe /c del "%localappdata%\Onix Launcher\OnixClient.dll" && pause`

This will delete the old Onix Client dll, and the launcher will install the new one on launch.

## 🌊 When I open the client, I get an error saying: "You are attempting to open a file of type 'system file'". Why does this happen?

This is because you are trying to open the DLL, which only works with other injectors. The DLL file cannot be opened and is not meant to be either. If you want to use this method please check out the Onix injector. If you use a third-party injector, we are not responsible for anything that might happen.

## 🔧 Can I turn off or customize the "OnixClient on top!" splash text?

No. We use this to make diagnosing problems much easier for our support team.

## 🐞 When I inject, my game crashes. Why does this happen?

Your game is most likely on an unsupported version. If you are below 1.16.40, you will need to upgrade to a higher version. If you are above the latest supported version, you will need to downgrade. You can downgrade (or upgrade) using [MCLauncher](https://github.com/MCMrARM/mc-w10-version-launcher).

### List of supported versions:
```
(1.18)     (1.17)     (1.16)
1.18.12    1.17.41    1.16.221
1.18.10    1.17.40    1.16.220
1.18.2     1.17.34    1.16.210
1.18.1     1.17.32    1.16.201
1.18.0     1.17.30    1.16.200
           1.17.11    1.16.100 (partial)
           1.17.10    1.16.40
           1.17.2
           1.17.0
```

## 🧥 Why does it say "as nobody (HOW)" on Discord instead of my Gamertag?

Make sure you have the Xbox Console Companion, which you can download [here](https://www.microsoft.com/en-us/p/xbox-console-companion/9wzdncrfjbd8#activetab=pivot:overviewtab). Log in, and it should show up after restarting the launcher.

If you have already downloaded Xbox Console Companion, log out and log back in to fix it.

## ❓ I clicked Launch and I see the "OnixClient on top!" splash text. Now what?

Go to a world or server and press L or Insert, then you'll be able to see the Client Settings button. To activate modules, right-click on them.

## Common launcher errors

### 🏢 Architecture Error
![Architecture Error V2](https://user-images.githubusercontent.com/71997480/155266817-c6c7fb22-56f8-4c3c-98d9-6c3fc8849669.png)

You have a 32-bit version of Minecraft. This is usually branded under FPS Boosting or Lag-Free AppX files. These are not compatible with Onix Client.

### ⛔ Unsupported Version
![Unsupported Version](https://user-images.githubusercontent.com/64127681/139366307-d319f1ea-36c3-4978-b8ba-ad3cd891141e.png)

You have a version of Minecraft that is not supported. You can see this list of supported versions [here](https://github.com/HugoNotHere/OnixClientFaq#list-of-supported-versions).

### 💉 Injection Error
![Injection Error](https://user-images.githubusercontent.com/64127681/139366443-21a01000-36c3-44a0-842e-30030bdf31d5.png)

An error occurred while trying to inject Onix Client. This may be due to your antivirus, however, we cannot quite pinpoint this issue to a cause. Please open a ticket if you have issues resolving this problem.

## 🎨 How can I get Onix UI?

It's being remade as of recently. You'll have to wait.

## 💰 How can I support Onix and the client?

You can support us by [becoming a patron](https://www.patreon.com/onixclient). The perks are listed in the tiers. If you buy a tier, please don't hesitate to open a ticket to get your roles if the bot hasn't already synced them.

## 🌈 Why are my rainbow modules not synced/in time with each other?

Press L, click on Client Settings, then turn on "Sync All Rainbow" on the Global Settings. This should sync the modules together.

## 🔎 Why is the zoom not working with my hotkey?

Right-click the module first (you can do this with any module to enable it). This is not a bug, but a feature that allows Onix to have a zoom out animation if you have zoom animations enabled.

## ❌ How do I remove the client?

Hold CTRL + L.

## 💺 What's the latest version of the client?

The current latest version is 2.75

## ⚙️ What features do we have in the client?

```
Zoom
Fullbright
Freelook (360 perspective)
Environment Changer
Java Debug Menu
Toggle Sprint/Sneak
Auto GG
Chunk Borders
Render Options
Third Person Nametag
Block Outline/Overlay
Custom Crosshairs
Hitboxes (they don't show through blocks/walls)
Waypoints (.waypoint in mc chat to get clear instructions)
FPS Counter
Clock
Keystrokes
Coordinates
Server IP Display
CPS Counter
Direction HUD
Speed Display
Reach Display
Combo Counter
Pack Display
Armor HUD
Movable Paperdoll
Flappy Bird
Snake
Potion HUD
Audio Subtitles
Player List Tab
Hurt Color
Light Overlay
TNT Timer
Creative Tools (cheats that you can use when you are operator)
Item Physics
Theme Editor (say .theme in chat)
.Commands 
Module Search
Client Side Nick (.nick)
```

Say ```.help``` in chat for a complete list of Onix commands.

## 🎥 How do I apply for media Role/Rank in the Discord? (@Youtuber)?

Requirements:
- 750+ Subs
- A video about Onix Client 
If you meet the requirements, open a ticket.

## 🔨 Do I get beta access if I boost?

Yes, now that the Epic Games Nitro promotion is over. If you boost our discord, you get access to [#beta-announcments](https://discord.com/channels/814195071356370977/900851856857788486) and [#beta-chat](https://discord.com/channels/814195071356370977/900851856857788486). You also get [#cool-chat](https://discord.com/channels/814195071356370977/853207500832374784) and image/embed perms in [#général](https://discord.com/channels/814195071356370977/852356013395148850).

## 📄 How do you get the default Minecraft font?

Open the module settings and enable "Minecraftia Font" on the right.

## 📌 I need the Onix logo for a thumbnail!

![Onix logo example](https://camo.githubusercontent.com/63fb5b9391792bee79fae1e73fe472f4e3b99af2b666db8c7105941135d7058c/68747470733a2f2f6d656469612e646973636f72646170702e6e65742f6174746163686d656e74732f3835323335363031333339353134383835302f3837373538353634323636303433333935302f6f6e69783273617475722e706e67)
![Onix logo example](https://camo.githubusercontent.com/aa9b4bb8abbdae246b47c8f7ea4a591ab3aff47f87d81da21197a2e9c263f79b/68747470733a2f2f6d656469612e646973636f72646170702e6e65742f6174746163686d656e74732f3833303735333338373433353738363237312f3839373531383037323435363433373834302f4f6e69784c6f676f42757448616c6c6f7765656e2e706e67)
![Onix logo example](https://camo.githubusercontent.com/a5742cdd28af00abcc1e85dee5e202ff4e91d2b64067c194351020c8cfba1978/68747470733a2f2f6d656469612e646973636f72646170702e6e65742f6174746163686d656e74732f3833303735333338373433353738363237312f3839373532313538363132313335393336302f42616e6e65722e706e67)
![Onix logo example](https://camo.githubusercontent.com/15e3694b508fa5e1d6fe48f269d62351d07a1744684b427e07ac3e1fdf8519c2/68747470733a2f2f6d656469612e646973636f72646170702e6e65742f6174746163686d656e74732f3835333331323432353032353230383336302f3931353333353132383335343532353233342f30413941444138362d353231392d313145432d413532462d3032333437413334383845372e676966)
![Onix logo example](https://camo.githubusercontent.com/0f93c185650659afe79f6af5d9c60b02f936fd8d8f63c373d6ad1e67118b1a79/68747470733a2f2f6d656469612e646973636f72646170702e6e65742f6174746163686d656e74732f3835333331323432353032353230383336302f3931353333353332353035343830383037342f4f6e69785f4368726973746d61735f4c6f676f5f46696e616c655f56325f7468696e67792e706e673f77696474683d393839266865696768743d393839)
![Onix logo example](https://camo.githubusercontent.com/55cc9dae7af7c8c8d4e6478740a570dce13ec29a34c7f0208e8482c3ad0aa1a9/68747470733a2f2f6d656469612e646973636f72646170702e6e65742f6174746163686d656e74732f3835333331323432353032353230383336302f3931353333353330353435303633393433302f46696e616c5f42616e6e65725f4f6e69782e706e673f77696474683d31373538266865696768743d393839)

## 🖼️ I want pictures of the Onix Launcher and Injector!

![Onix injector/launcher example](https://camo.githubusercontent.com/deebd779f5e2e830636e2d8c7e51a29f4110cfc75f5a7ec0b1915587738b7854/68747470733a2f2f6d656469612e646973636f72646170702e6e65742f6174746163686d656e74732f3738353931303732353439393432303639362f3838303834323334323736373136313336342f756e6b6e6f776e2e706e67)
![Onix injector/launcher example](https://user-images.githubusercontent.com/64127681/139374739-a69c085f-ce7b-4e17-93d6-0cfdd6437d0f.png)

## 🧪 Why don't the PotionHUD icons show up?

One of your texture packs probably broke them. But don't worry, we have a PotionHUD Fixer [here](https://github.com/HugoNotHere/OnixClientFaq/blob/main/files/PotionFix.mcpack?raw=true)! Due note: this pack may break custom hotbars/XP bars.

## 🛏️ When I have render options on, I can't see beds and chests and other blocks.

Turn off "Hide Tile Entities".

## 🖌️ How do I change the theme of my Onix GUI?

Say .theme in chat.

## 💜 How do I reset a colour/module?

Middle-click the change colour button or the module in the Onix GUI. You can middle-click by pressing the scroll wheel down or clicking with 3 fingers on a trackpad.

## 🔻 How do I remove the red arrow from Minecraft?

Download [this pack](http://www.mediafire.com/file/kqyjo9s9ld39nkn/No+Red+Arrow+by+Mhavin.mcpack/file) and apply it. The reason why it exists is that the pack maker/porter of one of your packs never updated hud_screen.json. The bug report and discussion can be found [here](https://bugs.mojang.com/browse/MCPE-105882).

![Red Arrow Bug](https://camo.githubusercontent.com/611f29fa85267ae8044cf1a3238a2afb2383d681bb7bbdf31c1a2f646c7d4f43/68747470733a2f2f696d616765732d6578742d312e646973636f72646170702e6e65742f65787465726e616c2f5861544a716e464b70546d5676705a527349556a69625272533143684442386e5a434a473078756b4c33452f68747470732f6875676f2e706c656173652d656e642e6d652f6f67702f35386e4d69557748642e706e67)

## 📋 Where can I find the latest changelog?

### Changelog for OnixClient 2.70

```
Client:
```
Fixed "Custom Crosshair" using image crosshairs
Added an option to "Custom Crosshair" to use "Texture Pack" crosshair
Fixed freecam for 1.18.12
Fixed "Render Options" not being compatible with "Zoom" hide hand option
Fixed "Item Physics" for 1.18.30/1.18.31 with item frames
Fixed Darkness effect showing as "Unknown"
Added the option to have round corners on most mods
Added support for 1.18.31
```

QOL fixes/tweaks:
- Re-enabled FPS showing in the Java Debug Menu
- Fixed block position in Java Debug Menu occasionally reading inaccurately
- Speed display now works properly when riding entities
- Increased the creative tools block reach cap from 12 to 25
- Renamed and clarified all module descriptions
- Fixed rounding errors in Direction HUD
- Fixed some instances where mod menu text would render invisible on 1.17.40 and 1.17.41

Launcher:
- Removed the taskbar icon
- Fixed Discord Presence not updating because of the taskbar icon
- Added logs for troubleshooting purposes, which are located in %localappdata%\Onix Launcher\Logs
- RPC Error has been moved to the logs, and is no longer displayed as an error message
- Custom DLL is now Insider Mode and can be toggled on/off by double clicking the Onix logo

Miscellaneous:
creative tools freecam is gone from 1.18.10/1.18.12 and future versions
```

## 🦠 My antivirus blocks the client.

Depending on the antivirus that you're using, you should either turn it off so you can download the client or you can exclude the client from being flagged. Onix Client is not a virus of any sort. The launcher is open source; the source code can be viewed [here](https://github.com/notcarlton/OnixLauncher) if you want to compile it yourself or check if the code is safe.

<table>
<thead>
<tr>
<th style="text-align:center"><strong>Antivirus</strong></th>
<th style="text-align:center"><strong>Exclude Links</strong></th>
<th style="text-align:center"><strong>Disable Links</strong></th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align:center">Windows Defender</td>
<td style="text-align:center"><a href="https://www.technipages.com/windows-10-how-to-exclude-a-file-from-windows-defender/">Exclude</a></td>
<td style="text-align:center"><a href="https://support.microsoft.com/en-us/windows/turn-off-defender-antivirus-protection-in-windows-security-99e6004f-c54c-8509-773c-a4d776b77960">Disable</a></td>
</tr>
<tr>
<td style="text-align:center">Norton</td>
<td style="text-align:center"><a href="https://www.lifewire.com/exclude-files-from-norton-antivirus-scans-153348#">Exclude</a></td>
<td style="text-align:center"><a href="https://www.lifewire.com/disable-norton-antivirus-4589389">Disable</a></td>
</tr>
<tr>
<td style="text-align:center">Malwarebytes</td>
<td style="text-align:center"><a href="https://support.malwarebytes.com/hc/en-us/articles/360039024133-Exclude-detections-in-Malwarebytes-for-Windows-v3">Exclude</a></td>
<td style="text-align:center"><a href="https://support.malwarebytes.com/hc/en-us/articles/360038524894-Enable-or-disable-Real-Time-Protection-in-Malwarebytes-for-Windows-v3">Disable</a></td>
</tr>
<tr>
<td style="text-align:center">McAfee</td>
<td style="text-align:center"><a href="https://service.mcafee.com/?page=shell&shell=article-view&articleId=TS102056">Exclude</a></td>
<td style="text-align:center"><a href="https://www.linksys.com/us/support-article?articleNum=135555">Disable</a></td>
</tr>
<tr>
<td style="text-align:center">Avast</td>
<td style="text-align:center"><a href="https://support.avast.com/en-ph/article/Antivirus-scan-exclusions/">Exclude</a></td>
<td style="text-align:center"><a href="https://bestantiviruspro.org/blog/how-to-temporarily-disable-avast/#:~:text=Go%20to%20the%20Windows%20taskbar,until%20computer%20restart%20OR%20permanently.">Disable</a></td>
</tr>
<tr>
<td style="text-align:center">BitDefender</td>
<td style="text-align:center"><a href="https://www.bitdefender.com/consumer/support/answer/13427/">Exclude</a></td>
<td style="text-align:center"><a href="https://clean-my-pc.com/how-to-disable-bitdefender#:~:text=Disable%20Bitdefender%20Issues&amp;amp;text=Open%20the%20Bitdefender%20software%20application,option%20from%20the%20Shield%20tab.">Disable</a></td>
</tr>
<tr>
<td style="text-align:center">Kaspersky Internet Security</td>
<td style="text-align:center"><a href="https://support.kaspersky.com/KESWin/10SP2/en-US/128138.htm">Exclude</a></td>
<td style="text-align:center"><a href="https://support.kaspersky.com/KIS/2020/en-US/43539.htm">Disable</a></td>
</tr>
<tr>
<td style="text-align:center">Quick Heal</td>
<td style="text-align:center"><a href="https://pastebinp.com/1qXb5ugXTJJvzPwN0grgHQ#X4eOM2tB_9A9D4HqARc8CZpnsDQkBgIsbHC_axVGAgg=">Exclude</a></td>
<td style="text-align:center"><a href="https://www.quora.com/How-do-I-disable-Quick-Heal-antivirus-in-Windows-8-1">Disable</a></td>
</tr>
<tr>
<td style="text-align:center">AVG</td>
<td style="text-align:center"><a href="https://support.avg.com/SupportArticleView?l=en&urlname=AVG-Antivirus-scan-exclusions#:~:text=Open%20AVG%20AntiVirus%20and%20go,box,%20then%20click%20Add%20exception.">Exclude</a></td>
<td style="text-align:center"><a href="https://pastebinp.com/KkUjBKhGXpr1rHXq5EVxQ#kK0YoBfCMex0gJyy33GH9mpp2P5cORVZjEhCzdx6a6U=">Disable</a></td>
</tr>
<tr>
<td style="text-align:center">Webroot</td>
<td style="text-align:center"><a href="https://pastebinp.com/990CALwgMkEVszAPC1WBg#nHxmjWr0CKHZ-Kzmz11djBCbLmkkuE_iWawPdRuCJV0=">Exclude</a></td>
<td style="text-align:center"><a href="https://community.webroot.com/tech-talk-7/how-can-i-turn-off-webroot-temporarily-337647">Disable</a></td>
</tr>
<tr>
<td style="text-align:center">Panda/Panda Dome</td>
<td style="text-align:center"><a href="https://www.pandasecurity.com/en/support/card?id=55521">Exclude</a></td>
<td style="text-align:center"><a href="https://www.techwalla.com/articles/how-to-disable-the-panda-antivirus#">Disable</a></td>
</tr>
<tr>
<td style="text-align:center">Spectrum F-Secure</td>
<td style="text-align:center"><a href="https://pastebinp.com/RuwyAM9BvnlJJO5GmXAw#RXthundQfjFjfWCDz-XjlpU4_zt-cXCXx3i0f0r6dcU=">Exclude</a></td>
<td style="text-align:center"><a href="https://pastebinp.com/GfkArfGf8xP2bSTbgfIzJg#vxqH7m8Yweb2waI-MvjoAM4apryli6Cj_5fsf75pg5U=">Disable</a></td>
</tr>
<tr>
<td style="text-align:center">PCMatic</td>
<td style="text-align:center"><a href="https://forums.pcmatic.com/topic/203530-manually-adding-a-programservice-to-whitelist/">Exclude</a></td>
<td style="text-align:center"><a href="https://forums.pcmatic.com/topic/205678-is-there-any-way-to-turn-pcmatic-off/">Disable</a></td>
</tr>
<tr>
<td style="text-align:center">k7</td>
<td style="text-align:center"><a href="https://support.k7computing.com/index.php?/selfhelp/view-article/How-can-I-manage-exclusion">Exclude</a></td>
<td style="text-align:center"><a href="https://support.sathyainfo.com/kb/a239/how-do-i-disable-my-antivirus-program-in-windows.aspx">Disable</a></td>
</tr>
<tr>
<td style="text-align:center">RAV Antivirus</td>
<td style="text-align:center"><a href="https://www.reddit.com/r/RAVAntivirus/comments/tq31n5/how_to_exclude_files_or_folders_from_rav/">Exclude</a></td>
<td style="text-align:center"><a href="https://howtoremove.guide/rav-antivirus-uninstall/">Uninstall</a></td>
</tr>
</tbody>
</table>
<td style="text-align:center"><a href="https://support.k7computing.com/index.php?/selfhelp/view-article/How-can-I-manage-exclusion">Exclude</a></td>

~~Avira users:~~
~~Avira will not let you use Onix Client, even if it's disabled. We recommend you uninstall Avira until we get this issue sorted out with them.~~

^^ This issue is now fixed.


If you have an antivirus that's not included here or if a link stops working,DM me [@ItzHugo#2308](https://discord.com/users/731013984710426694) so I can fix it.

DM [Isaiahluke40#3089](https://discord.com/users/397244496586211339) for now until Hugo comes back. (Only if related to antivirus problems). If I'm not online, I suggest going to [#make-a-ticket](https://discord.com/channels/814195071356370977/945717582269399050) and create a ticket.

Please go to [#make-a-ticket](https://discord.com/channels/814195071356370977/945717582269399050) and create a ticket there if you are currently encountering issues relating to the injector and/or client. (Please wait patiently after making a ticket)

# The Onix Client License

Definitions: Us/We (the Onix Client developers), You (you reading this/using Onix Client)
We own the Onix Client name, the logo, and its programs/binaries.
You are subject to the following terms:
## - You can:

• Talk about the client

• Show the logo in your YouTube thumbnail(s)

• Use the logo to showcase the client in rewiews, showcases, etc

## - You cannot:

• Use the logo and name for your own product(s) **without permission from us**

• Claim the logo and name as yours

• Promote your product with the logo and name

• Reupload or redistribute the client/launcher in different websites
(Mediafire, Dropbox, your own Discord server, etc.)

• Distribute a modified version of the client/launcher

• Use, distribute, and/or own older versions of any of our products

Failure to comply with these terms will result in your content being taken down.

## If you do not agree with those terms:              
 Delete all binaries logos, files do not use any of the products              
 To remove it from the game close it              
 if you use it anyway you agree to follow these terms

Extra notes: We don't want to be a boring company. We just want to protect our logo and name.
Any questions should be asked in [#make-a-ticket](https://discord.com/channels/814195071356370977/945717582269399050).


## 🤝 Contributing

You can contribute to this FAQ by making a fork of this project, editing it, and submitting a pull request. All **valid** help is accepted and is encouraged. Thank you for reading and helping to make this better!

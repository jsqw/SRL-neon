# SRL-neon

Scripts made with SRL and WaspLib to be used alongside RuneLite and its plugins.

## Using Simba with RuneLite

This tutorial assumes that you have previously used 32-bit Simba, e.g. the waspscripts.com automatic installer.

### Getting 64-bit Simba

Start by downloading the 64-bit version of Simba. You still need to do this even if you have 32-bit Simba previously installed.

You can find 64-bit Simba [here](https://github.com/Villavu/Simba/releases/tag/simba1400-release).

![simbadl](https://i.imgur.com/D2zMG7E.png)

After downloading, move the 64-bit .exe file to your SimbaFolder, which is by default at:

`C:\Users\username\AppData\Local\Simba`

After moving the file, it is recommended to send a shortcut to the Desktop:

![scut](https://i.imgur.com/J21Mxrn.png)

For clarity, let's rename the shortcuts:

![rename](https://i.imgur.com/ev6e4jn.png)

### Getting RuneLite and the .properties file

Download and install RuneLite, if you haven't already.

[www.runelite.net](www.runelite.net)

![rl](https://i.imgur.com/jVeUqY3.png)

After installing RuneLite, head to the repository and locate the .properties file, which includes plugin setups for the neon [scripts](https://github.com/jsqw/SRL-neon).

Click the small icon to download the file.

![save](https://i.imgur.com/xGs9WrW.png)

After you have downloaded the .properties file, open up RuneLite settings and the profiles tab.

Click import profile and locate the file you just downloaded.

Lastly, click open.

![cl](https://i.imgur.com/11M31kW.png)

Rename the Imported profile as neon.

![sve](https://i.imgur.com/iDGKZUW.png)

After renaming the profile, double-click it to activate it.

![sadve](https://i.imgur.com/mBv50VN.png)

Close RuneLite.

After closing RuneLite, copy and paste the Desktop shortcut of RuneLite to have two copies of it.

![scpe](https://i.imgur.com/mjvGHXq.png)

Rename them with descriptive names.

![names](https://i.imgur.com/VZ9OjuL.png)

Open the properties of both of them.

![prop](https://i.imgur.com/JEqq9lp.png)

Add the flag: `--profile=neon` to the Neon shortcut and `--profile=default` to your normal RuneLite shortcut. Click apply and OK.

![proff](https://i.imgur.com/yy7kdTI.png)

Now you should have two different RuneLite shortcuts, one for the Default profile you can play on and one for the Neon profile that you can bot on.

Start up the 64-bit Simba and the Neon RuneLite. On the first time, you might have to trust the new 64-bit Simba that you downloaded:

![protrff](https://i.imgur.com/V8BYEr6.png)

Before running scripts with RuneLite you have to always make sure that:

- The RuneLite sidebar is hidden
- You have manually dragged the target selector to the client window.

![dd](https://i.imgur.com/4GxwF4U.png)

### Thanks to:

- Torwent (waspscripts.com, SRL-T and WaspLib)
- Slacky (answering my questions, work towards SRL)
- Flight (tutorials on villavu and helping with questions)

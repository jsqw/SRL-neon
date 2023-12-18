# SRL-neon

This repository contains scripts for use with RuneLite and its plugins, developed using SRL and WaspLib.

## Script list:

### Agility

Currently supported courses:

- Draynor rooftop
- Al Kharid rooftop
- Canifis rooftop
- Seer's Village rooftop
- Pollnivneach rooftop

### Bonfirer

Automatically and progressively levels woodcutting and firemaking north of the Crafting Guild.

### Camdozaal fisher

Levels fishing, cooking and prayer in the ruins of Camdozaal.

### Mage Training Arena

Automatically completes the four different rooms of the minigame.

## Using Simba with RuneLite

This guide is tailored for users familiar with the 32-bit version of Simba, such as those installed via the waspscripts.com automatic installer.

### Getting 64-bit Simba

1. **Download the 64-bit Simba:**
   Even if you have the 32-bit version, you need the 64-bit version to use it with RuneLite. Download it from [Simba's GitHub Release Page](https://github.com/Villavu/Simba/releases/tag/simba1400-release).

   ![Download Simba](https://i.imgur.com/D2zMG7E.png)

2. **Configure the 64-bit Version:**
   Move the downloaded `.exe` file to your Simba installation folder, typically located at `C:\Users\username\AppData\Local\Simba`. Consider creating a desktop shortcut for easy access.

   ![Create Shortcut](https://i.imgur.com/J21Mxrn.png)

3. **Organize Shortcuts:**
   Rename the shortcuts for better clarity.

   ![Rename Shortcuts](https://i.imgur.com/ev6e4jn.png)

### Setting Up RuneLite

1. **Install RuneLite:**
   If you haven't already, download and install RuneLite from [www.runelite.net](www.runelite.net).

   ![RuneLite Installation](https://i.imgur.com/jVeUqY3.png)

2. **Configure RuneLite:**

   - Locate and download the `.properties` file for neon scripts from the [SRL-neon repository](https://github.com/jsqw/SRL-neon).
   - In RuneLite, go to settings and then the profiles tab.
   - Import the downloaded `.properties` file.

   ![Import Profile](https://i.imgur.com/11M31kW.png)

3. **Profile Management:**

   - Rename the imported profile to 'neon'.
   - Activate it by double-clicking, and then close RuneLite.

   ![Activate Profile](https://i.imgur.com/mBv50VN.png)

4. **Create Shortcuts:**

   - Duplicate the RuneLite desktop shortcut by copying and pasting it on the Desktop.
   - Rename them descriptively.
   - Modify properties: Add `--profile=neon` for the neon profile and `--profile=default` for your standard profile.

   ![Shortcut Properties](https://i.imgur.com/JEqq9lp.png)
   ![Launch Profiles](https://i.imgur.com/yy7kdTI.png)

5. **Launch Setup:**
   Open 64-bit Simba and the Neon RuneLite. Initially, you may need to approve the newly installed 64-bit Simba.

   ![Trust Simba](https://i.imgur.com/V8BYEr6.png)

6. **Pre-Script Checks:**
   Before running any scripts, ensure the RuneLite sidebar is hidden and the target selector is manually dragged into the client window.

   ![Preparation Steps](https://i.imgur.com/4GxwF4U.png)

### Acknowledgements

Special thanks to:

- Torwent (waspscripts.com, SRL-T, and WaspLib)
- Slacky (for answering questions and contributions to SRL)
- Flight (for tutorials on villavu and assistance with queries)

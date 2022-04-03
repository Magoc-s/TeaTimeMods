# TeaTimeMods
The collection of mods/plugins the Teatime minecraft server is using, as well as how to install them!

---

## Installation

## For Windows
**Step 1**: Download the [fabric installer.](../main/fabric-installer-0.10.2.exe) (This is what makes the mods work.)
  - Source: (https://fabricmc.net/use/installer/)

**Step 2**: Run the installer, and select **1.18.1** as the game version, and leave the "loader" version as it is. You shouldn't have to change the install location either. Now click install.

**Step 3**: Download the [mods zip.](../main/teatime_mods.zip)
  - You may also download the optional_mods zip if you are interested in installing some performance oriented mods.

**Step 4**: Extract the mods from this zip folder into your mods folder in your '.minecraft' directory.
  - If you are unsure how to do this, then about 1/3 of the way down [this website](https://www.alphr.com/fabric-install-mods/) explains it.

![image](https://user-images.githubusercontent.com/85176789/161418929-ec6414ae-06c1-4762-99da-62a490b4a1e0.png)

Here's what my mods folder looks like. You can leave the zip file in there if you would like, it doesn't matter. **NOTE:** The mods sit inside the `.minecraft/mods` folder, you can't have any sub-folders inside here! I.e. `.minecraft/mods/teatime_mods/< ... mods ... >` will not work. 

**Step 5 (Optional)**: In your minecraft launcher, go to the 'Installations' tab and press the three dots on the newly created Fabric loader installation.
  - Step 5.1: Edit the advanced options and modify the `-Xmx2G` value in the 'Launch Arguments' section. By default minecraft has 2GB of RAM allocated to it (indicated by the 2). Change this to how ever much ram you want to allocate to minecraft. General rule of thumb is half your total available ram.
   
---

## For Mac
Step 1: Download the 'Universal JAR' from the [Fabric Installer Download page](https://fabricmc.net/use/installer/).
  
  ![image](https://user-images.githubusercontent.com/85176789/161418991-21ae16c3-1149-47ab-af52-9a3227d38dce.png)

**Step 2**: Run the JAR file, and select **1.18.1** as the game version, and leave the "loader" version as it is. You might have to change the install location to point towards your minecraft folder (whereever your minecraft is installed). Now click install. 
  - Note: if Mac doesn't know how to run the Jar file, you may need to install the Java runtime environment first. You can follow the comments on this page for some help: https://stackoverflow.com/questions/16828076/how-to-run-a-jar-in-mac

**Step 3**: Download the [mods zip.](../main/teatime_mods.zip)
  - You may also download the optional_mods zip if you are interested in installing some performance oriented mods.

**Step 4**: Extract the mods from this zip folder into your mods folder in your '.minecraft' directory.
  - If you are unsure how to do this, then about 1/3 of the way down [this website](https://www.alphr.com/fabric-install-mods/) explains it.

![image](https://user-images.githubusercontent.com/85176789/161418929-ec6414ae-06c1-4762-99da-62a490b4a1e0.png)

Here's what my mods folder looks like. You can leave the zip file in there if you would like, it doesn't matter.

**Step 5 (Optional)**: In your minecraft launcher, go to the 'Installations' tab and press the three dots on the newly created Fabric loader installation.
  - Step 5.1: Edit the advanced options and modify the `-Xmx2G` value in the 'Launch Arguments' section. By default minecraft has 2GB of RAM allocated to it (indicated by the 2). Change this to how ever much ram you want to allocate to minecraft. General rule of thumb is half your total available ram.

---

## FAQ

**Q:** Can I use optifine with this?
  - **A:** Not at the moment sorry. Optifine causes Origins to crash.

**Q:** Can we add some more origins in? How many is there to begin with?
  - **A:** There are about 47 origins right now. So do we even need more? Also no - due to a limitation in how the player sends and receives data when joining a server, adding any additional origins can sometimes cause players to be unable to join worlds or servers.

**Q:** What enchantments are there? What origins are there?
  - **A:** Play and find out! We want everything to be a natural exploration process. There may be some really OP things initially as we still try and find the balance for everything. So just let us know if you think something is too powerful and we may remove/modify it. Cheers.

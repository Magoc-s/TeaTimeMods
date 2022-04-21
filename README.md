# TeaTimeMods
The collection of mods/plugins the Teatime minecraft server is using, as well as how to install them!

---

## Installation

## For Windows
**Step 1**: Download the [fabric installer.](../main/fabric-installer-0.10.2.exe) (This is what makes the mods work.)
  - Source: (https://fabricmc.net/use/installer/)

**Step 2**: Run the installer, and select **1.18.1** as the game version, and leave the "loader" version as it is (it should be the most recent). You shouldn't have to change the install location either. Now click install.
  - Note: you will have to have Java installed to run this. This will require you to install the JDK and the JRE.
  - JDK: https://jdk.java.net/17/
  - JRE: https://java.com/en/download/manual.jsp

**Step 3**: Download this repo by clicking the green `Code` button in the top right and clicking `Zip`.
  - Then follow the steps in the `README.md` files in the `mods/` and `resourcepacks/` folders to install.
  - If you are unsure how to do this, then about 1/3 of the way down [this website](https://www.alphr.com/fabric-install-mods/) explains it.

![image](https://user-images.githubusercontent.com/85176789/161418929-ec6414ae-06c1-4762-99da-62a490b4a1e0.png)

Here's what my mods folder looks like. **NOTE:** The mods sit inside the `.minecraft/mods` folder, you can't have any sub-folders inside here! I.e. `.minecraft/mods/teatime_mods/< ... mods ... >` will not work. 

**Step 4 (Optional)**: In your minecraft launcher, go to the 'Installations' tab and press the three dots on the newly created Fabric loader installation.
  - Step 5.1: Edit the advanced options and modify the `-Xmx2G` value in the 'Launch Arguments' section. By default minecraft has 2GB of RAM allocated to it (indicated by the 2). Change this to how ever much ram you want to allocate to minecraft. General rule of thumb is half your total available ram.
   
---

## For Mac
Step 1: Download the 'Universal JAR' from the [Fabric Installer Download page](https://fabricmc.net/use/installer/).
  
  ![image](https://user-images.githubusercontent.com/85176789/161418991-21ae16c3-1149-47ab-af52-9a3227d38dce.png)

**Step 2**: Run the JAR file, and select **1.18.1** as the game version, and leave the "loader" version as it is. You might have to change the install location to point towards your minecraft folder (whereever your minecraft is installed). Now click install. 
  - Note: if Mac doesn't know how to run the Jar file, you may need to install the Java runtime environment first. You can follow the comments on this page for some help: https://stackoverflow.com/questions/16828076/how-to-run-a-jar-in-mac

**Go to step 3 above.**

---

## FAQ

**Q:** Can I use optifine with this?
  - **A:** Not at the moment sorry. Optifine causes Origins to crash.

**Q:** Can we add some more origins in? How many is there to begin with?
  - **A:** There are about 60+ origins right now. If you find a good datapack with one you like - send Julian a link to it. Make sure its for MC 1.18

**Q:** What enchantments are there? What origins are there?
  - **A:** Play and find out! We want everything to be a natural exploration process. There may be some really OP things initially as we still try and find the balance for everything. So just let us know if you think something is too powerful and we may remove/modify it. Cheers.

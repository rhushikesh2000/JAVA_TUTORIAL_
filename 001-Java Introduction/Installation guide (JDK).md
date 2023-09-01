Installation guide (JDK)
---

**Step 1:**
---
 Open the <https://www.oracle.com/java/technologies/javase-downloads.html>  url in the browser and it will navigate to the official Oracle Java downloads page.

**Step 2:** 
---
- Select the version of Java which we want to download.
- Select the operating system.
- Scroll down to the page and click on the URL option suitable for your computer Operating system. But for a 64-bit machine, choose the software name ending with x64.  


![jdk2](https://github.com/rhushikesh2000/JAVA_TUTORIAL_/assets/124034778/d7e94d3b-d952-4669-b0e9-7cc1f4e2ecc7)


**Step 3:** 
---

![jdk3](https://github.com/rhushikesh2000/JAVA_TUTORIAL_/assets/124034778/60b068f0-a337-4935-8205-54d34ac75387)

After the downloading procedure is complete, we need to run the installer



**Step 4:** 
---
Once Java installation wizard opens, click on the Next button as shown below:





![jdk4](https://github.com/rhushikesh2000/JAVA_TUTORIAL_/assets/124034778/ab9f3a8c-8434-41e2-a9e1-849c0a1a5288)










**Step 5:** 
---
Again click on the Next button if we wish to install Java development kit in the default directory(encircled with green color), or we can change this directory by clicking on Change button.  




![jdk5](https://github.com/rhushikesh2000/JAVA_TUTORIAL_/assets/124034778/2dcd0d3a-e01e-4f1f-af3d-11019c967093)








**Step 6:** 
---
The installation will begin as shown below:




![jdk6](https://github.com/rhushikesh2000/JAVA_TUTORIAL_/assets/124034778/ce69af96-28e0-4400-8c5b-9610c8572a97)



**Step 7:**
---
Finally, we can click on the Close button after the confirmation window appears which says that the Java is installed.




![jdk7](https://github.com/rhushikesh2000/JAVA_TUTORIAL_/assets/124034778/bc07ac32-19d9-4196-b611-ed8b1ec96110)









**Setting up Environment in Java**
---
- After downloading,  Once you install Java on your device, you have to set up the environment variable.

**Step 1**:
---
Locate the JDK Installation Folder:

After installing the JDK, it's important to find out where it's installed. By default, java is installed in the “C:\Program Files\Java\jdk\bin” folder OR “C:\Program Files(x86)\Java\jdk\bin”. In case, you have installed Java at any other location, then add that path.

**C-drive  à Program Filesàjava àjdk à bin (copy the path)**

**Step 2:**
---
Go to the search bar and search **f**or **Environment variable ->** click on **Edit system Environment variable.**

Under the Advanced System Setting option click on **Environment Variables** as highlighted below**.**





![env2](https://github.com/rhushikesh2000/JAVA_TUTORIAL_/assets/124034778/8a216db5-7a5e-4c28-ae06-94544b156cc0)







**Step 3**
---
Now, you have to alter the “**Path”** variable under System variables so that it also contains the path to the Java environment. Select the “Path” variable and click on the **Edit button** as highlighted below.



![env3](https://github.com/rhushikesh2000/JAVA_TUTORIAL_/assets/124034778/78bd6cff-b2af-4294-830c-bf730a340f0e)




**Step 4:**
---
You will see a list of different paths, Click on the **New** button, and then add the path where Java is installed. By default, java is installed in the “C:\Program Files\Java\jdk\bin” folder OR “C:\Program Files(x86)\Java\jdk\bin”. In case, you have installed Java at any other location, then add that path.










![env4](https://github.com/rhushikesh2000/JAVA_TUTORIAL_/assets/124034778/2b1a517d-4df7-43c2-a296-8b47525f2257)












**Step 5**: 

Click on OK, Save the settings, and you are done !! Now to check whether the installation is done correctly, open the **command prompt** and type **java --version**. You will see that java is running on your machine.

[ref1]: Aspose.Words.f34fb923-a537-4b9b-8671-08be93095383.002.png

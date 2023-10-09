# A02
### GIT and GitHub Tutorial with WebStorm

**GIT**: A distributed version control system that helps track changes in source code throughout the development process.

**GitHub**: A cloud-based platform that uses **GIT** for version control, allowing multiple people to collaborate on projects.

**WebStorm**: A powerful and intelligent IDE developed by JetBrains. It offers advanced coding, debugging, and testing tools to help developers.

To download WebStorm, visit JetBrains official website: https://www.jetbrains.com/webstorm/


#### Step 1: Setting Up Your Environment
1. Install **GIT** from [https://git-scm.com/]
2. Set up an account on **GitHub** at [https://github.com/]
3. To download WebStorm, visit JetBrains' official website: https://www.jetbrains.com/webstorm/
4. In WebStorm, configure **GIT** by navigating to File > Settings (or Preferences) > Version Control > Git. Point to the git.exe file.


#### Step 2: Creating Your First **Repository**
1. On **GitHub**, click the '+' icon on the top right > New repository.
2. Name your **repository**, add a description, and initialize it with a README.
3. Click 'Create Repository'.


#### Step 3: **Clone** the **Repository** to WebStorm
**Clone**: Create a copy of the **repository** from **GitHub** to your local machine.
1. In WebStorm, go to File > New > Project from Version Control > Git.
2. Enter the URL of your **GitHub** **repository** and choose where to save it locally.
3. Click 'Clone'.


#### Step 4: Making Changes and **Commit**ting
**Commit**: Saving your changes to the **repository**.
1. Make changes to your project in WebStorm.
2. To save these changes, go to VCS > **Commit**.
3. Add a commit message describing your changes.
4. Click 'Commit'.


#### Step 5: **Push**ing Changes to **GitHub**
**Push**: Send your **commit**ted changes to a remote **repository**.
1. After **commit**ting, go to VCS > Git > **Push**.
2. Confirm and push the changes to **GitHub**.


#### Step 6: **Pull**ing Changes from **GitHub**
**Pull**: Fetch changes from the **GitHub** **repository** and **merge** them with your local copy.
1. To get the latest changes, go to VCS > Git > **Pull**.
2. Confirm and pull the changes into WebStorm.


#### Step 7: Working with **Branch**es
**Branch**: Different versions of a **repository**. 
1. To create a new **branch**, go to VCS > Git > **Branch**es > New Branch.
2. Name your branch and create it.
3. Switch between branches using the bottom-right panel in WebStorm.


#### Step 8: Resolving **Merge Conflicts**
**Merge Conflict**: Occurs when changes conflict with each other, and Git cannot determine which is correct.
1. When **pull**ing or **merge**ing changes, WebStorm will alert you if there's a **merge conflict**.
2. Open the conflicting file. WebStorm highlights the conflicting areas.
3. Manually choose which changes to keep.
4. **Commit** and **push** your resolved changes.


#### Step 9: Connecting to a **Remote**
**Remote**: A **repository** hosted on the internet or another network.
1. To add a **remote**, go to VCS > Git > Remotes.
2. Add the URL of the remote **repository**.
3. Now you can **push**, **pull**, and **fetch** changes from this **remote**.


#### Step 10: **Fetch**ing Code from a **Remote**
**Fetch**: Downloading changes from a **remote** without **merge**ing them.
1. Go to VCS > Git > **Fetch**.
2. WebStorm will **fetch** the latest changes from the **remote**, allowing you to review them.


### References:
- [Git Official Documentation](https://git-scm.com/doc)
- [GitHub Help](https://docs.github.com/en)
- [WebStorm Documentation](https://www.jetbrains.com/webstorm/documentation/documentation.html)

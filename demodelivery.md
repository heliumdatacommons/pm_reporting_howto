# Demo Delivery 

See [dcppc/organize](https://github.com/dcppc/organize/blob/master/reporting/README.md) for Team Copper's description of the entire demo delivery process pipeline. 

## How To?
There are several ways to update the [dcppc/internal/phase-1](https://github.com/dcppc/internal/blob/master/phase-1/index.md)
repo with the demo information.

Below are the steps to take if you have read and write access and can **Create a New Branch**: 

1) Create a new branch by selecting the grey dropdown menu towards the top left, which is currently called "Branch:**master**". Start typing a new branch name
    - Example: "2M.1FullStacks-Helium"
2) Double-check that you are in your new branch. Look for the same grey dropdown menu, which should now have the name of the branch you created. In this example, we should see "Branch:**2M.1FullStacks-Helium**" . 
3) Navigate to the dcppc/internal/phase-1 folder by ensuring you are in the **Code** tab and clicking on the phase-1 folder link. You will see a list of markdown (.md) files of previous demos that have been delivered. Add a new .md file to internal/phase-1/ by selecting the **Create new file** button, and name your new .md file.
    - Example: "2M.1FullStacks-Helium.md"
4) Add the appropriate links to the demo/code/video/etc, and a description of the demo in the new .md. Then scroll down and click **Commit changes**.
5) Finally, link the new .md file you just created to the internal/phase-1/index.md markdown file.
    - After navigating to the index.md file (it is one of the files listed in the phase-1 folder), Click the pencil icon (:pencil2:) to **Edit** this file
    - Under the appropriate Demo heading, create a bullet point (* and a space) and type in [Team Helium demo]
    (Name of the new .md file you just created)
    - Example: * [Team Helium Demo] (2M.1FullStacks-Helium.md) 
    - Note: there should not be a space between [] and () to ensure hyperlinking
    - Preview changes to ensure that your addition turned into a bulleted hyperlink, and click the hyperlink to ensure
    that it goes to your newly created .md file
        - Note: if this results in a 404 error, you are not in the correct branch. Cancel changes and double check that the grey drop down menu says "Branch:**Nameofyourbranch**"
6) Submit pull request by navigating to dcppc/internal and selecting the green button **Compare and pull request**
    - The title of the pull request will be generated based on what you've done, please ensure that it is descriptive.
    Use the comment section to call out specific people that you would like to review the branch (ex: Helium developer, Claris, Titus, etc) using @GitHubHandle
    - Click the **Submit Pull Request** button 
    - This branch is now under review for the next 7 days. Team Copper will format the new .md file and may request additional information
    - Once the review process is over, Team Copper will merge the new branch into the **master** Branch. 
    

**Additional helpful info:** 
[GitHub How to Create a New Branch](https://help.github.com/articles/creating-and-deleting-branches-within-your-repository/) 

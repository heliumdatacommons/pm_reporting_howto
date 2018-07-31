# Demo Delivery 

See [dcppc/organize](https://github.com/dcppc/organize/blob/master/reporting/README.md) for Team Copper's description of the entire demo delivery process pipeline. 

## How To?
There is more than one way to update the [dcppc/internal/phase-1](https://github.com/dcppc/internal/blob/master/phase-1) repo with the demo information.

Below are the steps to take if you have read and write access and can **Create a New Branch**: 

0) First start by clicking the [dcppc/internal/phase-1](https://github.com/dcppc/internal/blob/master/phase-1) hyperlink
1) Create a new branch by selecting the grey dropdown menu towards the top left, which is currently called "Branch:**master**". Start typing a new branch name and then select "Create branch"
    - Example branch name: "2M.1FullStacks-Helium"
2) Double-check that you are in your new branch. Look for the same grey dropdown menu, which should now have the name of the branch you created. In this example, we should see "Branch:**2M.1FullStacks-Helium**" . 
3) Assuming you are still in the phase-1 folder, you will see a list of markdown (.md) files of previous demos that have been delivered. Scroll down until you see the index.md markdown file, and select this file. Click the pencil icon (:pencil:) to **Edit** this file
    - Scroll until you find the appropriate Demo heading, and beneath it type in "Team Helium links"
    - Then below the "Team Helium links" line, create a bullet point(s) for each link that Helium has for that demo (* and a space)
    - Example: * [Helium Github repo] (url for Helium Github repo) (note, ensure there are no spaces between [] and () to ensure hyperlinking) 
     - Preview changes to ensure that your addition(s) turned into a bulleted hyperlink, and click the hyperlink to ensure
    that it goes to the correct webpage
4) Submit pull request by navigating to the **Code** tab of dcppc/internal and select the green button **Compare and pull request**
    - The title of the pull request will be generated based on what you've done, please ensure that it is descriptive (like Helium 3M.1 Demo).
    - The text of the pull request will autogenerate with the template of questions needed to be answered about the demo you are submitting (see here [template here](https://github.com/dcppc/internal/blob/master/.github/pull_request_template.md)). 
    - Preview your text and click the **Submit Pull Request** button 
    - Use the comment section to call out specific people that you would like to review the branch (ex: Helium developer, Claris, Titus, etc) using @GitHubHandle
    - **Note:** You can still edit this PR until it is merged. Hit the pencil :pencil: icon to edit 
5) This branch is now under review for the next 7 days. Team Copper will format the new .md file and may request additional information - **be on the lookout for questions that Helium developers need to answer!!!!**
    - Once the review process is over, Team Copper will merge the new branch into the **master** Branch. 
    

**Additional helpful info:** 
* Note: if you are submitting more than 1 demo for the month, submit all demo .md files in 1 PR
* [GitHub How to Create a New Branch](https://help.github.com/articles/creating-and-deleting-branches-within-your-repository/) 
* [GitHub How to Write in Markdown](https://guides.github.com/features/mastering-markdown/)

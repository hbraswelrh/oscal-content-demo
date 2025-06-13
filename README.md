## trestle-workspace 🤖

## Table of Contents
- [Getting started](#introduction)
  - [Tracking Progress](#tracking-your-course-progress-in-a-pr-octocat)
- [Deep Dive](#deep-dive)
  - [What it should look like](#pull-request-body)
  - [Creating the PR](#creating-the-pr-tada)
  - [Interacting with the PR](#interacting-with-the-pull-request-)
- [Usage](#usage)
  - [Basic Usage](#using-the-trestle-workspace)
    - [Manually updating the Component Definitions](#manually-updating-an-oscal-component-definition)
    - [Leveraging GitHub Actions](#leveraging-github-actions-to-author-component-definitions-octocat)
      - [Steps](#world_map-steps)   
  - [Dev Usage](#dev-usage)
- [Support](#support)
  - [Resources](#resources) 

---
## Getting Started

#### Tracking your course progress in a PR :octocat:

1. **Switch to the `develop` Branch:**  
   * In your `trestle-workspace` repository, navigate to the "Branches" tab or use the dropdown menu.  
   * Switch from the `main` branch to the `develop` branch.  
   * All your course changes will be made on this `develop` branch.

    <img alt="branches.png" height="100" src="https://github.com/hbraswelrh/trestle-workspace/blob/9ef7608ec8c0599a90f1b85d1a3de8259ca9d3a3/assets/img/branches.png" width="150"/>

2. **Make Your First Change:**  
   * Edit the `README.md` file in your `develop` branch to include your name.  
   * Commit your changes directly to the `develop` branch by clicking "Commit Changes."
   
   <img alt="readmechange.png" height="80" src="https://github.com/hbraswelrh/trestle-workspace/blob/9ef7608ec8c0599a90f1b85d1a3de8259ca9d3a3/assets/img/readmechange.png" width="250"/>

3. **Create Your Pull Request (PR):**  
   * Go to the "Pull Requests" tab in your repository.  
   * Click the "New Pull Request" button.  
   * Ensure the comparison is set to: `base: main` **\<--** `compare: develop`.  
   * You should see your `README.md` change listed in the file differences.  
   * Provide a descriptive title for your PR (e.g., `feat: My First Course Submission - [Your Name]`).  
   * Click "Create pull request."

   <img alt="img.png" height="55" src="https://github.com/hbraswelrh/trestle-workspace/blob/9ef7608ec8c0599a90f1b85d1a3de8259ca9d3a3/assets/img/create_PULL.png" width="600"/>

   - You should see your recently changed `README.md` as part of the pull request.
   
   <img alt="img.png" height="60" src="https://github.com/hbraswelrh/trestle-workspace/blob/9ef7608ec8c0599a90f1b85d1a3de8259ca9d3a3/assets/img/viewPR.png" width="500"/>

4. **Submit Evidence of Completion:**  
   * Once your Pull Request is created, copy its unique URL from your browser's address bar.  
   * Paste the URL into the designated field of the [self-assessment](assets/self_assessment/self_assessment.md). This PR link serves as your evidence of attempting the `trestle-workspace` course activities. 🎉

5. **Interact and Learn (Optional but Recommended):**  
   * Bookmark your PR page. :bookmark:
   * Use the "Comments" section within your PR to ask questions or make notes about your progress. This is a great way to engage with the material and receive support. 💬
  
## Deep Dive 

#### Pull Request Body

The "New Pull Request" will take the changes you made to the `README.md` and place those in a history log. Then, that log will be proposed to be merged to the `main` branch of the repository.

Notice the _Write_ and _Preview_ tabs. Markdown format is present in the _Write_ tab. Check your mardown plain text using _Preview_. 

<img alt="img.png" height="250" src="https://github.com/hbraswelrh/trestle-workspace/blob/9ef7608ec8c0599a90f1b85d1a3de8259ca9d3a3/assets/img/pretty_md.png" width="230"/> <img alt="img.png" height="250" src="https://github.com/hbraswelrh/trestle-workspace/blob/9ef7608ec8c0599a90f1b85d1a3de8259ca9d3a3/assets/img/learning-course.png" width="230"/>


#### Creating the PR :tada:

Click the green "Create pull request" button :white_check_mark:. Then, the page should automatically refresh and look like this: 

  <img alt="img.png" height="200" src="https://github.com/hbraswelrh/trestle-workspace/blob/9ef7608ec8c0599a90f1b85d1a3de8259ca9d3a3/assets/img/PRBODY.png" width="300"/>


#### Interacting with the Pull Request 

:bookmark: _Bookmark the page..._

The new PR `feat: learning course tracker {YOUR_NAME}` will be available in your copy of the trestle-workspace. :closed_lock_with_key:

<img alt="img.png" height="85" src="https://github.com/hbraswelrh/trestle-workspace/blob/9ef7608ec8c0599a90f1b85d1a3de8259ca9d3a3/assets/img/WORKSPACE_PR.png" width="490"/>

:incoming_envelope: The comment section allows for asking questions, making changes, and referencing those changes in your work.

> Example comment: "@hbraswelrh I need help with my PR!!"

<img alt="img_1.png" height="200" src="https://github.com/hbraswelrh/trestle-workspace/blob/9ef7608ec8c0599a90f1b85d1a3de8259ca9d3a3/assets/img/PR_COMMENT.png" width="300"/>

#### What you'll submit

To submit your progress and changes made in the `trestle-workspace`, include the link to the new PR you created in the quiz found [here](assets/self_assessment/self_assessment.md). 

## Usage

### Using the trestle-workspace

> #### Manually updating an OSCAL Component Definition

> You can manually update an OSCAL Component Definition in the `component-definitions` folder of the trestle-workspace.
<img alt="compdef_folder.img" height="200" src="https://github.com/user-attachments/assets/8085baa4-e3a9-4d2b-bd4a-5e81dc545017" width="400"/>

> #### Leveraging GitHub Actions to author Component Definitions :octocat:

> The GitHub Actions available will allow you to create OSCAL Component Definitions using the `workflow_dispatch` functionality.

##### :world_map: Steps:

1. Navigate to the Actions tab in your trestle-workspace.
2. Click the action in the top left corner that is named [Create a Component Definition](https://github.com/hbraswelrh/trestle-workspace/actions/workflows/create-cd.yml).
3. Click "Run workflow." There should be a box populated that requests the following inputs:
   - Name of profile in trestle workspace to be imported into the component definition. 
   - Name of component definition to create.
   - Name of the component in the generated component definition.
   - Type of component (e.g., service, policy, physical, validation, etc. ).
   - Description of the component in the generate component definition.
   - Filter the component definition control by a separate profile.
     
   <img alt="img.png" height="400" src="https://github.com/hbraswelrh/trestle-workspace/blob/7492e400d5709d29c030fe39badff15bcc0a8e81/assets/img/workflow_entry.png" width="200"/>

**Example inputs for the [Create a Component Definition](https://github.com/hbraswelrh/trestle-workspace/actions/workflows/create-cd.yml) workflow in the trestle-workspace**

`profile:` [my-profile](https://github.com/hbraswelrh/trestle-workspace/blob/main/profiles/my-profile/profile.json)

`component definition name:` [rhel10-anssi-high](https://github.com/hbraswelrh/trestle-workspace/blob/main/component-definitions/rhel10/rhel10-anssi-high/component-definition.json)

`component in generated component definition:` "Rule_Id"

`component type:` "software"

`description of the component in the component definition:` "Red Hat Enterprise Linux 10"

`filtering by profile:` *intentionally left blank*

#### Dev Usage

## Support 

#### Resources

Reference the [GLOSSARY.md](https://github.com/hbraswelrh/creme-brulee/blob/main/docs/GLOSSARY.md) in the creme-brulee learning course.
Using Pull Requests in GitHub to track interaction with a project. 



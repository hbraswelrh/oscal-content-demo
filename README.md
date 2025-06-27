## oscal-content-demo
## oscal-content-demo 🤖 - {REPLACE_ME}
_developing OSCAL Content this time.._

## Table of Contents
- [Getting started](#getting-started)
  - [Tracking Progress](#tracking-your-course-progress-in-a-pr-octocat)
- [Deep Dive](#deep-dive-)
  - [What it should look like](#pull-request-body)
  - [Creating the PR](#creating-the-pr-tada)
  - [Interacting with the PR](#interacting-with-the-pull-request-)
- [Usage](#usage)
  - [Basic Usage](#using-the-trestle-workspace)
    - [Manually updating the Component Definitions](#manually-updating-an-oscal-component-definition)
    - [Leveraging GitHub Actions](#leveraging-github-actions-to-author-component-definitions-octocat)
      - [Steps](#world_map-steps)
  - [Resources](#resources) 

---
## Getting Started

#### Tracking your course progress in a PR :octocat:

1. **Switch to the `develop` Branch:**  
   * In your`oscal-content-demo` repository, navigate to the "Branches" tab or use the dropdown menu.  
   * Switch from the `main` branch to the `develop` branch.  
   * All your course changes will be made on this `develop` branch.

<img alt="idk.png" height="100" width="150" src="https://github.com/hbraswelrh/oscal-content-demo/blob/9ef7608ec8c0599a90f1b85d1a3de8259ca9d3a3/assets/img/branches.png">

2. **Make Your First Change:**  
   * Edit the `README.md` file in your `develop` branch to include your name.  
   * Commit your changes directly to the `develop` branch by clicking "Commit Changes."
   
<img alt="branches.png" height="130" src="https://github.com/hbraswelrh/oscal-content-demo/blob/main/assets/img/newone.png" width="390"/>

3. **Create Your Pull Request (PR):**  
   * Go to the "Pull Requests" tab in your repository.  
   * Click the "New Pull Request" button.  
   * Ensure the comparison is set to: `base: main` **\<--** `compare: develop`.  
   * You should see your `README.md` change listed in the file differences.  
   * Provide a descriptive title for your PR (e.g., `feat: My First Course Submission - [Your Name]`).  
   * Click "Create pull request."

<img alt="img.png" height="50" src="https://github.com/hbraswelrh/oscal-content-demo/blob/9ef7608ec8c0599a90f1b85d1a3de8259ca9d3a3/assets/img/create_PULL.png" width="590"/>

   - You should see your recently changed `README.md` as part of the pull request.
   
<img alt="img.png" height="58" src="https://github.com/hbraswelrh/oscal-content-demo/blob/9ef7608ec8c0599a90f1b85d1a3de8259ca9d3a3/assets/img/viewPR.png" width="500"/>


4. **Submit Evidence of Completion:**  
   * Once your Pull Request is created, copy its unique URL from your browser's address bar.  
   * Paste the URL into the designated field of the [self-assessment](assets/self_assessment/self_assessment.md). This PR link serves as your evidence of attempting the `trestle-workspace` course activities. 🎉

5. **Interact and Learn (Optional but Recommended):**  
   * Bookmark your PR page. :bookmark:
   * Use the "Comments" section within your PR to ask questions or make notes about your progress. This is a great way to engage with the material and receive support. 💬
  
## Deep Dive 

#### Pull Request Body

The "New Pull Request" will take the changes you made to the `README.md` and place those in a history log. Then, that log will be proposed to be merged to the `main` branch of the repository.

Notice the _Write_ and _Preview_ tabs. Markdown format is present in the _Write_ tab. Check your markdown plain text using _Preview_. 

<img alt="img.png" height="250" src="https://github.com/hbraswelrh/oscal-content-demo/blob/9ef7608ec8c0599a90f1b85d1a3de8259ca9d3a3/assets/img/pretty_md.png" width="230"/> <img alt="img.png" height="250" src="https://github.com/hbraswelrh/oscal-content-demo/blob/9ef7608ec8c0599a90f1b85d1a3de8259ca9d3a3/assets/img/learning-course.png" width="230"/>


#### Creating the PR :tada:

Click the green "Create pull request" button :white_check_mark:. Then, the page should automatically refresh and look like this: 

<img alt="img.png" height="300" src="https://github.com/hbraswelrh/oscal-content-demo/blob/main/assets/img/newone3.png" width="500"/>


#### Interacting with the Pull Request 

:bookmark: _Bookmark the page..._

The new PR `feat: learning course tracker {YOUR_NAME}` will be available in your copy of the oscal-content-demo. :closed_lock_with_key:


<img alt="img.png" height="85" src="https://github.com/hbraswelrh/oscal-content-demo/blob/main/assets/img/newone2.png" width="490"/>

:incoming_envelope: The comment section allows for asking questions, making changes, and referencing those changes in your work.

> Example comment: "@hbraswelrh I need help with my PR!!"

<img alt="img_1.png" height="200" src="https://github.com/hbraswelrh/oscal-content-demo/blob/9ef7608ec8c0599a90f1b85d1a3de8259ca9d3a3/assets/img/PR_COMMENT.png" width="300"/>

#### What you'll submit

To submit your progress and changes made in the `oscal-content-demo`, include the link to the new PR you created in the quiz found [here](assets/self_assessment/self_assessment.md). 

## Usage

### Using the oscal-content-demo workspace

> #### Manually updating an OSCAL Component Definition

> You can manually update an OSCAL Component Definition in the `component-definitions` folder of the oscal-content-demo.

<img alt="img.png" height="120" src="https://github.com/hbraswelrh/oscal-content-demo/blob/main/assets/img/newone4.png" width="400"/>

> #### Leveraging GitHub Actions to author Component Definitions :octocat:

> The GitHub Actions available will allow you to create OSCAL Component Definitions using the `workflow_dispatch` functionality.

##### :world_map: Steps:

1. Navigate to the Actions tab in your oscal-content-demo.
2. Click the action in the top left corner that is named [Create a Component Definition](https://github.com/hbraswelrh/oscal-content-demo/actions/workflows/create-cd.yml).
3. Click "Run workflow." There should be a box populated that requests the following inputs:
   - Name of profile in oscal-content-demo to be imported into the component definition. 
   - Name of component definition to create.
   - Name of the component in the generated component definition.
   - Type of component (e.g., service, policy, physical, validation, etc. ).
   - Description of the component in the generate component definition.
   - Filter the component definition control by a separate profile.
     
   <img alt="img.png" height="400" src="https://github.com/hbraswelrh/trestle-workspace/blob/7492e400d5709d29c030fe39badff15bcc0a8e81/assets/img/workflow_entry.png" width="200"/>

**Example inputs for the [Create a Component Definition](https://github.com/hbraswelrh/oscal-content-demo/actions/workflows/create-cd.yml) workflow in the oscal-content-demo**

`profile:` [my-profile](https://github.com/hbraswelrh/oscal-content-demo/blob/main/profiles/my-profile/profile.json)

`component definition name:` [rhel10-anssi-high](https://github.com/hbraswelrh/oscal-content-demo/blob/main/component-definitions/rhel10/rhel10-anssi-high/component-definition.json)

`component in generated component definition:` "Rule_Id"

`component type:` "software"

`description of the component in the component definition:` "Red Hat Enterprise Linux 10"

`filtering by profile:` *intentionally left blank*

#### Resources

Reference the [GLOSSARY.md](https://github.com/hbraswelrh/creme-brulee/blob/main/docs/GLOSSARY.md) in the creme-brulee learning course.

The [oscal-content](https://github.com/ComplianceAsCode/oscal-content) repository in the ComplianceAsCode organization will follow this learning course. 



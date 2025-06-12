## trestle-workspace 🤖

## Table of Contents
- [Getting started](#introduction)
  - [Tracking Progress](#tracking-your-progress-in-a-pr-octocat)
  - [What to Expect](#pull-request-body)
  - [Creating the PR](#create-the-pr-tada)
  - [Interacting with the PR](#interacting-with-the-pull-request-)
  - [What you'll Submit](#what-youll-submit)
- [Testing it out](#test-it-out)
- [Installation](#installation)
  - [Prerequisites](#prerequisites)
- [Usage](#usage)
  - [Basic Usage](#basic-usage)
  - [Dev Usage](#dev-usage)
- [Testing](#testing)
  - [How to Configure](#how-to-contribute)
- [Support](#support)

---
## Getting Started

#### Tracking your progress in a PR :octocat:

1. Switch from the trestle-workspace `main` branch to the trestle-workspace `develop` branch.

    <img alt="branches.png" height="100" src="https://github.com/hbraswelrh/trestle-workspace/blob/9ef7608ec8c0599a90f1b85d1a3de8259ca9d3a3/assets/img/branches.png" width="150"/>

2. Make a change to the `README.md` to include your name. Click "Commit Changes..."

   <img alt="readmechange.png" height="85" src="https://github.com/hbraswelrh/trestle-workspace/blob/9ef7608ec8c0599a90f1b85d1a3de8259ca9d3a3/assets/img/readmechange.png" width="250"/>

3. Go to the Pull Requests tab and click the green "New Pull Request" button.

   
- Make sure that the `compare: develop` branch is being compared to the `base:main` branch.
   

   <img alt="img.png" height="95" src="https://github.com/hbraswelrh/trestle-workspace/blob/9ef7608ec8c0599a90f1b85d1a3de8259ca9d3a3/assets/img/newPR.png" width="320"/>

   <img alt="img.png" height="55" src="https://github.com/hbraswelrh/trestle-workspace/blob/9ef7608ec8c0599a90f1b85d1a3de8259ca9d3a3/assets/img/create_PULL.png" width="600"/>

   - You should see your recently changed `README.md` as part of the pull request.
   
   <img alt="img.png" height="60" src="https://github.com/hbraswelrh/trestle-workspace/blob/9ef7608ec8c0599a90f1b85d1a3de8259ca9d3a3/assets/img/viewPR.png" width="500"/>
   
#### Pull Request Body

The "New Pull Request" will take the changes you made to the `README.md` and place those in a history log. Then, that log will be proposed to be merged to the `main` branch of the repository.

- You can update the Summary to include the changes you made. The other fields are for later. 

Notice the _Write_ and _Preview_ tabs. Markdown format is present in the _Write_ tab. Check your work using _Preview_. 

<img alt="img.png" height="250" src="https://github.com/hbraswelrh/trestle-workspace/blob/9ef7608ec8c0599a90f1b85d1a3de8259ca9d3a3/assets/img/pretty_md.png" width="230"/> <img alt="img.png" height="250" src="https://github.com/hbraswelrh/trestle-workspace/blob/9ef7608ec8c0599a90f1b85d1a3de8259ca9d3a3/assets/img/learning-course.png" width="230"/>

[//]: # (< img alt="img.png" height="250" src="https://github.com/hbraswelrh/trestle-workspace/blob/9ef7608ec8c0599a90f1b85d1a3de8259ca9d3a3/assets/img/learning-course.png" width="230"/>)

#### Create the PR :tada:

Click the green "Create pull request" button :white_check_mark:. Then, the page should automatically refresh and look like this: 
  
  <img alt="img.png" height="30" src="https://github.com/hbraswelrh/trestle-workspace/blob/9ef7608ec8c0599a90f1b85d1a3de8259ca9d3a3/assets/img/create-PR.png" width="400"/>

  <img alt="img.png" height="200" src="https://github.com/hbraswelrh/trestle-workspace/blob/9ef7608ec8c0599a90f1b85d1a3de8259ca9d3a3/assets/img/PRBODY.png" width="300"/>

[//]: # (<img alt="img.png" height="240" src="https://github.com/hbraswelrh/trestle-workspace/blob/9ef7608ec8c0599a90f1b85d1a3de8259ca9d3a3/assets/img/PR.png" width="250"/>)


#### Interacting with the Pull Request 

_Bookmark the page..._ :bookmark:

The new PR `feat: learning course tracker {YOUR_NAME}` will be available in your copy of the trestle-workspace. :closed_lock_with_key:

<img alt="img.png" height="85" src="https://github.com/hbraswelrh/trestle-workspace/blob/9ef7608ec8c0599a90f1b85d1a3de8259ca9d3a3/assets/img/WORKSPACE_PR.png" width="490"/>

The comment section allows for asking questions, making changes, and referencing those changes in your work. :incoming_envelope:

> Example comment: "@hbraswelrh I need help with my PR!!"

<img alt="img_1.png" height="200" src="https://github.com/hbraswelrh/trestle-workspace/blob/9ef7608ec8c0599a90f1b85d1a3de8259ca9d3a3/assets/img/PR_COMMENT.png" width="300"/>


#### What you'll submit

To submit your progress and changes made in the `trestle-workspace`, include the link to the new PR you created in the quiz found [here](assets/self_assessment/self_assessment.md). 

## Test it Out

#### Manually updating an OSCAL Component Definition

You can manually update an OSCAL Component Definition in the `component-definitions` folder of the trestle-workspace.

#### Leveraging GitHub Actions to author Component Definitions

The GitHub Actions available will allow you to create OSCAL Component Definitions using the `workflow_dispatch` functionality.

##### Steps:

1. Navigate to the Actions tab in your trestle-workspace.
2. Click the action in the top left corner that is named [Create a Component Definition](https://github.com/hbraswelrh/trestle-workspace/actions/workflows/create-cd.yml).
3. Click "Run workflow." There should be a box populated that requests the following inputs:
   - Name of profile in trestle workspace to be imported into the component definition. 
   - Name of component definition to create.
   - Name of the component in the generated component definition.
   - Type of component (e.g., service, policy, physical, validation, etc. ).
   - Description of the component in the generate component definition.
   - Filter the component definition control by a separate profile.
     <img alt="img.png" height="150" src="https://github.com/hbraswelrh/trestle-workspace/blob/7492e400d5709d29c030fe39badff15bcc0a8e81/assets/img/workflow_entry.png" width="100"/>

## Installation 

### Prerequisites 

## Usage

#### Dev Usage

## Testing 

### How to Configure

## Support 

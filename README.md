# Design Guidelines for Tableau Dashboard Extensions

With the release of Extensions in [Tableau Desktop 2018.2](https://www.tableau.com/support/releases/desktop/2018.2), we're unleashing the creativity and problem-solving skills of passionate developers to make extensions for Tableau dashboards. Here’s your roadmap for designing great extensions.


### About
This document is focused on guiding developers towards best practices for designing extensions, including user interaction and visual style guidelines. For technical guidance, refer to our [Extensions API Documentation](https://tableau.github.io/extensions-api/).


### What are Dashboard Extensions?
Tableau Dashboard Extensions are web applications that have two-way communication with the dashboard. Dashboard extensions enable all sorts of scenarios, like letting you integrate Tableau with custom applications, making possible for you to modify the data for a visualization, or even creating custom visualizations inside the dashboard. 

&nbsp;

# Contents
These are all the main things you need to know about designing a great extension experience.

#### 1. [Interaction Guidelines](#interaction-guidelines)
#### 2. [Style Guidelines](#style-guidelines)
#### 3. [Deploying your Extension](#deploying-your-extension)

&nbsp;

## Interaction Guidelines

#### [1 – Build, Test, Share](Interaction Guidelines/1 - Build, Test, Share.md)
The developer's roadmap for how to get started developing and designing extensions.

&nbsp;

#### [2 – Extension Components and Modes](Interaction Guidelines/2 - Extension Components and Modes.md)
The main user-facing components of an extension to create content for. Learn about modes for configuring extensions, viewing extensions, and dashboard user types.

&nbsp;

#### [3 – Controls and UI Patterns](Interaction Guidelines/3 - Controls and UI Patterns.md)
Usage and design specifications for user interface controls and patterns in your extension.

###### *At this time, we are only able to provide surface-level usage and design specifications for controls. We are working to make code for Tableau controls accessible to developers in the future.*

&nbsp;

&nbsp;

## Style Guidelines

#### [4 – Branding your Extension](Style Guidelines/4 - Branding your Extension.md)
How to style your extension in accordance with the Tableau brand and your personal/company brand.

&nbsp;

#### [5 – Layout](Style Guidelines/5 - Layout.md)
Details about dashboard containers and spacing in the extension container.

&nbsp;

#### [6 – Color](Style Guidelines/6 - Color.md)
Use color effectively in your extension, and an opportunity to use Tableau's colors.

&nbsp;

#### [7 – Fonts](Style Guidelines/7 - Fonts.md)
Guidelines for fonts that can be used in extensions.

&nbsp;

&nbsp;

## Deploying your Extension

### [Sharing to the Extension Gallery](Sharing to the Extension Gallery.md)
Guidelines on what you need to share your extension to Tableau's Extension Gallery.

&nbsp;

&nbsp;

---
&nbsp;

![Extensions are made using a manifest file called a .trex! FreLard stands for the Seattle neighborhoods of Fremont and Wallingford, where Tableau's headquarters stands.](imgs/trex.png)

*This document is a work-in-progress. To give feedback, ask questions, or if you have technical questions about Extensions, please contact devplat@tableau.com.*

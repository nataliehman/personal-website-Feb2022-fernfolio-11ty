---
title: Optimising process and data access for Smartology's ad campaign management dashboard
metaDescription: A project showcasing the work done on addressing the challenges of creating a dashboard supporting centralised data access for Smartology's team.
summary:
client: Smartology
cover: dashboard-cover.webp
tags:
  - Affinity mapping
  - Brainwriting
  - Flow diagrams
  - User interviews
  - User testing
  - Wireframing
  - Prototyping
  - project work
order: 1
---

![Smartology dashboards](/static/img/dashboard/dashboard-versions.webp)

## Key learnings
As the solo designer, this project taught me valuable lessons on how to effectively apply the UX process. It also emphasised the importance of adapting quickly to my team's needs over strictly following a linear design process.

When the new dashboard design was launched, I noticed how the UX process improved team collaboration. For example, the engineering team proactively asked the team for feedback and did more user testing on features they were developing. 

I feel that I would have more clarity if I knew how to question the 'whys' about the business objectives. For example, why was the dashboard missing key data for account managers to do their reporting? Why was sales and finance capturing certain data, which is not be stored on the current dashboard? 

This project taught me to embrace flexibility and adapt to unpredictable changes whilst maintaining clarity on the project's direction.

## Overview

The project was driven by changes in the advertising industry moving towards automated online (programmatic) advertising. There was also more focus on data-driven campaign optimisation, which meant the need to improve the company's internal workflows to adapt to these changes.

## Objectives

- Develop a new dashboard interface within 8 months
- Optimise processes for adopting programmatic advertising technologies
- Streamline data access

## Team

Natalie H. Man, UX Designer, Smartology
Robert Varney, Senior UX Designer, Freelance (support for high fidelity prototyping and testing)

## Gathering insights through collaborative voting

I allocated around 3 weeks for user research and the first activity was to gather requirements and pain points from the team. My goal was to ensure transparency and have all relevant team members be involved in the process. Also, since my team had no UX maturity, it was a good opportunity to introduce activities that encourages them to work collaboratively and receive updated on the project's progress.

![Team voting to prioritise current major challenges to be addressed for the project](/static/img/dashboard/dashboard-requirements-voting.webp) <figcaption>I used Google Sheet to gather pain points experienced within the team. I wanted a general overview on what challenges my team deals with in their daily tasks. Since everyone had access to the file, not only it provided transparency but also filter similar issues, which helped the team with prioritising.</figcaption>

![Affinity map of the requirements and pain points grouped into themes](/static/img/dashboard/dashboard-requirements-affinity-map.webp) <figcaption>Affinity map of the requirements grouped into process phases. Each category had its requirements totalled and if it's over 15, that phase is considered a major area to address.</figcaption>


## Prioritising automation and centralised data capture for optimised team workflow

The existing dashboard's development was mostly focused on supporting the account management team. However, speaking to secondary users like finance and sales highlighted how their pain points in their workflows and dashboard usage are generally overlooked by the primary users (account management). The insights gained from the interviews presented opportunities in improving other areas of the dashboard.

![Speaking with our Finance Controller highlighted the need to automate manual tasks for more accurate reporting](/static/img/dashboard/dashboard-interview-finance.webp) <figcaption>Interview with our finance controller to learn about her process and challenges. I transcribed my written notes into Google Docs and summarised the insights into categories. Insights highlighted the majority of her process required manual tasks. For example, for billing, she had to do calculations and recheck data from contracts/invoices. This revealed opportunities like automating reports and to support better centralised data capture within the dashboard for team access.</figcaption>

![Speaking with our Head of Sales (EMEA) highlighted the need for dashboard features that can support the sales team in managing the sales pipeline](/static/img/dashboard/dashboard-interview-sales.webp) <figcaption>Interview with our head of sales (EMEA). I also transcribed my written notes into Google Docs and summarised them. Insights highlighted how the sales team used many tools for their process e.g. Salesforce to manage sales pipeline, Google Drive for file storage, internal dashboard to monitor client campaign performance and live campaigns etc. This revealed opportunities like creating advertising contracts in the dashboard for the sales team in managing prospects.</figcaption>


## Workflow optimisation through flow diagrams

I sketched multiple flow diagrams to visualise the different workflows for teams like sales and finance. They were recreated in Lucid Chart and printed for relevant stakeholders to review, ensuring the diagrams accurately reflected their processes. Their feedback helped identify missing information between the current processes and what the dashboard captured. This highlighted opportunities to include more data fields in the dashboard for storing important client campaign information, rather than saving numerous files in Google Drive.

![Visualising the campaign management process via system flow diagrams](/static/img/dashboard/dashboard-flow-diagrams.webp) <figcaption>The first diagram sketch shows the iterative development and review process of a campaign. The second Lucid Chart diagram illustrates the flighting process for activating campaigns with feedback from relevant stakeholders. They revealed missing steps in the diagrams, such as checking with sales if the contract is up-to-date, and checking spreadsheets ensuring everything is correct before a campaign goes live.</figcaption>

## Facilitating creative brainwriting in stakeholder ideation workshops

For the ideation workshops, I combined HMWs and brainwriting into a structured activity. My team are also not use to collaborative activities, so I approached it this way to ensure everyone can participate without feeling overwhelmed. I wanted all participants to equally contribute independently without the stress of being judged by others. This not only provides diverse ideas but having them write on paper helps them to focus on the topic and their thoughts with little distractions.

![HMWs voted and grouped under the high priority categories.](/static/img/dashboard/dashboard-hmw-voted.webp) <figcaption>HMWs voted and grouped under the high priority categories. Examples of HMWs used include 'How might we enable account managers to create showcases before campaign information is confirmed?', 'How might we allow sales to easily enter campaign information into the system so that campaigns can go live quicker?' etc.</figcaption>

![Gathering the activity sheets to be transcribed into a document](/static/img/dashboard/dashboard-brainwriting.webp) <figcaption>After the sessions, the activity sheets were gathered to be transcribed into a Google document.</figcaption>

![Summary of the HMW ideas used as a reference by engineering on what to development](/static/img/dashboard/dashboard-hmw-summary.webp) <figcaption>Summary of HMW ideas. The development team used it as a to-do list and prioritised them into a backlog in Jira. Some example ideas include 'allowing clients to review content items to be used in their campaigns with a shareable link', 'better status indicators to show the progress of a campaign for transparency' etc.</figcaption>

## Wireframing concepts from competitor dashboard analysis

I analysed various competitors' dashboards to understand how they organise content for users to find data efficiently. Based on the insights, I created various wireframes and had stakeholders provide feedback such as suggestions on having an RFP (request for proposal) section for managing the sales pipeline. This activity highlighted the importance of reviewing competitors to validate design assumptions and learn best practices addressing similar challenges.

![Exploration of different ideas via wireframing by analysing competitor dashboards](/static/img/dashboard/dashboard-wireframes.webp) <figcaption>I analysed Rubicon's dashboard for managing magazine RFPs, which highlighted critical details like budget and targets that is required for sales to efficiently manage new advertising opportunities. Including a similar section in our dashboard would allow capturing these key data. This would help our sales team more efficiently manage prospects and for the team to plan for upcoming client campaigns.</figcaption>

![Exploring an alternative layout for the main page of the dashboard](/static/img/dashboard/dashboard-wireframe-main.webp) <figcaption>Exploring an alternative layout for the main page of the dashboard with additional data like performance of a campaign (pacing and clicks) and also filtering options for account managers to have better control on customising the layout based on their needs e.g. showing campaigns they are managing.</figcaption>

![A concept for an RFP section for the dashboard](/static/img/dashboard/dashboard-wireframe-rfp.webp) <figcaption>A concept for an RFP page with additional notes from stakeholder feedback on missing key data required in a RFP e.g. budget allocation, creative sizes etc.</figcaption>

![](/static/img/dashboard/dashboard-wireframe-showcase.webp) <figcaption>Exploring the concept of having a creative template page allowing account managers to select sizes a client wants to use for their ad campaign and efficiently do the content showcase using the templates. Currently, the front-end team have to manually build the templates and put them into the system, which can be time consuming and prone to human errors.</figcaption>

## Guiding development through user testing

With the development team preparing for sprint planning and development, we hired a contract senior ux designer to prototype a full campaign management dashboard. My collaboration with the designer involved providing context on our campaign management processes and how we used the existing dashboard. I also shared insights and challenges from user research and presented flow diagrams to help him visually see the flow of the system.

Some areas of the process had insufficient research data, so we leveraged existing data to prototype the key areas used regularly by the team in high fidelity. We also mapped a user flow to visualise navigation through the prototype, and did user testing using Invision and Silverback to gather feedback.

![](/static/img/dashboard/dashboard-user-flow.webp) <figcaption>A user flow illustrating how to create and manage a new campaign based on existing research data. The development team also referenced this to identify potential features to consider in the new dashboard such as search filtering and exporting of data.</figcaption>

![](/static/img/dashboard/dashboard-prototype-main.webp) <figcaption>A high-fidelity prototype of the main dashboard screen was created by Robert (senior UX designer) in Sketch. It featured key campaign metrics like performance and progress through using numbers, colors and graphs. These elements allow account managers to easily monitor and compare metrics when tracking campaigns.</figcaption>

![](/static/img/dashboard/dashboard-prototype-testing.webp) <figcaption>We did user testing for the campaign dashboard prototype using Invision and Silverback. User feedback highlighted the need for users to adapt their process to the new design. New terminology would require explanation on their purpose, such as through tooltips. The use of graphs was also confusing for users without clear labeling and explanation.</figcaption>

## Admin 2.0: an iterative process to dashboard refinement

The initial dashboard release supported the early adoption of programmatic advertising, allowing our company to offer this emerging technology as a new service. Key features such as data exporting and creative gallery preview improved account managers' workflow. Clear labeling and presentation of key data also enhanced transparency for campaign management. The automated workflow provided by programmatic advertising helped scale our business efficiently, increasing both client numbers and campaign capacity.

Working with unpredictable markets and needs taught me the importance of organic, iterative growth as requirements evolve over time. Focusing initial development on core functionality provided a stable foundation while additional features were gradually implemented. As a designer on such a project, flexibility and adaptability were key to collaborate effectively through this dynamic, user-centered design process.

The images below are screens of the new dashboard using some design elements from the prototype such as the navigation menu and colour scheme.

![](/static/img/dashboard/dashboard-final-main.webp) <figcaption>Main screen showing archived campaign data for Adobe.</figcaption>

![](/static/img/dashboard/dashboard-final-campaign.webp) <figcaption>AB Global campaign showing the different publishers it was running on.</figcaption>

![](/static/img/dashboard/dashboard-final-orders.webp) <figcaption>The Economist order for AB Global showing key data such as different budgets, creative sizes and overall campaign length for this publisher.</figcaption>

![](/static/img/dashboard/dashboard-final-showcase.webp) <figcaption>Creative showcase where account managers can preview content on a creative template for AB Global.</figcaption>
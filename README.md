## Hi there 👋

Thanks for checking out our repository and showing interest in the code that supports the annual Dancing England Rapper Tournament (DERT) through the DertInfo website and app. 

Each year a host team takes on the responsibility of hosting the event in their home city and takes on the challenge of finding and organising venues, recruiting and guiding judges, teaching the next generation and ensuring that we have a fair, well run, inclusive and enjoyable competition for all who attend.

The competition is one of the highlights of the rapper dancing community calendar and it is important to the community that they can be confident that the results will be accurate, and they will get positive and constructive feedback on their performances.

This is where DertInfo comes in and hopes to simplify some of these challenges through providing well-constructed, secure and reliable software to support the event.

Please note that we're new to running open source projects on GitHub so please support us with any knowledge that you have. 

## Getting Started

For a cross workload view of the ongoing work and the project in general please see the following two items

- Projects: https://github.com/dertinfo/dertinfo/projects
- Wiki: https://github.com/dertinfo/dertinfo/wiki

We track projects and big peices of work wich spans several of the workloads (applications, services) using GitHub projects. If you want to help us with planning the work and deciding what we work on next or help with deciding what issues are good for first time developers or are important to the community please let us know. Projects are public as are most issues in the projects (less security vunerabilites) and issues where relevant should be added to a project backlog. 

The wiki is where most of the technical documentation will be added to help communicate to contributors how the system works and design decisions in producing the system so that they can be evalauted against and new work that we're looking to complete. 

For each individual workload these are the respositories

- The Main Website: [https://github.com/dertinfo/dertinfo-web](https://github.com/dertinfo/dertinfo-web) 
- The Web App: [https://github.com/dertinfo/dertinfo-app](https://github.com/dertinfo/dertinfo-app) 
- The Api: [https://github.com/dertinfo/dertinfo-api](https://github.com/dertinfo/dertinfo-api)
- The Image Resizging Function App: [https://github.com/dertinfo/dertinfo-image-resize-v4](https://github.com/dertinfo/dertinfo-image-resize-v4)

A depiction and information of the architecture can be found here in the wiki: 

- [https://github.com/dertinfo/dertinfo/wiki](https://github.com/dertinfo/dertinfo/wiki)

Each of these projects has it's own README.md which gives more information about how to setup and run the workload. 

For all workloads there is a related docker container which is constucted and published from the main branch in all cases. This is completed by the Azure Dev Ops (ADO) build pipeline and these are downloadable from Docker Hub: [https://hub.docker.com/dertinfo](https://hub.docker.com/u/dertinfo). This allows you to run dependancies using docker and docker-compose for which each project has been make availbale in the location of "infra/docker/" allowing you to work on any single project without needing to setup all services in debug. 

Please note that at the time of writing there is currently minimal seed data in the database to allow the system to run and allow a user to engage with the system. As we gain support it is intededed that we can provide this to allow quicker engagement with some of the more compllex features of the system without having to first build a rich dataset from scratch.  Discussion here: [https://github.com/dertinfo/dertinfo/discussions/20](https://github.com/dertinfo/dertinfo/discussions/20)

## Technology

Have a look at the reposiories for specifics on the technologies used but as a general idea out clients are mostly written in Angular and typescript and are Single Page Applications (SPAs) that communicate with the API written in C# .NET. We use Azure for our hosting and Azure DevOps for out deployment pupelines. We use SendGrid for emails and we use SQL Server for our stuctured data. We use GitHub for managing the project and source control. Application insights for monitoring and telemtry. We use blob storage for unstuctured data. We also use docker for contaienrisation and devcontainers to support development. We use markdown for docuemntation and I'm sure there's a bunch of other stuff in here. 

## History

DertInfo was originally constructed for the DERT 2014 run by Black Swan Rapper at the time this was a single ASP.NET Razor pages website written by David Hall. 

After several iterations where the website changes to be an API with Angular Front End and then the addition of a formally native but now a web app the software used has changed significantly.

In 2024 following the birth of his daughter its tricky for David to continue to continue to allocate the time maintain, improve and patch the artefacts in the solution on his own and therefore DertInfo is now being gifted to the community under the GNU General Public License v3.0.

David will be continuing to support the team through being available to guide any contributors, complete code review and will offer insights and engage with discussions on the boards within GitHub. It is hoped that by engaging with the community the knowledge can be transferred to the community.

David informs that he has learnt an immeasurable amount from producing, improving and maintaining these software artefacts over the last 10 years and with the sincerest hope that by contributing you will too. 

## Contributing

Throughout the repositories in this account, you will find issues against each of the workloads. Please feel free to address any. Considered easy contributions will be marked with "good-first-issue" and any new issues that we need to review will be marked as "requires triage". 

Please note that the "main" branches are protected please refer to the [wiki](https://github.com/dertinfo/dertinfo/wiki) for the branching strategy details. Though in short we use feature branches with pull requests. 

<!--
For the web & app front ends we've constructed the .devContainers so that you can edit directly from GitHub codespaces and the codespaces will construct the API and downstream services based on the latest docker images. So in order to make changes to these items simply click the codespace and start editing. When you're ready create the PR. 
-->

At this time David will be notified of PR requests and will endeavour to review them as quickly as possible. As the community grows it is intended that we increase our pool of reviewers and approvers. 

Once your PR has been approved and merged your code will be deployed via automated tools in Azure DevOps to the staging environment. We can validate that it integrates with the other services correctly and then we can approve the promotion to the live environment. 

## Ideas, New Features, Process Improvements

If there is something that you want to work on that is not in backlog or an improvement that you would like to make please raise that as an idea under the [Discussions](https://github.com/dertinfo/dertinfo/discussions) and we can discuss how we can support you in making your idea a new feature and integrate it into the eco system. 

Also if you have any suggestion on ways to make contributing easier or safer then please get in touch as we're keen to hear your ideas. Please add these to the dicsussions.  

## Security

If you identify a security issue within the solution please contact us as dertinfo@gmail.com with a high priority email and details of your findings. We'll endeavour to triage and address the issue as soon as possible. Also in most repos we've enabled "Private Vunerability Reporting" to which you can raise a special security "issue" that will be private.

<!--
**dertinfo/dertinfo** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

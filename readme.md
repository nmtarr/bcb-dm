# BCB Data Management Foundation - synthesis workshops
This repository is set up to support a series of workshops and followup online work of the BCB team on our data management fundamentals. The workshops will focus on one of four areas that we use to organize our overall foundational data and product suite:

* Habitat characterization - including the National Terrestrial Ecosystems product and related data/information along with evolving work to characterize freshwater, estuarine, and marine ecosystems
* Species characterization - including the GAP Species Models and related data/information along with evolving modeling of freshwater fish species and observation data systems
* Protected Areas (and managed lands in general) - including PAD-US and our further evolution of that product
* Habitat impact characterization - a new data asset that is being built from NFHP work on habitat impact factors and how these are used to generate metrics and indices along with work to integrate and synthesize data on habitat treatment actions

The goal of the workshops is to bring together all members of the BCB team who are involved in managing data and information in these areas along with staff who are working on analytical work with these data to work on implementing and further evolving a set of core data management principles and practices. The work will advance the concepts of and build out the Biogeographic Information System, specifically the Data Reference Library component. In addition to our core team, we are inviting participation in the workshops and followup work from leadership with the USGS Community for Data Integration and the Earth Science Information Partners for additional expertise and perspectives.

## Core Principles
The following are some core principles for managing data that we are continuing to work on.

* Analytical results need to be reproducible and buildable - As we get more into providing more complex products from scientific analysis (e.g., reporting on the conservation status of groups of species in context with potential management options), the products of that work need to be fully reproducible from their base data and information. These products should have scientific software or workflows of some type that instantiate our thinking and analytical process, and those workflows need to be able to be run by someone other than us.
* Data should be online actionable - To meet the reproducibility principle and have our scientific software operate effectively, the data we are analyzing needs to be in an online and actionable form and not something that has to be downloaded and spun up locally in a specific environment to operate. There are all kinds of ways to do this, and the tech methods will get better over time. So, we need to employ usable software today to make this happen and be prepared to upgrade regularly as new capabilities are accessible to us.

## How to use this repo
This repository is essentially the live proceedings of our workshops and will continue as a living online tool for as long as it is useful. We want everyone to contribute to the repository who is directly involved in the workop, and anyone who is not able to be with us in person or who has an interest may also contribute. Here are some basic guidelines and procedures we will work with and evolve as needed with experience.

* Clone the repo and contribute code and documentation via pull requests - Pull requests in Git are a great way of having lots of folks contribute directly in a managed way. Everyone can have their own copy of the repo and then contribute changes to code and other artifacts by making those changes and issuing a pull request to the parent repo. As needed, we can take advantage of branching to go off in a completely new direction or just contribute back to the master branch directly.
* Try to do something with actual code whenever possible - We are now routinely using Jupyter Notebooks for software coding work in Python and R, and these serve well as combined code blocks with inline documentation and explanation.
* Use issues - As we identify specific things to work on or notes about specific topics, we'll use the Issues in this repo to document the specifics. The great thing about issues is that they can be commented on by anyone to keep a running conversation, and they can be assigned to team members for further work. They can also be labeled to organize them, and they can be closed out when we're done working on something.
* Science questions - The point of all this foundational data management stuff is to enable us (and others) to probe interesting science questions that we've articulated at a high level in our BCB Science Plan and elsewhere. We are especially thinking that we will capture specific science questions that we know we want to pursue with the data we are managing and talking about in the workshops. We can do that with code when it's possible to start writing code, but we can also do that with labeled issues and a conversation about how we would go about probing the question. Those questions will help us focus our efforts on the right parts of the data management challenge.
* Projects - As we put together a few issues or come up with some work we can do in code to get some work done, we'll use the projects feature in GitHub to create a project, do work on issues, submit code via pull requests, review it together, and then close out the project. Some projects may get done quickly within the course of an hour or so of work in the working group meeting, while others may get partially defined and then need to be handled after our meetings (let's try for more of the former and fewer of the latter).
* Asynchronous work from remote participants. While we are not planning to provide for traditional remote participation in these working groups, we have team members who may not be able to join us. Part of our experimentation in this will be on what sort of methods promote effective participation at whatever level in the work. Documenting things quickly, in real time within the GitHub repo means that folks who are not with us in person can comment on issues, post new issues of their own, submit working code, and even spin up and complete projects on their own.

## Provisional Software Disclaimer
Under USGS Software Release Policy, any software codes here are considered preliminary, not released officially, and posted to this repo for informal sharing among colleagues.

This software is preliminary or provisional and is subject to revision. It is being provided to meet the need for timely best science. The software has not received final approval by the U.S. Geological Survey (USGS). No warranty, expressed or implied, is made by the USGS or the U.S. Government as to the functionality of the software and related material nor shall the fact of release constitute any such warranty. The software is provided on the condition that neither the USGS nor the U.S. Government shall be held liable for any damages resulting from the authorized or unauthorized use of the software.
# Durable skills learned at American Express

## Overview of my learnings on the job

I joined my team at Amex at a crucial time. Our team is currently migrating our app from Angular to React. This migration is crucial to enhance app performance, ease troubleshooting for devs, reducing outages, making our app more scalable, and optimizing the development process. 

I have worked on crucial parts in this migration:

- A webworker which essentially allows javascript to be multithreaded instead of single threaded. This enhanced our apps performance by making our logger run on a seperate thread so it would not affect our UI. This was actually my first Jira story I was assigned. It was originally a spike but I managed to complete enough research during the sprint and implement the webworker.

    _JF 2.2: Can identify relevant and up-to-date software designs and how to read and implement functional/technical specifications_

- Adding Error Boundary using ```react-error-boundary``` library our the app. ```react-error-boundary```  is a react library that catches react component errors and renders a fallback UI. It also comes with features to re-render components that have failed. I also incorporated logging to this the Error Boundary. The logging logs fatal errors to splunk with the full error stack and other crucial information to help with debugging. This improvement has helped our team in real time a lot because now we have a detailed view to what exactly is failing thus allowing us to quickly solve errors.

    _JF 5.1	Knows relevant and up-to-date software testing frameworks and methodologies_

- I played a huge part in the migration of several components that are used daily by our customer service agents.
-  I followed our UX designers mocks and acceptance criteria listed in jira stories to successfully finish the stories on time. These were complex components that included dispatches to our redux store, using react state/hooks, and implementing custom hooks.
  
    _JF 1.4: Can distinguish between the different software development methodologies, such as agile and waterfall_

    _JF 1.6: Can follow software designs and functional/technical specifications_		

    _JF 2.3: Can develop effective user interfaces_

    _JF 2.5: Can implement a responsive User Interface_	

    _JF 2.6: Can translate wireframes into User Interfaces_

    _JF 2.7: Effectively manages state for complex User Interfaces_											

- I have also helped my team by completed open github issues.Holding a KT (knowledge transfer) on CMS (a content management system that is holding all of our static assets). Being present in deployment calls and helping to solve issues that arise after deployment. Deploying branches to our QA environment for testing.

    _JF 1.5: Can work effectively and contribute appropriately on a team to produce software_				

    _JF 1.7: Can follow company, team or client approaches to continuous integration, version and source control_	

    _JF 5.5	Understands and can apply structured techniques to problem solving, can debug code and can understand the structure of programmes to identify and resolve issues_			 	

- Currently I am deepening my knowledge of testing with jest by reading Mastering React Test Driven Development and also taking on larger stories.

    _JF 4.6	Can test code and analyze results to correct errors found using unit testing_		

## Technologies/methodologies learned

- react
- angular
- splunk
- jest
- agile
- scrum
- sass

## Contact

Andrea Berrocal - andrea.berrocal95@gmail.com

## Acknowledgments

Resources used for this readme

  - [Basic writing and formatting syntax](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)

Thank you to my multiverse coach Jonathan Jacka. Throughout the entire apprenticeship he was super attentive and always open to help. I can not express how thankful I am for this experience. I truly love my job and could not be here if it were not for his help.
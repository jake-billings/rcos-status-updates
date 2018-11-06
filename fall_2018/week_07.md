## Last Week's Accomplishments

> In this section, you can write about what you accomplished in the previous week.

> Examples:
> Bug fixes, Features added, Links to Issues, Links to Pull-Requests, Lightning Talks, Bonus Sessions

- Productivity was pretty high this week.
- Since switching to the frontend development team, I started working on boilerplate for a frontend webapp.
- I chose AWS S3 and CloudFront for frontend web hosting.
- I chose `react-create-app` to generate a basic react app
    - https://github.com/codingandcommunity/spaceport
    - https://github.com/codingandcommunity/spaceport/commit/1fb91ef4f98ac75bd748602e2060ef988f016ca5
- I setup deploy scripts to AWS for `spaceport`
    - https://github.com/codingandcommunity/spaceport/commit/3e6bbc91a84b245eaa14de77dde0b9ba0274201d
    - https://github.com/codingandcommunity/spaceport/commit/cefb5aebb7c8f1086ace27aed41a635acd37b9aa
- I used `fetch` to query the `booster` lambda from the `spaceport` API
    - https://github.com/codingandcommunity/spaceport/commit/96b95fa2c69ff63e817d3950e2381ad1da91b2f1
- In response to the grading talk Friday, I created a centralized repository for documentation for grading.
    - https://github.com/codingandcommunity/rcos-open-source-curriculum-project/commit/a9538d6ab238ded524ffe82854381a87e2e4a085
- In response to the grading talk Friday, I documented a ton of pending tasks as GitHub Issues
    - https://github.com/codingandcommunity/rcos-open-source-curriculum-project/issues/1
    - https://github.com/codingandcommunity/rcos-open-source-curriculum-project/issues/2
    - https://github.com/codingandcommunity/rcos-open-source-curriculum-project/issues/5
    - https://github.com/codingandcommunity/booster-read-projects-function/issues/3
- In repsonse to the grading talk Friday, I added a ton of additional documentation to all four repositories
    - https://github.com/codingandcommunity/booster-read-projects-function/commit/7f74faba83dcd4cba362685b3f57b9d63641a296
    - https://github.com/codingandcommunity/booster-project-hello-world/commit/6f44d9ca3d0131d410ab99453d49df786f00be53

Everything I do for this project will now be linked to from this repository: https://github.com/codingandcommunity/rcos-open-source-curriculum-project

We now have a full-stack website that can handle thousands of users via AWS CloudFront that we can deploy to in seconds using `yarn deploy`.

## This Week's Plan

> In this section, you can write about what you have planned for next week.

> Examples: New Bugs to be fixed, Design choices

- Finish setting up https://spaceport.codingandcommunity.org with an SSL certificate and AWS CloudFront.
- Begin work on an actual useful UI in the spaceport project.
- Communicate with the Atom plugin team if possible. They need to use the booster API.


## Anything Blocking?

> In this section, you can write about any blockers that you are having trouble in the project.

> Examples: Confusion on how to approach a problem, Limited experience with a specific technology

I'm working with Ethan Graff to setup the DNS zone file for codingandcommunity.org. I don't have access to it on my own, so I have to communicate with him to make changes.

## Notes

> This is an optional section for any sort of information that does not fall under any of the other categories.

None

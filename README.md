# USACS Hacker Badge

### Introduction
For some developers, it's impractical to invest large amounts of time and effort into crafting a professional portfolio website. However, it's still important that developers and job candidates have a hub that's easily accessible by recuiters, showcasing their work.

The objective of the USACS Hacker Badge project is to create that hub. Given the login credentials to servies including a developers body of work, including Github and Devpost, Hacker Badge will generate a hub for recruiters to view. Additionally, the web app will generate physical QR Code linking to the portfolio so that job candidates can easily share their work with recruiters.

### Services
We're planning to use **Github** and **Devpost** as services to scrape projects for the generated portfolio. We might add more in the future, but these should work fine for now.

### Getting Service Content
Devpost does not have an API that we can use to scrape data from. Github, however, has a dedicated Rest API for accessing user data. Since we'll only be scraping ***public*** information, we may scarpe data from Github as well, instead of using the Rest API.

That's it for now!

### Contributors
Sam Olagun
## Overview 👋

Knippert is an upcoming hairdresser platform.
This project is made to test building a production ready architecture using two backends and one client hosted on Azure.

Knippert consists of the following (private) repositories:

**knippert.webapp**
A full-stack Next.js (TypeScript) application. Authentication done on client-side (PKCE) to allow scaling into CDN based static application.  

**knippert.api**
ASP.NET Core Web API (C#). Implementing an ORM (Entity Framework Core) with Azure SQL Database. During development we run a Microsoft SQL Server 2019 Docker container to reproduce production scenario. Authorization is done using Microsoft Identity with Azure B2C.

The architecture involves using an CAIM (Azure B2C with Google as Identity Provider) to handle the authentication/authorization on three layers: the webapp backend/client and ASP.NET Core Web API.

More to follow.


<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->

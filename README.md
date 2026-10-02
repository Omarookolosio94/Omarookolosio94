# Hi, I'm Oghenemaro 👋

Seven years ago, I started writing code for banks. Since then, most of what I've built has been about money moving between people who don't know each other and have no reason to trust each other. Payments, loans, marketplaces.

The thing nobody tells you about that work is how little of it is the code. It's the state machine. It's the error message. It's the merchant developer on a call at 9pm who can't get a test purchase to go through, and the realisation that the endpoint you thought was obvious isn't obvious at all.

I like that part. I build the thing, document it, and stay with it in production.

- 🧱 C#, .NET and ASP.NET Core on the backend. TypeScript with React, Next.js, Angular, Vue, and Svelte on the front end
- 🗄️ SQL is half my job: schema design, indexing, reading query plans, making slow things fast
- 📝 I write the docs, review the pull requests, and answer the integrator's call
- 🦀 Learning Rust, slowly, on purpose

### 🔗 Links

[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=About.me&logoColor=white)](https://omaro.netlify.app)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/oghenemaro-okolosio/)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:omarookolosio94@gmail.com)
[![Book a call](https://img.shields.io/badge/Book%20a%20call-4285F4?style=for-the-badge&logo=googlecalendar&logoColor=white)](https://calendar.app.google/DdpEDtJUyqwCBk6M7)

### 🛠 Projects

#### [Buy Now Pay Later](https://www.stanbicibtcbank.com/nigeriabank/business/products-and-services/ways-to-bank/buy-now-pay-later)

A customer wants the item today and wants to pay for it over the next six months. The merchant cannot wait six months. Somebody has to stand between them.

I built that somebody. An ASP.NET Core API and an Angular portal where a merchant offers instalments at checkout, gets paid in full the same day, and the customer repays over time. SignalR pushes the status live, so the merchant, the customer, and the bank are all looking at the same truth at the same moment.

Then I wrote the public docs and sat with the merchant developers while they integrated. That turned out to be the most useful thing I did. Several endpoints got redesigned because of those calls.

#### [EZ Cash](https://ezcash.stanbicibtc.com)

A bulk upload on the admin portal took over 25 minutes. Long enough that people started it and went to lunch.

I pulled it out into its own service. Under 6 minutes.

Then I went after the loan application path itself, and 24% more applications started making it through to the end. Then the onboarding errors, which told administrators almost nothing, so customers stalled halfway through KYC and never came back. Clearer failures, clearer guidance, faster completion. Same system, three different kinds of slow.

#### [CampusRunz](https://campusrunz.com)

Students need a ride, a room, groceries, laundry, food. Ten separate businesses that all happen to live in one app.

I own the architecture and run engineering across six repositories. Right now I'm leading a four-engineer team through a phased rebuild of the .NET API, moving web, admin, and mobile onto it while the old one keeps serving real users. Nothing goes dark.

Before that, the admin portal took over 10 seconds longer to load than it should have. Decoupled the frontend, added lazy loading and client-side caching, and got those seconds back. [Web app](https://app.campusrunz.com)

### 💻 Tools & Skills

![C#](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=c-sharp&logoColor=white)
![.NET](https://img.shields.io/badge/.NET-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-5FA04E?style=for-the-badge&logo=node.js&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white)

![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white)
![Angular](https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white)
![Vue.js](https://img.shields.io/badge/Vue.js-4FC08D?style=for-the-badge&logo=vuedotjs&logoColor=white)
![Svelte](https://img.shields.io/badge/Svelte-FF3E00?style=for-the-badge&logo=svelte&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)

![SQL Server](https://img.shields.io/badge/SQL%20Server-CC2927?style=for-the-badge&logo=microsoftsqlserver&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Oracle PL/SQL](https://img.shields.io/badge/Oracle%20PL%2FSQL-F80000?style=for-the-badge&logo=oracle&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-FF4438?style=for-the-badge&logo=redis&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)

![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-FF9900?style=for-the-badge&logo=amazonwebservices&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

### 📊 Stats

![](https://github-readme-stats.vercel.app/api?username=omarookolosio94&theme=default&hide_border=true&include_all_commits=true&count_private=true&show_icons=true)
![](https://github-readme-stats.vercel.app/api/top-langs/?username=omarookolosio94&theme=default&hide_border=true&include_all_commits=true&count_private=true&layout=compact)

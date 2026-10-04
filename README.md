#### Hi, I'm Oghenemaro 👋

Seven years ago, I started writing code for banks. Since then, I've built mostly systems for moving money, tracking where it goes, and making sure everyone involved agrees on what happened. Payments, loans, instalment credit, marketplaces.

Over time, I've become just as interested in what happens after the transaction as what happens before it. A payment can succeed, but does the ledger reflect it? Do the records reconcile? Can the business see what happened without someone spending half a day pulling spreadsheets together? 

That's where my work has been taking me lately: building data solutions, automating reconciliation processes, and turning reporting workflows that once depended on manual effort into repeatable, reliable systems.

Nobody tells you that building financial software is mostly not code. It's the state machine. It's the failure mode. It's the difference between a transaction being successful and a transaction being accounted for. It's the merchant developer on a call who can't get a test purchase through.

I like working across that entire chain. I build the services, work with the data, automate the processes, document the interfaces, and stay with the systems in production.

- 🧱 C#, .NET and ASP.NET Core on the backend. TypeScript with React, Next.js, Angular, Vue, and Svelte on the front end
- 🗄️ SQL is half my job: schema design, indexing, reading query plans, making slow things fast
- 📝 I write the docs, review the pull requests, and answer the integrator's call
- 🦀 Learning Rust, slowly, on purpose

#### 🔗 Links

[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=About.me&logoColor=white)](https://omaro.netlify.app)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/oghenemaro-okolosio/)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:omarookolosio94@gmail.com)
[![Book a call](https://img.shields.io/badge/Book%20a%20call-4285F4?style=for-the-badge&logo=googlecalendar&logoColor=white)](https://calendar.app.google/DdpEDtJUyqwCBk6M7)

#### 🛠 Projects

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

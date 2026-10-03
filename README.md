#### Hi, I'm Oghenemaro 👋

Seven years ago, I started writing code for banks. Since then, most of what I've built has been about money moving between people who don't know each other and have no reason to trust each other. Payments, loans, marketplaces.

The thing nobody tells you about that work is how little of it is the code. It's the state machine. It's the error message. It's the merchant developer on a call at 9pm who can't get a test purchase to go through, and the realisation that the endpoint you thought was obvious isn't obvious at all.

I like that part. I build the thing, document it, and stay with it in production.

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

# Skills Self-Assessment

- *Last Updated: Sep 10, 2024*
- *Previous Update: Sep 1, 2023*

I've been using Medium's growth metrics as a self-assessment tool to help identify my areas of growth, and to drive me to pursue them. They also serve as reminders to keep certain skills sharp. Hopefully, others might find this tool valuable.

## Current Areas of Development

- **Communication**: Pitch and sell people on org-wide developer productivity improvement initiatives.
- **Initiative:** My focus for the next six months is to positively impact as much of the organization as possible with my background in code quality, software engineering principles, observability, and flow engineering. Ostensibly, this will be targeted at Developer Experience and tech debt reduction.
- **Servers**: Get to advanced Go, and intermediate Rails. Continue to build upon knowledge of Kubernetes to improve our CI pipelines for better deployment times, and stability.
- **Supporting**: Start to impact the org with Staff+ activities.  
  
## The Medium Engineering Growth Rubric

The [rubric](https://docs.google.com/spreadsheets/d/1EO-Dbsayn8Nz9Ii3MKcwRbt-EIJ2MjQdpoyhh0tBdZk) provides detailed explanations of the categories below.

I've also resurrected [Medium Snowflake](https://snowflake-blond.vercel.app/#1,3,3,3,4,3,4,3,3,2,3,3,4,2,3,4,Stephen%20Kawaguchi,Principal%20Engineer) which is an invaluable tool to understand the rubric in more detail, and also the big picture around your own growth. Feel free to use it for your own self-assessment! Just modify the URL query string parameters to "save" your settings. **Note:** Medium itself has [evolved past using it](https://medium.engineering/engineering-growth-at-medium-4935b3234d25)).

Refer to Medium's [Engineering growth: Introduction](https://medium.com/s/engineering-growth-framework/engineering-growth-framework-overview-4e02ab330524) for more details on their engineering growth philosophy. It's one of the most useful ones in the industry. 

| Skill | Milestone | Points | Justification |
| :---- | --------: | -----: | ------------- |
| **Build** |
| **Mobile** | 1 | 1 | Experience with IBM Cognos React Native app deployed as iOS and Android. I did significant refactoring, but my focus was success with Continuous Delivery and I didn't have much hands-on experience with low-level mobile features. A few years removed, and not much has changed.  |
| **Web Client** | 3 | 6 | 20+ experience with web clients. Strong JavaScript knowledge, along with SPAs like React and a bit of Svelte. Low-level performance optimization. **Update:** I've done a bit of front-end work recently, mostly in Svelte for a couple of admin UIs. Overall, my knowledge is stable but I need a refresher in React. | 
| **Foundation** | 3 | 6 | **Update:** I believe my Kubernetes knowledge is good for a developer. I've done a lot of work over the years in CI servers - the past few years it's been GitHub Actions. I've gotten a lot more experience with multiple datastores in the past year: PostgreSQL, MySQL, DynamoDB, OpenSearch, and Kafka. I have no ML systems experience. I regularly debug problems and do things like reduce deployment times from 12 - 6 minutes, and many general fixes. I also set up and maintain our enterprise API Gateway using Tyk OpenSource. I was also part of refining our incident management process and establishing Game Days as a practice. I spearheaded our distributed tracing to move us away from our log-heavy debugging approach for the Orchestrator microservice that's my team's primary responsiblity. |
| **Servers** | 3 | 6 | We handed off our most complex service which included an ingestion pipeline using Kafka, ETLs, OpenSearch, and DynamoDB. I'm one of debuggers. I also contribute to our Go service template, including a major refactor to backfill integration tests. I've written the majority of the runbooks for our services. |
| *Sub-Total* | 10 | **19** |  (Sep 2024: +1/+3) |
| **Executing** |
| **Project Management** | 4 | 12 | 4 yrs/eng. manager + 2 yrs/eng. director + ~6 yrs/responsible tech leader. I was torn on this grade, but my PM seemingly has remained intact as I've had to leverage these skills even as a non-manager. On top of that, I've had to learn how to lead via influence vs. direct responsibility. For example, I've been unfortunate enough to coordinate ungodly levels of cross-team communication (4 teams on average, up to 30+ teams) and complex delivery. I've continued my study of leadership and management principles. I'm constantly looking to find ways to incrementally deliver high-quality software that meets product objectives using SixSigma, Lean, Agile, and DevOps processes, principles. Furthermore, I'm constantly working to establish these as cultural norms because they fundamentally support project delivery and lead to learning organizations with generative outcomes. **Update:** According to my colleagues, my contributions in this area have helped create a sense of delivery confidence. I ran point on the first production integration for our new API platform, and supported another major initiative in many ways. I also teamed up with another dev to roll out our new Flipp Developers' Portal. Executing all of these kept my project management skills pretty fresh. I even had to start attending our EM/PM weekly sync to identify risks and empower our Technical Delivery Manager with the data she needed to successfully argue for the proper delivery date. |  
| **Communication** | 3 | 6 | I believe my verbal and written communication is strong. I've communicated regularly with developers up to VPs. I've presented to dozens or hundreds of people at internal business meetings and guilds, but have NOT done any conference speaking. I'm a sporadic [blogger](https://skawaguchi.substack.com/) but have written substantial internal guides, standards, learning curricula, and primers. Topics include: Adopting [CUPID](https://dannorth.net/cupid-for-joyful-coding/), How to write tests, a software engineer's career growth roadmap, multiple SonarQube code quality guides, Consumer-Driven Contract Testing with Pactflow, Always-Shippable coding, a TDD internal conference talk, a TDD course, and how to formulate a microservice testing strategy. My favourite play is to take a problematic code component and rehabilitate it, and use my own code as examples of code smell identification, refactoring patterns, TDD/BDD, the application of design patterns, and other techniques. **Update:** My 2024 development target was to improve my conciseness and clarity. After working on this with my boss for six months, I took a poll of my colleagues to gauge my growth. They confirmed it was a night and day improvement. Next up: I'm about to work on some cross-org impact work with an eye towards developing my ability to pitch major approach changes. This will be the next level for this skill. |
| **Craft** | 4 | 12 | When it comes to coding principles, I'm heavily influenced by Agile thought leaders. I advocate for software craft through discussion, instruction, and practice. I'm also always learning this topic more deeply through my own research and experimentation. topics like CUPID, SOLID and software simplicity. I've written code using TDD/BDD for 7+ years, leading to greater understanding of design, code smells, and refactoring patterns. I push for better code quality metrics (beyond code coverage). I also make a point of providing extra knowledge in code reviews to teach software engineering principles. I've also been applying and teaching software architectural thinking, such as using architectural characteristics to drive trade-off decisions, thinking of fitness functions to preserve evolvability, and driving the application of architectural approaches, such as Functional Core, Imperative Shell, Hexagonal Architecture, and Clean Architecture as they are practically applied to microservices. |  
| **Initiative** | 3 | 6 | After a brief initial acclimatization stage, I've always thrown myself into the hardest or most valuable problems. At this point, I'm also wired to identify risk. After I do so, I advocate for preventative change, or simply put them in place as my normal order of business. Having been around onboarding practices and hiring practices, I would say that I've helped to significantly improve those activities in every organization I've been part of. Partly, it stems from Lean Management philosophies, and partly, it's a desire to create a psychologically safe environment from every teammate's Day One. From an engineering perspective, I refine and improve Agile methods through feedback and intention-setting, adoption of DevOps practices. I've led the charge from transitioning predilications for monoliths towards cloud-native, domain-aligned thinking to break down big, slow releases (and problems) into small, faster ones. I've also been deployed solve fundamental organizational problems, such as driving organizational adoption of TDD (John Deere), driving a Continuous Delivery mindset (IBM), and figuring out how to transition a high-profile but struggling team to greater levels of stability through coding practices, software engineering knowledge, and better architectures (Ada). Much of my work has been leading multiple teams with crippling architectural and technical debt levels and breaking down mindsets resistant to change, with facts (identifying broken systems), data (e.g. 90% bug reduction), and hands-on examples generally preferring to offer my own code up to provide lessons-learned. An area of growth for me is to exercise my autonomy more effectively and take steps to tackle the big problems nobody knows how to solve without asking for permission but without going totally rogue. |
| *Sub-Total* | 14 | **36** |  (Sep 2024: no change) |
| **Supporting** |
| **Career Development** | 3 | 6 | **Update:** I believe that I've established myself as a solid backend developer. I'm still getting used to startups after 20+ years in enterprise. I'm now pretty comfortable with my new domain (ad tech). I've also demonstrated that I can learn many things in short order, including bouncing between business domains. This year I've been in: geo-location (PostGIS), content search (OpenSearch), and now personalization. In terms of what _new_ things I've done in the past two years, a product vision doc, used The Startup Way/Scientific Method to drive technology choices, written production Go and Rails, researched and delivered an MVP API Gateway (Tyk) which is being used by multiple teams in production, developed a real-time image transformation pipeline in AWS (CloudFront, Lambda, Lambda@Edge with experiments with API Gateway and S3). I've also had two formal mentees, and another informal mentee. | 
| **Org Design** | 2 | 3 | I've been studying organizational design from the perspective of aligning teams to business domains for a while. I'm influenced by the Inverse Conway Maneuver,  Team Topologies, Systems Designs, the Spotify Model, and Domain Driven Design as an organizing concept for microservices. I've never led a re-org. Until I jump ladders to management, I probably won't be anything more than an interested advisor. Without having that kind of skin in the game, I'm not sure I'd really qualify as having a higher score. **Update:** I continue to research this and have discussions, but this is pretty far outside of my purview. |
| **Wellbeing** | 3 | 6 | I work very hard to foster a learning culture in my area. I've co-founded multiple learning clubs across organizations, contributed to the IBM Agile Academy, given multiple internal talks, and worked to create collections of resources. I do this to ensure my teammates are constantly challenged to grow at their own pace. I also hunt down work I believe they will find interesting. My goal is for them to be engaged and have a safe space to ask questions and learn. I try to inject as much rigour into our work without being overbearing. I wouldn't say I'm a cultural leader - more of a positive contributor. I recognize that some managers and other leaders contribute much more to the overall environment than I do - especially when I'm in heavy learning mode. My other criticism is that I don't shake things up as much as I used to. Part of it is because as I've risen higher and shifted to smaller orgs (startups), my ability and opportunity to focus have seen a steep decline. I'm trying hard to work on this - it was the central point of my PD plan at my last job and a constant focus. I've mostly developed this by reading books revolving around how to be more impactful in terms of formulating and executing strategy: The Art of Action, Lean Startup/The Startup Way, Radical Focus, Escaping the Build Trap, Accelerate, Staff Engineer, The Art of Business Value, Atomic Habits, Algorithms to Live By, Think Again, Limitless, The 7 Habits of Highly Effective People, and several others. My point is that I want to understand how to be a more effective person, and how to coach others (and parent my son) to be effective. **Update:** I've seen modest growth in this area. My learning has been paying off in terms of personal awareness, contentedness, ability to deliver, and ability to juggle more (by doing less!). |
| **Accomplishment** | 3 | 6 | **Update:** I've been doing more hands-on delivery in the past year and stretching my borders. Not enough to warrant any score change in either direction. To recap, I wrote my first-ever product vision doc, jumped fully into the back-end (Go, Rails, MySQL, PostgreSQL/PostGIS, DynamoDB) and cloud-native (Tyk, AWS API Gateway, CloudFront, S3, Go Lambda, Lambda@Edge). I also went from two AI-focused product organizations (although NOT on an ML or AI team myself) to an ad tech company where my long-term focus will be geo-spatial computing. Previously, I've taken several teams from siloed and low-performing to exemplary within their product groups. For example, by using Lean / Agile / DevOps strategies, I was able to lead my current team to the highest SonarQube metrics and gating conditions across ~2,000 developers and to turn them into the only DevOps-capable team deploying at 6x the rest of the org in a group of ~100 developers. I've also used coaching to halt departures and drastically increase engagement. I've done this for years in different situations. I've encouraged my team to do better in terms of our LinearB metrics, but I settled for picking up the slack myself to meet our performance OKR on Pickup Time. | 
| *Sub-Total* | 11 | **21** | (Sep 2024: No change ) |
| **Strengthening** |
| **Mentorship** | 4 | 12 | I currently have one formal mentee, and one informal one on my team.I've kept up mentorship relationships even after leaving big enterprises, and am pretty satisfied with my loose interpretation of Radical Candor-style 1:1s (with a focus on technology). Through 1:1s and informal mentorship, I've guided dozens of developers through their soft skills and software engineering knowledge growth. I'm very happy that many have moved on to leadership positions and/or pretty great organizations. I'm struggling to figure out how to scale these past 1:1s beyond inspiring my mentees to become mentors themselves. Update: Recently, I've worked with a few pretty amazing mentors, so I recognize that I have a lot to learn. I also feel like I'm not a very good mentee because I need to think harder about what I want to do and be more concise when I get 1:1 face time. I run Radical Candor style 1:1s for technical coaching with 7 developers currently and as many as 12 concurrent developers in the past. Most of my work has been with engineers, but I've also mentored architects and coached managers and executives.  | 
| **Evangelism** | 2 | 3 | I've evangelized Flipp to my network and made several job referrals. We have a rather detailed referral process, so it's actually quite time-consuming. Apparently, I write some of the best referral applications. I've spent most of my evangelism energy advocating for ways to improve Flipp Engineering capabilities. |
| **Recruiting** | 3 | 6 | I've been a hiring manager multiple times. I've conducted over 200 technical interviews and created an interviewing process. I've also built up multiple teams from scratch. **Update:** I've been part of hiring teams again, and have had a (small) hand in selling candidates on our culture, and taking the time to answer the questions behind their questions and creating a welcoming interview environment. I generally appeal to their desire for growth, and am pretty frank about the culture and opportunities in whichever org I'm working with. | 
| **Community** | 4 | 12 | I work hard to build bridges within my org. In this case, even though it's generally outside my purview as a senior dev, I'm still working across teams to improve our organizational abilities and look for hotspots and risks. I founded a Software Engineering Book Club where we read The Pragmatic Programmer, 20th Anniversary Edition. We used that to cover a lot of ground to learn about the concepts of the book, but with additional tangential teachings to help club members apply the concepts. We also have had active Slack discussions around a host of topics. So far, it's the only place where engineers from across the org come to discuss software engineering concepts and improve their craft. At IBM, my team had to work with 30+ teams - from dependencies, compliance/audit, and partnerships. There would be no chance of success if I hadn't brought all of my collaborative abilities to bear and run our product through the gauntlet. I also help foster a learning culture by giving occasional talks, leading and participating in study groups (DDD, Staff+ engineering, Kubernetes/cloud native, Clean Code) and guilds (Agile, Go), and sharing insights from my personal research with interested parties from developers, to managers, to exectives. I help other teams with their initiatives without sacrificing my own team's initiatives. I'm always hunting for win-win collaborations. |
| **Sub-Total** | 13 | **33** | (Sep 2024: +2/+6 )
| **TOTAL** | 48 | **112** | **Principal Engineer/Director of Engineering** |

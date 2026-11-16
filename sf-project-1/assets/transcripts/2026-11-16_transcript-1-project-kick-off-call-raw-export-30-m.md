# Transcript 1: Project Kick-Off Call (Raw Export - 30 Minutes)

00:00:04 Sarah Jenkins: Good morning everybody thanks for hopping on right on time. Give it maybe thirty seconds to see if anyone else is joining from the Vanguard side. Elena are we expecting anyone else today?

00:00:18 Elena Rostova: Morning Sarah. No I think it is just David, Liam, and me on our side today.

00:00:24 Sarah Jenkins: Awesome. Well let's dive right in so we respect everyone's calendars. Let's do a quick round of introductions first so everyone knows who is who and what role we are playing on Project Horizon. I will start. I am Sarah Jenkins, Engagement Manager here at Apex Cloud Partners. My job is keeping us on schedule, managing the budget, removing blockers, and making sure the SOW stays on track. Marcus do you want to go next?

00:00:52 Marcus Vance: Yeah sure. Hey everyone, Marcus Vance, Lead Solution Architect. I am going to be leading the discovery workshops starting tomorrow, designing the overall data model and security setup, and making sure everything we build fits together cleanly for your team.

00:01:09 Priya Nair: Hi everyone I am Priya Nair, Senior Salesforce Consultant on the Apex side. I will be doing the hands on configuration in your sandbox, building the flows, working closely with Liam on data migration, and running training once we get closer to launch.

00:01:26 David Thorne: Morning everyone. David Thorne here, VP of Operations at Vanguard Logistics. Really excited to finally get this moving. We have been living out of spreadsheets and an old Zendesk setup for way too long, so my main priority here is getting clean visibility into our freight pipeline and making sure dispatch issues don't slip through the cracks when a deal closes.

00:01:51 Elena Rostova: Hi all, Elena Rostova, Director of Revenue Operations. I am acting as the day to day product owner for Vanguard. I will be coordinating our sales and support leads for discovery sessions and helping make quick decisions so we don't stall out on your timeline.

00:02:09 Liam O'Connor: Hey guys, Liam O'Connor. I handle internal IT systems and database exports right now, and I actually just passed my Salesforce Admin cert last month. So I am looking forward to shadowing Priya during the build so I can own the org once we go live.

00:02:27 Sarah Jenkins: Oh congrats on passing the admin exam Liam that is huge. Having an in house admin ramping up alongside us makes post go live handover so much smoother. Let me share my screen here real quick. Can everybody see the kick off deck?

00:02:44 David Thorne: Yep got it.

00:02:46 Elena Rostova: Yes looks good.

00:02:48 Sarah Jenkins: Perfect. So we have got about twenty five minutes left and I want to walk through five quick things. Project vision and scope guardrails, our ten week timeline, how we are going to work together week to week, licensing and environment readiness, and then immediate action items for tomorrow's first discovery call.

00:03:11 Sarah Jenkins: Starting on slide two with the scope recap. As David mentioned, we are replacing your legacy spreadsheets and Zendesk instance with Salesforce Sales Cloud and Service Cloud for sixty five total users. Forty five on the sales side and twenty on support. Just to reiterate our phase one guardrails from the SOW so there are no surprises later, we are strictly keeping ERP and WMS integrations out of scope for phase one, and we are not doing CPQ or custom Apex code. We are sticking to declarative configuration and standard objects so we hit your target launch window. David, Elena, still completely aligned on that?

00:03:54 David Thorne: Yes hundred percent. We know we eventually want NetSuite talking to Salesforce in phase two, probably Q3 next year, but right now our reps just need one place to track quotes and hand off new accounts to support without emailing spreadsheets around.

00:04:12 Marcus Vance: That is great to hear. Keeping phase one focused on core process and clean data is the single best way to guarantee an on time launch. Looking at slide three, let's walk through the ten week schedule. Weeks one and two, starting today, are Discover and Design. We have got four discovery workshops booked across this week and early next week covering sales, service, security, and reporting. Our goal is to deliver the Solution Design Document by next Wednesday and get your formal sign off by Friday November twenty seventh.

00:04:50 Elena Rostova: Quick question on that date Marcus. Next Thursday and Friday is Thanksgiving break for us, our offices are closed both days. Does that affect the SDD sign off timeline?

00:05:04 Sarah Jenkins: Good catch Elena. Let me look at the calendar here. If your team is out Thursday the twenty sixth and Friday the twenty seventh, we will shift the SDD walkthrough to Tuesday the twenty fourth and aim for sign off by Wednesday afternoon before everyone logs off for the holiday. That way we don't lose momentum going into week three build. Does that work for you and David?

00:05:29 Elena Rostova: Tuesday walkthrough and Wednesday sign off works for me. David?

00:05:34 David Thorne: Yeah that works, just make sure it is on my calendar before noon Wednesday because I am catching a flight that afternoon.

00:05:42 Sarah Jenkins: Done, I will send that invite right after this call. Marcus go ahead on weeks three through six.

00:05:49 Marcus Vance: Yeah so weeks three through six are our Build and Configure sprints. Rather than disappearing into a cave for a month and showing you the system at the very end, we do live playback demos at the end of week four and week six. That lets you click around, see your actual fields and page layouts, and tell us early if something feels clunky.

00:06:13 Elena Rostova: I love that approach. Who should I invite to those demos? Should I bring in our regional sales managers or keep it smaller?

00:06:24 Marcus Vance: For week four, keep it tight. Just you, Liam, and maybe one trusted sales rep and one support lead. By week six when the flows and dashboards are wired up, definitely bring in the regional managers so we get their buy in before UAT starts in week seven.

00:06:44 Priya Nair: And speaking of week seven, Liam I want to touch on data migration early so it doesn't become a fire drill later. Per the SOW we are migrating active Accounts, Contacts, Open Opportunities, and the last twelve months of closed Cases from Zendesk. I am going to send you our CSV mapping templates tomorrow morning. Ideally we want a sample export from you by week four so we can test a dry run load into the sandbox before UAT.

00:07:16 Liam O'Connor: Okay makes sense. One thing I should warn you about now is our legacy customer database is pretty messy. We have got duplicate accounts everywhere, like Acme Logistics and Acme Logistics Inc and three different addresses under the same parent company. Is deduplication something you guys handle during the load or do we need to clean that first?

00:07:41 Priya Nair: Good question. Under the SOW, source data cleansing and deduplication sits on Vanguard's plate prior to us loading the files, mostly because only your team knows which version of Acme Logistics is the real billing entity. However, I will send you a quick Excel matching checklist and some formulas you can run to flag duplicates fast so you aren't staring at ten thousand rows manually.

00:08:09 Liam O'Connor: That would be super helpful, thanks Priya.

00:08:13 Sarah Jenkins: Moving to slide five on project governance and communication. We want to keep things lightweight and transparent. First, we will spin up a shared Slack channel between Apex and Vanguard today so Liam and Elena can ask quick questions without waiting for a formal meeting. Second, we will hold a thirty minute weekly status call every Wednesday at ten AM Eastern. Every Tuesday afternoon I will email out a one page status report with our RAID log, tracking risks, actions, issues, and decisions, so we spend Wednesday mornings solving blockers instead of reading status updates.

00:08:55 Elena Rostova: Wednesdays at ten AM Eastern works great for me.

00:08:59 David Thorne: Same here, I might drop into every other one just to keep a pulse on things, and if you guys ever hit a wall on a scope question or need a tie breaker, just ping me directly.

00:09:11 Sarah Jenkins: Appreciate that David. Let's check environment readiness real quick before we wrap. Liam, have you guys already provisioned your Salesforce Enterprise Edition org and spun up a Partial Copy sandbox?

00:09:26 Liam O'Connor: Production is live and provisioned, yes. I haven't created the Partial Copy sandbox yet because I wasn't sure if you wanted us to build it before or after we set up user licenses.

00:09:38 Marcus Vance: You can spin up the Partial Copy sandbox right now, it doesn't depend on user licenses yet. In fact, go ahead and kick that off today because sometimes Salesforce takes a few hours to provision a partial sandbox, and we want to start configuring in there right after discovery. Also please create System Administrator user accounts for Priya and me in both Production and the Sandbox.

00:10:04 Liam O'Connor: Will do. I will get those logins sent over to both of you right after lunch.

00:10:10 Sarah Jenkins: Awesome. Let's do a quick check on tomorrow's first discovery session. We have an hour blocked from one PM to two PM Eastern focused on Sales Cloud, covering lead management, accounts, contacts, and your opportunity pipeline. Elena, who from your side is joining tomorrow?

00:10:30 Elena Rostova: It will be Liam and me, plus Carlos Mendez who is one of our senior enterprise account executives. I also asked our inbound sales coordinator, Maya, to join for the first twenty minutes so she can show you how web leads currently come into the shared inbox.

00:10:49 Marcus Vance: That is the exact right mix of people. One request for Carlos and Maya, please tell them to bring real examples. If they can share their screen and show us an actual rate spreadsheet, a messy quote email, or how they currently track follow ups, that helps us way more than looking at a clean flowchart.

00:11:11 Elena Rostova: Already told them to have their real trackers open.

00:11:15 Sarah Jenkins: Fantastic. Let's recap our immediate action items before we give everybody back a few minutes. Liam is creating admin logins for Marcus and Priya and kicking off the Partial Copy sandbox today. Priya is sending over the data templates and pre discovery notes tomorrow morning. I am sending out the updated Tuesday Wednesday SDD review invites for next week and setting up our shared Slack channel today. Anything else from anyone before we wrap up?

00:11:48 David Thorne: Nothing from me. Thanks team, looking forward to getting off these spreadsheets.

00:11:54 Elena Rostova: Thanks everybody, talk tomorrow at one.

00:11:58 Sarah Jenkins: Thanks all, have a great rest of your day.



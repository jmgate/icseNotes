# Notes from ICSE 2018

## Sunday, May 27 (Cooperative & Human Aspects of Software Engineering)

### Psychological Safety and Norm Clarity in Software Engineering Teams

* What Google Learned from its Quest to Build the Perfect Team
* Impact, Meaning, Structure & Clarity, Dependability, Psychological Safety
* Psychological safety is a shared belief that the team is safe for interpersonal risk taking.
* Team norm clarity:  In a team with high norm clarity, it is clear what is,and what is not, acceptable behavior.
* Team norm clarity seems to be a slightly better predictor of job satisfaction, etc., than psychological safety.
* How can you foster psychological safety and norm clarity in software engineering teams?

### The Structure of Software Design Discussions

* Design Erosion:  Information on the design of a project slowly deteriorates over time.
* Can we use discussions to recover design information that's been lost?
* How does design information occur in written discussion?  (Where?)
* How are elements of design information related in a written discussion?  (How?)
* Structure of a discussion is nonlinear.
* Candidates (potential solutions) are often hard to distinguish from questions.

### Research Cooperation and Communication in Continuous Software Engineering

* Continuous Software Engineering:  Releasing ASAP; two weeks = a year.
* Challenges:  Tooling & architecting, quality, and business & user interaction.
* Automate the build, test, deploy pipeline.
* Challenges:  Design for testability & deployability.
* Your test automation is only as good as your test suite.
* How can we make the business agile enough to mesh with the agile development?
  * Continuous planning and budgeting.

### Some reasons why actual cross-fertilization in cross-functional teams is difficult

* Cross-functional:  The team has all the expertise it needs without any outside help.
* Cross-fertilization:  Spreading knowledge from different domains and people across the team.
* What is motivating or demotivating team members to work in a cross-functional manner?
* Inclination to interact  affected by:
  * Perception of inefficiency
  * Desire to learn
  * Sense of domain responsibility:  to keep the work and your personal knowledge in your own domain in proper shape.
  * Issues with career progression
  * Domain distance:  if you're required to do something further away from your area of expertise.
  * Wrong level of detail
  * Loss of focus
* Cognitave distance&mdash;connects to domain distance and level of detail.  Preknowledge of individuals likely a factor.  Personal motivation and personality also.
* Zone approximate development?

### What would a science of software engineering look like?

Jim Herbsleb @ Institute for Software Research @ Carnegie Mellon
* Does SE research have impact?
  * No one seems confident.
  * Computer science is the scientific underpinning of SE, but SE is not CS.
* Does science create impact?
  * Trial and error is a slow way to work toward an understanding.
  * Science may not have immediate application.
  * "Theory-oriented software engineering"; "A systematic review of theory use in software engineering experiements"
* What sort of science?
  * Human science of software engineering.
  * Problem:  people finding the right experts at a remote site.  Solution:  expertise browser.
  * Transactive memory systems (TMS).
  * Socio-technical coordination:  think of it as a constraint satisfaction problem over engineering design decisions.
* Barriers to human science of SE:
  * The universal principle of interdisciplinary contempt.
  * The Dilbert Pointy Haired Boss Principle:  everything I don't understand is simple.
  * Intellectual worth is evaluated on a single dimension:  from math to BS.
  * Not all statistical models are just about prediction.
  * Border defense:  Is that *really* CS?
  * Necessity to argue for practical application of each result.

### Who's Gets a Patch Accepted First?

* Do volunteers have to try more than employees to have a patcha ccepted?
* Do volunteers have to wait much more than employees to have a patch processed?
* Do volunteers follow contributing best practices?
* Volunteers face 26x more rejections than employees.
* Volunteers have to wait on average 11 days to have a patch processed, as opposed to three days for employees.
* Apparently nobody follows contributing best practices.

### A Case Study of Distances in a Large Co-Located Software Development Organisation

* Trying to ellicit requirements, figure out implementation, and do adequate testing turns out to be one long big game of telephone---something always gets miscommunicated along the way.
* Information traverses *distances* to achieve software development tasks.
* Practices decrease (or bridge) distances.
* Distances:
  * Interpersonal:  geographical, organisational, psychological, cognitive, temporal.
  * Artifacts:  semantic, adherence, navigational.
* Challenges increase with growing company/team size.
* Interactive posters for data gathering.

### Code Review for New Developers:  Is It Different?

* Newcomers' changes are less likely to be merged.

### Discussion

#### How do you get people to accept best practices?

* Just convince them it's useful for them, rather than the company.
* Reading up on best practices isn't producing code, therefore developers feel that work is inefficient.  Laziness is a big driver for behavior.
* Context matters, and whatever policies are accepted in the realm of best practices should be viewed as not set in stone.  You should be able to adapt practices to new information/environment.

#### How can we get the rest of ICSE to view CHASE as its core instead of periphery?

* Can we draw more people in from disciplines outside CS?
* Perhaps we should go to other conferences.
* Can we include some of this human aspects stuff into SE university programs. 
* Ex. from Brazil, they work human aspects topics into group projects with real clients throughout the course without directly teaching any human aspects stuff.

#### Note

* ICSE 2019 is in Montreal

## Wednesday, May 30

### 10+ Years of Teaching Software Engineering with iTrust:  the Good, the Bad and the Ugly (SEET)

* http://tiny.cc/itrust18
* Students work in teams in 1-week sprints.
* An early and intense experience with teamwork.
* Onboarding project:  Introduce technology stack and tools in classroom and labs (3 weeks).
* Guided project:  Introduce rpocess, such as pull requests, coe review, design, and testing (4 weeks).
* Team project:  Practice complete module development with teama nd process ( 3 weeks).
* Make time for "ClassOps":
  * Provide automation for course infrastructore:  Maintain scripts for setting up team repos and jenkins servers.
  * Rooting out flaky tests.
  * Best-Used by Date.

### Toward Enhancing the Training of Software Engineering Students and Professionals with Active Video Watching

* Teaching (transferable) soft skills is rather challenging.
  * Taught in (group) project courses, workshops.
  * Require feedback/coaching.
  * ==> video based training
* Active video watching:
  * watching + doing
  * engage with topic
  * deeper knowledge
* Environment:  AVW-Space
  * 4 tutorial videos (< 8 minutes each)
  * 4 example videos (< 8 minutes each)
* Step 1:  watch + comment
* Step 2:  review & rate others' comments
* It'd be good to get an idea of students' conceptual knowledge before and after a course.

### Developing an Optimizing Compiler for the GameBoy as a SE Project



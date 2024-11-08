# Rotating roles

**Struggling with team engagement and knowledge sharing?** Our rotating roles
system ensures that everyone on the team gets a chance to shine and learn
something new while taking care of daily tasks. These can be:

* handling releases or deployments
* running meetings
* grooming backlog
* keeping production service alive
* interacting with other teams, users and community

These should be a responsibility of the whole team, not just a single person.
With rotating roles, you can have an engaged team that takes turns in the daily
operations and is not disrupted when a key member leaves for a vacation.

This repository is an evolution of the rotating roles that we started in the
Packit team. You can see it in action [here](https://github.com/packit/agile)
and check role assignments in the [repository's
issues](https://github.com/packit/agile/issues).

After the technique proved successful, we followed with a series of blog posts:
1. 📄 [How to run an open-source service?](https://medium.com/@laura.barcziova/how-to-run-an-open-source-service-fb3303240e69)
2. 📄 [Inception of rotating roles](https://medium.com/@laura.barcziova/inception-of-rotating-roles-9caf971b3096)
3. 📄 [Share team responsibilities efficiently](https://medium.com/@laura.barcziova/share-team-responsibilities-efficiently-9a202aad7bd0)
4. 📄 [Role rotation tutorial](https://medium.com/@laura.barcziova/role-rotation-tutorial-957ed3545ef2)

And we also did a presentation:
- 📽️ [A journey of iteration and role rotation for better collaboration - DevConf.CZ 2024](https://www.youtube.com/watch?v=y1t7Wd31bL8)


## Common team roles
We have interviewed several colleagues of ours from Red Hat. The conclusion we
reached was there are multiple common roles that apply in many teams. We will
define them here so you can easily reuse the roles in your team. They don’t
apply everywhere and to everyone —  you are welcome to be inspired and create a
role that will fit your team.

## 🗓️Meeting lead

<img src="/img/meeting-lead.jpg" alt="A woman in charge of a meeting" style="max-width: 100%;" width="256">

Having a productive meeting that sticks to agenda, has notes, and a clear
outcome, has a tremendeous impact on everyone. With one responsible meeting
lead, you can have consistently an effective and productive conversation.

<details>
<summary><b>More about this role</b></summary>

### Responsible for
* Moderate agreed-upon team meetings
* Make sure people stay on topic
* Follow meeting agenda - address all points
* Write down action items and make sure the they are assigned
* Make meeting notes or assign someone on the call to write them down

### Why have this role?
* Meetings need moderators, otherwise they succumb to chaos
* Well run meeting is the difference between a complete waste of time and
  effectively coordinating in a group of people

### What can people learn?
* Not everyone likes the attention, so this can be a big step outside of
  comfort zone for many.
* It can be tiring to be in charge of everything all the time. Managers and
  leads can relate. Team members may suddenly feel more empathy and compassion
  once they realize that leading a meeting requires significant effort.

</details>

## 🏃 Agile lead

<img src="/img/agile-lead.jpg" alt="A team working on a problem together" style="max-width: 100%;" width="256">

As we participate in our agile methodology technique, be it scrum, kanban, or
anything else, we should have someone to be in charge. This role can be very
similar to the Meeting lead. We are keeping it separate here so we can clearly
distinguish between agile development methodology and just running meetings.

<details>
<summary><b>More about this role</b></summary>

### Responsible for
* The team sticks to all the agile ceremonies as they are defined.
* Coordinate with the meeting lead or be one.
* Make sure everyone has the capacity to work on their tasks.
* Assist people who are struggling in their assignments.
* Volunteer if possible for i.e. research, testing, or reaching out to
  different teams if needed.
* Celebrate success with the team.

### Why have this role?
* It could become chaotic without an agile lead.
* Every team is different and some can benefit a lot from getting the guidance.

### What can people learn?
* The responsibility to be in charge of the team's current agile iteration
  (such as scrum sprint, or a kanban cycle).
* It is an important experience for junior members of the team to be the lead.

</details>

## 🎙️Community shepherd

<img src="/img/shepherd.jpg" alt="Shepherd herding sheep in the mountains" style="max-width: 100%;" width="256">

Building community can take a lot of time and energy. It's something we are
often not taught at a school. When users can directly interact with project's
developers, it allows them to quickly address issues and start a lasting
professional relationship.

This role can be paired with the watcher of alerts and monitoring.

<details>
<summary><b>More about this role</b></summary>

### Responsible for
* Pay attention to questions and comments from your community in your chat
rooms, issue trackers, mailing lists, social media.
* Bring user's pain points back to the team and make sure they are triaged and prioritized.
* Suggest improvements based on the feedback.
* Lead community meetings.

### Why have this role?
* Your users will stay, when you listen to them.
* Close relationship between project members and users or customers can be a key to success.

### What can people learn?
* See how people use your team's solutions.
* Improve social skills and step out of the comfort zone.
* Expand your professional network and become more visible.

</details>

## 🔭 Chief reviewer

<img src="/img/reviewer.jpg" alt="Inspector doing a review" style="max-width: 100%;" width="256">

Reviews are a pillar of a successful project. They make sure we are not making
obvious mistakes and can be an effective learning tool for all parties. Make
sure that your team is clear who is responsible for driving a proposal towards
the end (i.e. merging a pull request): if it's the author, maintainer, manager,
or reviewer. If you are struggling with reviews, or even the design process,
your team may benefit from [Woody Zuill's Mob
Programming](https://woodyzuill.com/2024/02/software-teaming-mob-programming/).

<details>
<summary><b>More about this role</b></summary>

### Responsible for
* Provide reviews in project’s git repositories, design documents, email drafts
  or external communication before it’s sent out.
* If a proposal is unclear, don’t be afraid to set up a 1:1 time with the
  author of the pull request or a document to be on the same page.
* Try the proposed solution in practice so you can provide hands-on feedback
before it's released.

### Why have this role?
* Reviews can be an unpopular activity. Good review is really hard, takes a lot
  of time and requires empathy so that none of the sides get offended. It's an
  important skill we all should train.
* Good review culture in a project helps you build amazing solutions.
* Collaboration in teams without reviews leads to silos - knowledge and
  expertise will be accumulated in people who make solutions.

### What can people learn?
* Be amazing reviewers. This is immensely important to junior team members.
* Become better coders, analysts, researchers.
* Better knowledge about the code base to be able to review the changes.

</details>

## 🪛 Watching alerts, metrics, CI test runs

<img src="/img/monitoring.jpeg" alt="Monitoring the service" style="max-width: 100%;" width="256">

Keeping an eye on alerts, metrics, and CI test runs is crucial for maintaining system stability and 
catching issues early. This role ensures the health of services, 
preventing small problems from escalating into major incidents.

<details>
<summary><b>More about this role</b></summary>

### Responsible for
* Monitor system alerts and respond to any critical issues that arise.
* Keep track of key metrics (e.g. load, response times) to ensure systems are functioning 
within acceptable limits.
* Regularly check the results of CI test runs to catch external outages.
* Investigate and communicate the cause of any alerts or failing CI to the team.
* Document recurring issues and propose improvements to prevent future problems. 
* Ensure that any necessary escalations are communicated to the users (e.g. via status page).

### Why have this role?
* Without active monitoring, issues can go unnoticed until they become critical, impacting service 
uptime and user experience.
* Proactive monitoring and addressing issues early helps service health and prevents disruptions.

### What can people learn?
* Gain experience with monitoring tools and CI. 
* Learn how to troubleshoot alerts and CI failures. 
* Build problem-solving and critical-thinking skills.

</details>

## 🚀 Release & Deployment 

<img src="/img/release.jpeg" alt="Person in charge of releases and deployments" style="max-width: 100%;" width="256">

Managing smooth deployments and releases is critical for the success of any service. 
By ensuring the process is coordinated and thoroughly checked, you prevent issues
in production and maintain service reliability.

<details>
<summary><b>More about this role</b></summary>

### Responsible for
* Coordinate with the team to confirm whether deploying new changes is safe.
* Follow established instructions to carry out the new deployment.
* Capture shortcomings in any of the steps.
* Monitoring the outcome for any new issues.
* If your product ships as packages, manage the release process.
* Communicate release notes and any deployment impacts to users.
* Propose improvements to the release and deployment process.

### Why have this role?
* Deployments and releases can introduce risks. Without a structured approach, issues may slip into production.
* Having one person responsible ensures clear accountability and coordination.
* This role prevents disruption by ensuring deployments are carefully planned and executed.

### What can people learn?
* Gain a deeper understanding of the deployment process.
* Experience the challenge of handling releases under pressure, 
building problem-solving and decision-making skills.

</details>

# Thank you to the interviewees

We couldn't compile this database of roles without the interviews. Thank you
to: Michal Srb ([@msrb](https://github.com/msrb)), Neil Smith, Martin Pitt
([@martinpitt](https://github.com/martinpitt)), Petr Splichal
([@psss](https://github.com/psss)), Miro Vadkerti
([@thrix](https://github.com/thrix)), Martin Krizek
([@mkrizek](https://github.com/mkrizek)).

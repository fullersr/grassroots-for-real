

Working Title: **This is What Grassroots Looks Like** 

subtitle: **catchy subtitle**

## Table of Contents
1.  [Introduction](#introduction)
1.  [What's keeping us down](#failures_of_top_down)
1.  [The unrealized power of the grassroots network](#grassroots_network)
    1.  [The importance of the home group](#home_group)
    1.  [Organizations must collaborate](#org_collaboration)
    1.  [Use the consortium model to support big-ticket efforts](#consortium_model)
    1.  [It ultimately comes down to the individual](#individual)
1.  [Setting up the scaffolding: collaborate, borrow, and build](#proposal)
    1.  [Support for the home group](#org_support)
    1.  [Support for the individual](#individua_support)
1.  [Architectural Considerations](#architecture)
1.  [Appendix](#appendix)

------

## Introduction <a name = "introduction" />
Events over the course of the last decade and most dramatically over the last 6 months have shown just how vulnerable our democratic institutions have become. Principles we thought reliable are shifting under our feet and melting away like polar ice. Institutions we relied on to support economic stability, education, workers' rights, and environmental protection are being undermined. In short, national and often state governments are tending to work against the interests of the people they are supposed to represent, leaving us to feel isolated and/or under siege. Things seem out of whack.

 Right now people are energized in resistance. They want to do something to promote their vision of a just society. The greatest energy is emerging in the grass roots structures.
  
  It has become clear that neither of the two parties is capable of nurturing this kind of energy. In fact, they have fairly often proven themselves more of a hindrance

And while the issue-focused national and state efforts such as ACLU and Planned Parenthood are important allies, they are not by themselves sufficient. The issues demanding engagement are too varied for any single group. More importantly they do not provide the necessary forum to organize and coordinate local responses. They cannot replace the need for effective grass roots organizing.

Many are turning to volunteer groups such as those founded on the Indivisible Guide, and those inspired by Michael Moore's 5 things. These new efforts continue the pattern of grassroots activism modeled by Black Lives Matter among others. But these most recent efforts lack much coordination and coherence.  Energy is dissipated by bad scheduling and contradictory messaging. How can they be sustainable unless they can effectively channel their energy.

What we need is a networked model for grassroots organizing.

Individual activists benefit from working within a home group, a group that is small enough to truly reflect the interests of its members and to nurture leadership. It serves as a forum for each member to engage. It must provide members with the ability to track events, to initiate actions and to contribute to ongoing efforts. It must be able to network with other allied groups to coordinate messaging and events and to provide a larger talent pool.

The individual activist must be able to network within and beyond the home group, to engage with other groups according to specific interests: to be able aggregate events and news feed from those organizations and to track and participate in upcoming campaigns.

When it comes to working with the larger, more expensive efforts, the networked home group could play a role in funding them so that they need not compete with grass roots but to draw from that energy.

This document argues that volunteer-based, well networked grassroots organizations are our best chance for correcting the problems we face. It presents the capabilities we think are essential for success. It then goes on to sketch out the architecture, entity model and APIs to promote interoperability and optimal user control.

In addition for arguing the case for well-networked grassroots groups, we explore capabilities needed and possible IT approaches to facilitating its growth.

## What's keeping us down? <a name = "failures_of_top_down" />
Progressive organizations have not kept pace with cultural and structural changes in our country.

The shift to online interaction has loosened civic bonds.
*   Trade unions have been weakened and are often not sufficiently representative
*   Religious institutions, taken as a whole, do not offer a coherent moral narrative
*   The traditional two parties will probably continue to dominate our electoral process, but they have largely failed to produce candidates who truly represent the interests of the people. In fact, the two party system consistently tends to impede rather than foster progressive change
*   Individuals no longer have a common fund of reliable, useful information. Important information is too often lost amidst the spinning and pontificating.

This often leaves individuals or stand-alone groups working for democratic change fighting in isolation with scarce resources against fabulously well-endowed superPACs and national parties. At the risk of oversimplification, the grass roots is in a battle with the oligarchy for the soul of the country.

The internet is less open these days, but it still offers a solution, and grass roots groups have yet to make good use of it.

Despite all the talk of netroots, modern web capabilities have left grassroots groups stranded. Resistance movements are working with Facebook, Twitter, Google groups, small sites and independently maintained email lists. These are useful but insufficient. They lack any real infrastructure for inter-organizational collaboration, and facilities available for the individual to assemble resources are themselves scattered among many calendars, many URLs, and many messages in the inbox. The signal-to-noise ratio is quite low.

The world has moved on to dynamic, user-centered, mobile-friendly apps, and  The work to develop these is often beyond the scope of groups depending on volunteer support. This leaves grass roots groups at a disadvantage. They must either pony up for hosted capabilities or rely on donated IT time, the latter tending to lead to one-off, poorly maintained solutions.

Then, there is the issue of big data analytics, which the oligarchy has effectively deployed for their own, often unsavory, purposes.  It would be wonderful if grass roots groups could develop this capability for more democratic purposes. Unfortunately, It is totally out of reach of small, mostly volunteer, un-networked groups.

Finally, we are still suffering under the fallacy of scarce resources. It is wrong for progressive groups to compete for email addresses and dollars. Doing so undermines grass roots activism. Rather than competing, groups should be offering mutual support. Consider this knock-knock story:

*   Tuesday: Knock, knock. _Do you care about clean lakes? Would you sign this petition to address pesticide runoff. Could you please donate $20, $50, $80 to save the Lakes?_
*   Wednesday: Knock, knock: _Do you care about the honeybees? Would you sign this petition to control the use of these chemicals. Could you please donate $20, $50, $80 to save the bees?_
*   Thursday: Knock, knock: _Help us fight gerrymandering. Would you sign this petition for fair redistricting. Could you please donate $20, $50, $80 to get the message out there?_

Many people care about all of these things along with a host of others but have little to give and want to plan their gifts as well as their engagements carefully.

This way of doing business is adequate at best only as a last resort and when the population is passive and unorganized. But in the current environment, people are desperate to organize, desperate to engage more fully, desperate to have their energy (including money) put to effective use. How can signing those petitions and being deluged with more hectoring email help us take meaningful action?

 What is worse, some national groups will not share information with their state and local chapters. If a person joins a national progressive group, she would logically assume she would be tied in with the local chapter. But, surprisingly, that may not be the case. At least one national group will not release its membership roles to the local, even on an opt-in basis.

 This is a failed model.

## The unrealized power of the grassroots network <a name = "grassroots_network" />
People have risen in protest many times over the last decade in response to attacks on people's safety and well-being. the Black Lives Matter movements and The Wisconsin resistance movements of 2011 are two examples.  Many have proven effective for at least a while, some are still active, all have left a legacy of possibilities.

Right now, the call to resistance is massive. People are mobilized.  What we need is to organize by building on what we've learned so far. Networked grassroots organizing is the best approach.

#### The importance of the "home" group <a name = "home_group" />
A home group is crucial to a well-networked grassroots movement. It should be small enough to provide a sense of community and belonging, and it should be large enough to sustain itself. It should offer participants opportunities to engage according to interests, skills, and availability, and it should nurture leadership.

Effective resistance requires action at local, district, and state levels as well as at the national level. For that to work, the home group must operate at the local or at least regional level. Resistance also requires action on a fairly large number of issues. An individual activist should ideally be able to find support for issues she cares most about through the networked home group. rather than having to spread herself out across a multitude of non-networked groups.

#### The organizations must collaborate <a name = "org_collaboration" />
The power of the internet draws from its openness and flexibility. It is resilient, adaptive, and capable of operating at great scale. That is exactly the paradigm we are seeking in grassroots organizing.

What we are talking about here is a federated network, a different structure from that of the national group and local affiliates (sometimes poorly integrated, as noted above). Thinking globally and acting locally is possible. Federation gives us the power of numbers hitherto enjoyed only by the national groups but it keeps the focus with the home group.

  We have argued that it is an essential base for organizing, but without federation, i.e., without being networked with other similar groups, it tends to be ineffective. Even in a small city such as Madison, we have seen any number of new grassroots groups spring up. Some following the Indivisible Guide, others spun up from the ACLU People Power initiative, and some from other sources. That they emerged so rapidly is wonderful, that they have not yet started collaborating effectively is a growing problem. Marches, town halls, letter-writing campaigns could be much more effective with better coordination.

Networking the home groups involves identifying allied groups. Perhaps the analog here is "friending". Alliances can be ad hoc based on issues or campaigns or they can be more longstanding. Through these alliances, a network can be built. Allies will need a forum for coordinating actions and sharing resources. They will need a shared calendar. They will also need to share announcements, blog posts, etc. At the same time the network of federated groups should uphold the privacy and consent of its members.

Supporting these capabilities may sound challenging, but what we are talking about here is not that much different from what has already been achieved in collaborative efforts in many other areas such as research, open software development, and open learning systems.

#### Use the consortium model to support big-ticket efforts <a name = "consortium_model" />
Though we promote the value of the networked home group, we understand the importance of the non-profit organizations that serve progressive interests. We need media and lobbying efforts; we need constitutional lawyers and watchdog groups; we need health and counseling services in our communities. There is an important role for such organizations, and their budgets can be large.

Where donations are tax deductible there is an incentive for them to appeal directly to the individual.

Nonetheless we believe that an ecosystem, in which activism is based on networked home groups can coordinate well with these non-profits. Perhaps the home group and allies could use polling and forum methods to help individual members prioritize their resources. Perhaps also where individuals perceive unneeded competition, redundancies and inefficiencies among the non profits they can use their home group and affiliates to lobby for improvement making them more responsive.

```
 need to develop the above better
```

#### It ultimately comes down to the individual <a name = "individual" />
The individual activist is the one to determine the nature of her engagement: on what issues to focus, how much time to expend, in what capacity. As we have argued, the home group is the best way to support her, but she must be able on her own to tailor her activism according to her needs.

 She may want to engage in specific projects through the home group and filter out others. She may want to start a new project and recruit participants. She may want to include in her kit some tools and resources offered outside of her home group.

 In all cases she should be getting just the information she wants and needs in order to engage effectively.

## Setting up the scaffolding: collaborate, borrow, and build <a name = "proposal" />
We propose a collaboration of IT activists to identify and build out the capabilities needed to support a vibrant grassroots ecosystem. Some of these capabilities exist in other contexts, so often it will be a matter of re-purposing them rather than building them from scratch.


#### Support for the home group <a name = "org_support" />
The home group needs to perform at least the following tasks:
*   Create content
*   Create events
*   Manage campaigns/projects
*   Track members
*   Manage roles and permissions
*   Provide forums for users
*   Identify and manage issues
*   Establish and manage alliances with other groups
*   Send messages
*   Publish and subscribe content and events related to issues.

Recent work in learning technology, especially for secondary and post-secondary education might be one such area from which to draw. The notions of empowerment, collaboration, projects (substitute campaigns) and adaptive behavior are already the focus in this area. Efforts in this area to provide a set of standards-based interoperable tools and resources lend themselves well to our purposes.  They allow the learner (substitute activist) and the instructor (substitute issue-focused sub-group) to assemble what is needed to suit their purposes.  So we should look here for material and inspiration.

Open source CMS applications such as Drupal and CRM applications such as CiviCRM might be another useful area to explore. They are optimized to provide content and event management capabilities out of the box. But they will need to be modified to support inter-group networking and to give the individual activist more latitude to assemble her own dashboard and calendar.

#### Support for the individual <a name = "individual_support" />
The individual activist needs to perform at least these tasks:
*   Join and withdraw from a group
*   Create and update profile information (including privacy requirements)
*   Participate in the activities of the home group
*   Establish and manage connections outside the home group
*   Maintain a calendar filtered on issues and other criteria that she sets

 A user should be able to access her resources on mobile as well as laptop/desktop devices.

Learning technology efforts may provide a starting point here too. One branch of this work has focused on the personal learning environment (PLE), which explores the methods for the learner (or in this case activist) to assemble her own tools and resources as needed.

We should also look at existing portal solutions that provide the user with an informative dashboard that can be tailored to her needs. Apereo uPortal is one such


## Architectural Considerations <a name = "architecture" />

```
 More work to do here
```

##### Identity and access management middleware and/or APIs

##### IMSGlobal LTI v2 or other similar support for linking resources

##### Network graph capabilities to identify larger alliances

----
.

## Appendix <a name = "appendix" />

#### Technical precedents/Optional starting points.

Current efforts to support grassroots
*   https://github.com/november9/wecansavedemocracy
*   Civi.workks https://civ.works/


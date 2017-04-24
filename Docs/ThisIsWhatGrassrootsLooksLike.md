

Working Title: **This is What Grassroots Looks Like**

subtitle: **catchy subtitle**

## Table of Contents
1.  [Introduction](#introduction)
1.  [What's keeping us down](#failures_of_top_down)
1.  [The unrealized power of the grassroots network](#grassroots_network)
1.  [Setting up the scaffolding: collaborate, borrow, and build](#proposal)
    1.  [Support for the home group](#org_support)
    1.  [Support for the individual](#individua_support)
1.  [Architectural Considerations](#architecture)
1.  [Appendix](#appendix)

------

## Introduction <a name = "introduction" />
Events over the course of the last decade and most dramatically over the last 6 months have shown just how vulnerable our democratic institutions have become. Principles we thought reliable are shifting under our feet and melting away like polar ice. Institutions we relied on to support economic stability, education, workers' rights, and environmental protection are being undermined. In short, national and often state governments are tending to work against the interests of the people they are supposed to represent leaving us to feel isolated and/or under siege. Things seem out of whack.

 Right now people are energized in resistance. They want to do something to promote their vision of a just society. The greatest energy is emerging in the grass roots structures.

  It has become clear that neither of the two parties is capable of nurturing this kind of energy. In fact, they have fairly often proven themselves more of a hindrance. And while the issue-focused national and state efforts such as ACLU and Planned Parenthood are important allies, they are not by themselves sufficient. The issues demanding engagement are too varied for any single group. More importantly they do not provide the necessary forum to organize and coordinate local responses. They cannot replace the need for effective grass roots organizing.

Many are turning to volunteer groups such as those founded on the Indivisible Guide. These new efforts continue the pattern of grassroots activism modeled by Black Lives Matter among others. But these most recent efforts lack sufficient coordination and coherence.  Energy is dissipated by bad scheduling and contradictory messaging. How can they be sustainable unless they can effectively channel their energy.

What we need is a networked model for grassroots organizing.

Individual activists benefit from working within a home group, a group that is small enough to reflect the interests of its members and to nurture leadership. The home group serves as a forum for each member to engage. It must provide members with the ability to track events, to initiate actions and to contribute to ongoing efforts. And, very importantly, It must be able to network with other allied groups to coordinate messaging and events and to provide a larger talent pool.

The individual activist must be able to engage within and beyond the home group according to specific interests: to launch campaigns and participate in events from within the home groups and to track campaigns and events taking place elsewhere.

When it comes to working with the larger, more expensive efforts, the networked home group could play a role in funding them so that they need not compete with each other but draw from the combined energy of the grassroots groups.

This document argues that volunteer-based, well networked grassroots groups are our best chance for correcting the problems we face. It presents the capabilities we think are essential for success. It  goes on to sketch out the architecture, entity model and APIs to promote interoperability and optimal user control. And it then it explores possible IT approaches to facilitate the growth of a robust grassroots ecosystem.

## What's keeping us down? <a name = "failures_of_top_down" />
Progressive organizations, at least in the USA, have not kept pace with cultural and structural changes. The reasons should be well understood by now.

The changes to the economy and to common forms of social interaction have loosened civic bonds.
*   Trade unions have been weakened and are often not sufficiently representative
*   Religious institutions, taken as a whole, do not offer a coherent moral narrative
*   The traditional two parties will probably continue to dominate our electoral process, but they have largely failed to produce candidates who truly represent the interests of the people. In fact, the two party system consistently tends to impede rather than foster progressive change
*   Individuals no longer have a common fund of reliable, useful information. Important information is too often lost amidst the spinning and pontificating.

So, individuals or stand-alone groups working for democratic change fight in isolation with scarce resources against fabulously well-endowed superPACs and national parties. At the risk of oversimplification, the grass roots is in a battle with the oligarchy for the soul of the country.

Despite all the talk about the "netroots", modern web capabilities have left grassroots groups stranded. The internet is less open these days, but it still offers a solution, and grass roots groups have yet to make good use of it. Resistance movements are working with Facebook, Twitter, Google groups, small sites and independently maintained email lists. These are useful but insufficient. They lack any real infrastructure for inter-organizational collaboration. Facilities available for the individual to assemble resources are themselves scattered among many calendars, many URLs, and many messages in the inbox.

The world has moved on to dynamic, user-centered, mobile-friendly apps. But the work to develop these is often beyond the scope of groups depending on volunteer support, which leaves grass roots groups at a disadvantage. They must either pony up for hosted capabilities which can be too expensive or rely on donated IT time which often leads to one-off, poorly maintained solutions.

Then there is the issue of big data analytics, which the oligarchy has effectively deployed for their own, often unsavory uses.  It would be wonderful if grass roots groups could develop this capability for more democratic goals. Unfortunately, that is totally out of reach of small, mostly volunteer, non-networked groups.

Finally, progressive efforts often compromise their own usefulness by competing with each other for the attention, email address, and dollars of the activist.  Doing so undermines grass roots activism. Consider this knock-knock story:

*   Tuesday: Knock, knock. _Do you care about clean lakes? Would you sign this petition to address pesticide runoff. Could you please donate $20, $50, $80 to save the Lakes?_
*   Wednesday: Knock, knock: _Do you care about the honeybees? Would you sign this petition to control the use of these chemicals. Could you please donate $20, $50, $80 to save the bees?_
*   Thursday: Knock, knock: _Help us fight gerrymandering. Would you sign this petition for fair redistricting. Could you please donate $20, $50, $80 to get the message out there?_

Many people care about all of these things along with a host of others but have little to give and want to plan their gifts as well as their engagements carefully.

Competing often results in a refusal to share resources. Some national groups will not even share with their state and local chapters. If a person joins a national progressive group, she would logically assume she would be tied in (either by default or by opt-in) with the local chapter. But, surprisingly, that may not be the case.

The above practices may have made more sense when the population was passive and unorganized. But things are different now. People are desperate to organize, desperate to engage more fully, desperate to have their energy (including money) put to effective use.  Rather than competing, groups should be offering mutual support.

## The unrealized power of the grassroots network <a name = "grassroots_network" />
People have risen up in protest many times over the last decade in response to attacks on our safety and well-being. the Black Lives Matter movements and The 2011 Wisconsin resistance movement are two examples.  Many have proven effective for at least a while, some are still active, all have left a legacy of possibilities.

Right now, the call to resistance is massive. People are mobilized.  What we need is to organize by building on what other activists have done well and on what other collaborative efforts have shown to be possible. Additionally, we need to reclaim the power of the internet. Networking grassroots entities is the key to successful progressive change.

#### The importance of the "home" group
The home group is crucial to a well-networked grassroots movement. It should be small enough to provide a sense of community and belonging and large enough to be sustainable. It should be a reservoir of talent and energy to support the activist goals of its members and offer them opportunities to engage according to interests, skills, and availability.

It shouuld accommodate initiatives on multiple issues accoring to the interests and energy of its members. Referring to our earlier example, a home group might coneeivably take on redistricting AND clean water AND honeybees. Or it might defer one or more of those if need be to concentrate on more urgent matters. It should support projects that relate directly to the goals of the group and those of the project teams.

In short, it should feel to the individual activist that participation will contribute to meaningful results.

#### The organizations must collaborate

The home group must be networked, that is, it must be able to ally with other groups and share events and content.  The old addage "Think globally, act locally" applies here. Effective resistance must address issues at local, district, and state levels as well as at the national level. Networking the home groups is the only way to do this.

The power of the internet draws from its openness and flexibility. It is resilient, adaptive, and capable of operating at great scale. That is exactly the paradigm we are seeking in grassroots organizing. Like the internet itself, the network of home groups is a federation of independent entities.

Without being networked, the home group struggles and the membership becomes demoralized. Even in a small city such as Madison, we have seen any number of new grassroots groups spring up. Some following the Indivisible Guide, others spun up from the ACLU People Power initiative, and some from other sources. That they emerged so rapidly is wonderful, that they have not yet started collaborating effectively is a growing problem. Marches, town halls, letter-writing campaigns could be much more effective with better coordination.

Home groups become part of the network by building alliances, either ad hoc or long-standing.  As they do so, their combined force grows. It allows groups to collaborate: to share talent, coordinate events, work together on campaigns and more. The possibilities are numerous.  Obviously, this is a very different model from that of the national group and local affiliates (sometimes poorly integrated, as noted above).

One can imagine differing patterns developing for extended alliance. There are direct relationships whereby each group affilates with one or more others.  Those are useful for specific, usually local actions. To achieve broader reach, though, groups might build alliances by inference as is done with social netowrks. Larger networks can be inferred from the direct alliances of each group and from the issues it tackles and the kinds of skills it has.

Allied groups will need forums for coordinating actions and sharing resources. They will need a shared calendar. They will also need to share announcements, blog posts, etc. At the same time the network of federated groups should uphold the privacy and consent of its members.

Supporting these capabilities may sound challenging, but what we are talking about here is not that different from what has already been achieved in collaborative efforts in many other areas such as research, open software development, and open learning systems.

#### Use the consortium model to support big-ticket efforts
While this document stresses the primacy of the netowrked home group, it recognizes the importance of non-profit organizations that serve progressive interests. We need media and lobbying efforts; we need constitutional lawyers and watchdog groups; we need health and counseling services in our communities. There is an important role for such organizations, and their budgets can be large.

Where donations are tax deductible there is an incentive for them to appeal directly to the individual. Nonetheless we believe that an ecosystem that grounds activism in networked home groups can foster a more efficient approach for funding these non-profits. Perhaps the home group and allies could use polling and forum methods to help individual members prioritize their resources. Perhaps also where individuals perceive unneeded competition, redundancies and inefficiencies among the non profits they can use their home group and affiliates to lobby for improved, more responsive behavior.

```
 need to develop the above better
```

#### It ultimately comes down to the individual
The individual activist is the one to determine the nature of her engagement: on what issues to focus, how much time to expend, and in what capacity. As we have argued, the home group is the best way to support her, but she must be able to tailor her activism according to her needs.

 She may want to engage in specific projects through the home group and filter out others. She may want to start a new project and recruit participants. She may want to include in her kit some tools and resources offered outside of her home group.

 In all cases she should be getting just the information she wants and needs in order to engage effectively.

## Setting up the scaffolding: collaborate, borrow, and build <a name = "proposal" />
We propose a collaboration of IT activists to identify and build out the capabilities needed to support a vibrant grassroots ecosystem. Some of these capabilities exist in other contexts. Often it will be a matter of re-purposing them rather than building them from scratch.


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

##### Further reading
1.  http://www.resilience.org/stories/2017-04-21/from-platform-to-open-cooperativism/

#### Technical precedents/Optional starting points.

Current efforts to support grassroots
*   https://github.com/november9/wecansavedemocracy
*   Civi.workks https://civ.works/


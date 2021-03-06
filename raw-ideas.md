# FromTeal-whitepaper Raw Ideas

```purpose/what we're trying to achieve```
We want fromTeal to generate beauty & specifically Art, beautiful Art, in the world.

The way we want to that is this. 
There are many artists in the world, all persuing different types of art, for example, it may be some traditional art form, or it might be figuring out some solution to a problem that many people have, or building a new technology, 
or any other beautiful new thing that people create, that is so original, novel & beaufitful that people appreciate it & say: 
wow, this is something I never saw before, it's so simple & powerful, that it's just beautiful.

There are many people who do that, but there's even more beauty created when people collaborate.
It is just so that 1+1>2 many times. It may be when people drive each other to do something new, 
or that doing something together blends the different skills into something special or new,
or it just might be that someone had an idea that's exactly the missing piece for something someone else wanted to do,
so combining the ideas gives them something much bigger & more special.

So, there are many examples of where people created art in a group, creating something much bigger than what each one of them would have been able to create individually.

Given that, why aren't there more artist groups? And to be clear, we're speaking of an extended concept of art, it could be the Velvet Underground, or XEROX PARC, or Watson & Crick & Franklin.

So how is fromTeal going to help generate more beautiful art, & specifically by helping people create art groups, in which the sum is much bigger than it's parts?

```solution layers```
fromTeal tries to do that using 3 layers:
1. **Maps** mapping purposes/problems to people/teams
2. **Digital world** for teams to collaborate & work together in
3. **Smart Contracts** infrastructure facilitating the teams' governance & finance


```description of the solution```
We need to help people to discover each other, & we need people working on some specific problem or need, to discover others working on the same problem or need.
And either group together or cross-polinate each other (even when not in the same group, they can still contribute & influence each other).

How do you help one artist/engineer/researcher working on something, discover another artist working on the same thing? And connect them.



So, fromTeal tries to do this in this way:
It offers a digital world, containing 4 main entities:
1. **Purpose Neighborhood**: areas built around some purpose - purpose can be "create songs from poetry on the extreme difficulties of modern life", or it can be "discover a way to capture CO2 from the atmosphere". Purposes can be very diverse & variful.
2. **Category Street**: areas for sub-categories within a purpose, in which problem lots are created.
3. **Problem Lot**: areas of lands, created around some specific problem, need or goal, within some purpose & category, in which team buildings can be built.
4. **Team Building**: a building for teams forming to work together on some problem or need

Any fromTeal user, can create any of these entities - neighborhoods, streets, lots or buildings, but is subject to moderation by fromTeal moderators, who try to ensure that anything created complies with the rules & standards for keeping the map effective & accurate.

A person passionate about some purpose, or having a certain problem or need, or actually working on some type of art, research or technology, will create the relevant purpose neighborhood, category street, problem lot or team building, if any of these do not yet exist. If the neighborhood, street or lot already exist, the person can join them as member, indicating that she is passionate about that purpose or having the relevant problem or need. If a team building already exists for exactly the same work as the person is doing, she may ask to join the team, or alternatively start her own team building on the same problem lot.

Besides the team buildings on problem lots, users can also create team booths for external teams or organizations, also working on the same problem, who do not use fromTeal. The booth will contain references to the external team communication channels (website, twitter &c), so that fromTeal can automatically update the booth with publications from the external teams.

Based on this digital world composed of purpose neighborhoods, category streets, problem lots & team buildings/booths, fromTeal offers an organized map of the relationship between pruposes/problems & people/teams/organizations working on them. This map can help anyone passionate about a specific purpose, problem or need, to discover others who share the same passion or purpose have the same problem or need, & either learn from them or join them. Team buildings will have an indication whether they are looking for & accepting new members. 

Since all the teams on the same problem lot are all interested in solving the same problem, & generally driven by the same purpose, they have an incentive to help each other & share ideas & learnings. Team buildings are therefore open & transparent, to share with others their progress & ideas. This doesn't mean that there's no evolution of fittest & competition on resources (customers or team members) - teams want to succeed by being more fit in solving the problem - but they also cooperate & help each other, because they are driven by the same cause, & not just their self-interest.

The digital world is built on infrastructure that synchronizes with a blockchain intended to keep the state of the digital world in decentralized concensus, without the ability to temper with the data. Moderators still are a centralized decision making for now. Having the state of the digital world on-chain, & having the code open-source, means that it is possible for the community to fork the whole digital world in case of governance issues.

```Solution description: automatically managing the financial equity of teams```
The other major purpose of the infrastructure under the digital world, is to automatically manage the financial equity of teams, so that they can fairly split the value they create together. These teams, they are solving a problem, people in the lot reported that they have that problem. The team wants to work on it, & maybe make a living out of what they build, the value they created. So, it is possible for the team to sell what they worked on, to other people having the problem or need. If they sell what they created, who is the owner who gets all the money & pays salaries? In fromTeal, it's not who, it's the team itself. fromTeal provisions a smart contract for managing each team. That smart contract will basically own the team, so that there's no single person owning the team, all members are owners. The money from sales arrives to the smart contract, & the profits are split between the team members in a fair way, based on their contribution.

```How it works: automatically tracking level of contribution```
In order for this infrastructure to manage the teams equity, & keep track of each member contribution, the team buildings contain the tools & integrations that keeps track of tasks, meetings, customers, sales &c. So when team members use the tools & update the state of objects, fromTeal smart contracts are informed & can manage the equity & keep track of members contribution.

In particular, there are 7 levels of contribution, determined by the smart contract, which result in a monthly amount of equity tokens that are granted to team members. The calculation of the level of contribution of each member is based on 4 factors, measured per time-period (e.g., month):
* The number of delivered tasks
* The ranking of the tasks difficulty (based on a scale of years-of-experience required)
* The ranking of the tasks value by their recipients
* The number of attended team meetings/calls

The smart contract has a formula calculating the number for each member every month, & the number falls into 1 of the 7 levels of contribution, based on which the member will earn equity tokens.


```Solution description: helping with team governance```
Besides managing the equity & fair splitting of the value created by teams, the smart contract infrastructure also manages the overall governance of the team in a fair way. As the team are for creative people (artists, engineers, researches), it must not have any artificial hierarchy, where some members have more power over others & tell others what to do. This means though that there must be agreed ways to resolve conflicts & regulate decision making. In general, based on the Teal principles, every team member has the power to make decisions on everything that impacts them, as long as they ask other for advice, especially whoever is also impacted by the decision.

Teams in fromTeal are encouraged to remain small - up to 10 members. For example, a team building a solution to a problem, that already has customers paying for the solution, would normally be composed of 5-6 engineers/artists/proffessionals working on the solution, 2-3 people taking care of the customer happiness, & 1-2 people taking care of reaching out & selling to customers. If the team's revenue grows over a certain amount, that exceeds the capacity of work the team is capable of, they can perform cell-splitting operation, in which a team splitts into 2 teams, each having different product variant or cusromer segment. The 2 teams can then grow back to the original size. The smart contract will regulate the process & ensure fair splitting of budget to ensure the success of both teams. This process can continue multiple times, so the team essentially becomes an organization of federated teams. However, there's no central management of the organization. The smart contract will provide ways for the teams to decide on global decisions & proposals, but normal decisions are just made by teams getting other teams buy-in & helping each other.


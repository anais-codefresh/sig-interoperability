# CDF Interoperability SIG Meetings

[![HacmKD documents](https://hackmd.io/badge.svg)](https://hackmd.io/HuufSDMaTPyb3qxkyBKg3A?edit)

## Quick links

* [Logistics](#Logistics)
* [Meeting Recordings](https://www.youtube.com/playlist?list=PL2KXbZ9-EY9QxICOnONBFPn_cYfJ8BsaG)
* [Agenda and Notes](#Agenda-and-Notes)
    * [2021-01-21 Meeting](#January-21-2021)
    * [2021-01-07 Meeting](#January-7-2021)

## Logistics

* **Meeting notes on HackMD.io**: https://hackmd.io/@cdf-sig-interoperability/ry3TTB5DL
* **When**: First and third Thursdays at 16:00UTC (*See your timezone [here](https://time.is/1600_in_UTC)*).
* **Zoom Bridge**: https://zoom.us/j/827082528?pwd=RlN5OUZtVVBuZGZRY0NBRnZyZ0NJQT09
* **Zoom International dial-in numbers**: https://zoom.us/zoomconference
* **Meeting Recordings**: [CDF Youtube Channel SIG Interoperability Playlist](https://www.youtube.com/playlist?list=PL2KXbZ9-EY9QxICOnONBFPn_cYfJ8BsaG)
* **CDF Public Calendar**: [here](https://calendar.google.com/calendar/embed?src=linuxfoundation.org_mhf0kmgedn67ihni8r129avp24%40group.calendar.google.com&ctz=America%2FLos_Angeles)
* **Past Presentations in CDF Presentations Repository**: https://github.com/cdfoundation/presentations/tree/master/sig-interoperability
* **Presentation Schedule**: https://docs.google.com/document/d/1Owg_I52WEXzqF8g_lX6OTdwbHkH4Z2-7TBA7eCSVMqY/edit
* **2020 Meeting Minutes**: https://github.com/cdfoundation/sig-interoperability/blob/master/docs/meetings_2020.md

## Agenda and Notes

Meeting agenda and notes are kept on [HackMD.io](https://hackmd.io/@cdf-sig-interoperability/ry3TTB5DL) where everyone can add new topics to the agenda for upcoming meetings or take notes during the meetings. Please click edit button to edit the document.

If you are looking for 2020 minutes of meetings, please take a look at [Meetings 2020 document](https://github.com/cdfoundation/sig-interoperability/blob/master/docs/meetings_2020.md) in SIG Interoperability repository on GitHub.

### January 21, 2021

#### Participants
* Fatih Degirmenci, Ericsson Software Technology
* Andreas Grimmer, Dynatrace
* Mattias Linnér, Ericsson
* Kara de la Marck, CloudBees
* Christie Wilson, Google
* Tracy Miranda, CDF
* Emil Bäckmark, Ericsson
* Anthony O'Gorman, Fidelity Investments
* Oliver Nocon (SAP)
* Jeremy Stanley, OpenDev/Zuul
* Andrea Frittoli, IBM

#### Agenda and Notes
* Action Item Review, All
* Events in CI/CD becoming SIG, Workstream Members
    * EB: Draft charter for the SIG was presented to CDF TOC on January 19. Positive response received.
    * AG: Charter had priority and contribution to standardized metadata is in the backlog.
* Interoperability Whitepaper, Tracy Miranda
    * TM: Work is in progress by the creative team. References is empty and will be .
    * TM: Content will be massaged and visuals will be included.
    * TM: Additional feedback will be asked to the community members.
* cdCon Update, Tracy Miranda
    * TM: CFP is open. 
    * TM: Early bird submissions are open and 5 proposal will be selected and highlighted as Early Bird picks by the programming committee.
    * TM: Proposals are welcome.
    * TM: Hopin platform is integrated with the tool [Miro](https://miro.com) to collaboratively/interactively work on visual material.
* End User Council Update, Tracy Miranda
    * TM: End User Council has its [own repo](https://github.com/cdfoundation/end-user-council).
    * TM: End User Council published 2021 plan and the material is available in [End User Repo on GitHub](https://github.com/cdfoundation/end-user-council/blob/main/End%20User%20Council%20Plan%202021.pdf).
    * TM: There will be discussions relevant to Interoperability area and there will be discussions on the topic in End User Council.
* SIG Interoperability One Year Old, All
    * [Blog post](https://cd.foundation/blog/2021/01/19/cdf-sig-interoperability-2020-year-in-review/) celebrating this 
* [Continuous Delivery Definitions](https://docs.google.com/document/d/1IUSmgtw5eC2JwyfiX7IPK3twl3MSjWAsmCKmJ6Y5z-w/edit#), [CD timeline](https://github.com/cdfoundation/glossary/blob/main/timeline.md), Christie Wilson
    * CW: The discussion on definitions started in this group so I wanted to give an update to the group.
    * CW: The interoperability whitepaper had a section to describe CI and CD and there were lots of conversations on the topic.
    * CW: One thing I did was to get some progress was to create a timeline to see when/where these things were originated. Both Continues Deliver and Continuous Deployment appeared same year.
    * CW: First appearance of Continuous Delivery was in [Agile Manifesto](https://agilemanifesto.org/principles.html)
    * FD: What about related terms such as DevOps, DevSecOps, GitOps, Progressive Delivery? (https://github.com/cdfoundation/glossary/issues/7)
    * TM: Can help out with them.
    * CW: Jez Humble tries to explain the differences between and reasons for (e.g., business) Continuous Delivery vs Continuous Deployment. (https://continuousdelivery.com/2010/08/continuous-delivery-vs-continuous-deployment/)
    * KM & CW: This topic could feed into the work done in CDF Best Practices SIG.
    * TM: Everybody has a different view on Continuous Delivery and Continuous Deployment. If we say Continuous Delivery is much wider and what other things it compasses.
    * TM: What are the best practices for using SCM, deployment strategy, trunk based development, GitOps, advanced bots, ChatOps.
    * TM: Best Practices SIG started the work recently.
    * AO: [SIG Best Practices](https://github.com/cdfoundation/sig-best-practices) is a good idea an want to be involved in it.
* Ortelius Presentation/Demo, Tracy Ragan, Steve Taylor
    * Postponed
 
#### Action Items
* Ramin A to bring an example manifest from eBay for metadata topic - Fatih to remind
* Tracy R/Steve T to demo Ortelius (manifest/metadata/visibility focused), 21st January
* Events in CI/CD workstream to provide input to standardized metadata topic based on their discussions
* Tracy M to bring the whitepaper to the attention of CDF creative team
* ~~Tracy M to help with creation of a repo for standardized-metadata, https://github.com/cdfoundation/foundation/issues/262~~
    * Repo is ready: https://github.com/cdfoundation/standardized-metadata
* Steve to start the work on commit metadata
* Dave to start the work on artifact metadata
* ~~Emil to bring Eiffel example in new repo - https://github.com/cdfoundation/standardized-metadata/pull/3~~
* Steve/Tracy R to bring Ortelius example in new repo
* Tracy M to get SIG Interop in touch with Dina Graves Portman and invite her to one of the upcoming SIG meetings
* Kara and Fatih to populate references in whitepaper

#### Meeting Recording
* \<addme\>

### January 7, 2021

#### Participants
* Fatih Degirmenci, Ericsson Software Technology
* Andrea Frittoli, IBM
* Oliver Nocon, SAP
* Kara de la Marck, CloudBees
* Dave Sudia, UPchieve
* Jeremy Stanley, OpenDev/Zuul
* James Strachan, CloudBees

#### Agenda and Notes
* Action Item Review, All 
* Archival of 2020 Meeting Minutes, All
    * The minutes of past meetings available [here](https://github.com/cdfoundation/sig-interoperability/blob/master/docs/meetings_2020.md)
* Upcoming Events, All
    * [FOSDEM 2021](https://fosdem.org/2021/), 6-7 February 2021
        * [CI/CD Devroom schedule](https://fosdem.org/2021/schedule/track/continuous_integration_and_continuous_deployment/) published
        * CI/CD Devroom happens on February 7
        * 2 talks from SIG are accepted
            * [The Road to Interoperability in CI/CD](https://fosdem.org/2021/schedule/event/the_road_to_interoperability_in_ci_cd/) by Fatih Degirmenci and Kara de la Marck
            * [Events in CI/CD](https://fosdem.org/2021/schedule/event/events_in_ci_cd/) by Andrea Frittoli
    * [cdCon 2021](https://events.linuxfoundation.org/cdcon/), 23-24 June 2021
        * TM: CFP opens Monday, January 11th. CFP may stay open until after FOSDEM.
        * TM: SIG Interoperability will be reached out for Birds of Feather session.
        * TM: Registration is already open: https://events.linuxfoundation.org/cdcon/register/
        * TM: Expectation is to have about 3000 people. (300 already registered.)
* Events in CI/CD Workstream to become a separate SIG, Workstream Members
    * AF: The work on charter started happening and the discussion will happen during the very first meeting of the Events in CI/CD Workstream.
    * AF: The Events in CI/CD workstream meeting will happen on January 18th, 16:00UTC.
    * AF: The working document is here - still WIP: https://docs.google.com/document/d/1cuaOHmrvK20WxHxHZZuLif3CW3q1ICZ_RglJRp_IAQ0/edit?usp=sharing
    * FD: The topic of Events in CI/CD workstream becoming top level SIG will be discussed during the next CDF TOC Meeting on January 19th.
    * FD: CDF TOC Meeting logistics/agenda/minutes available here: https://docs.google.com/document/d/1uBHar55fTInWF9Li4t0lyG3tTC8BRLU0FfBfsgk_Jrs/edit?ts=5c9580be#heading=h.en8cy6hno0c6
    * KM: What kind of collaboration is happening toward CloudEvents?
    * AF: Not much happening with CloudEvents yet but we were thinking of using CloudEvents for transport. Need to check.
* [Standardized Metadata](https://hackmd.io/BYbkuR8uSlKt_w7Y4KE1OQ), James Strachan, All
    * DS: Where should the repo be?
    * FD: The repo will be in CDF organisation.
    * DS: Reached out to CNCF GitOps WG and SIG App Delivery and few people shown interest. Already got contribution for ArgoCD to Rosetta Stone CI/CD document.
* CDF End User Community, Tracy Miranda
    * TM: Very first topic everyone unanomously agreed was measuring DevOps Success. (e.g. MTTR from DORA folks)
    * TM: Link to blog post on measuring Devops: https://cd.foundation/blog/2020/11/05/measuring-devops/
    * TM: There will be discussions on what everyone is doing, how they are measuring.
    * TM: The group is keen on connecting what CDF is doing and the projects and groups under CDF.
    * TM: cdCon 2020 Tekton talk on how to collect metrics and display them on dashboard.
    * TM: This topic could be considered as a focus area within SIG Interoperability and we can schedule a call with the group and Dina Graves Portman.
    * TM: A demo could be made to this group. 
    * TM: There are already open source/propietary tools/dashboards such as Spinnaker, CloudBees so it would be good to get input from them as well.
 
#### Action Items
* ~~Fatih to ping Cameron on Jenkins Spinnaker for whitepaper~~
* Ramin A to bring an example manifest from eBay for metadata topic
* Tracy R/Steve T to demo Ortelius (manifest/metadata/visibility focused), 21st January
* Events in CI/CD workstream to provide input to standardized metadata topic based on their discussions
* Tracy M to bring the whitepaper to the attention of CDF creative team
* ~~Tracy M to help with updating meeting invitation according to what is agreed~~
* Tracy M to help with creation of a repo for standardized-metadata, https://github.com/cdfoundation/foundation/issues/262
* Steve to start the work on commit metadata
* Dave to start the work on artifact metadata
* Emil to bring Eiffel example in new repo
* Steve/Tracy R to bring Ortelius example in new repo
* Tracy to get SIG Interop in touch with Dina Graves Portman and invite her to one of the upcoming SIG meetings

#### Meeting Recording
* https://www.youtube.com/watch?v=655DDU3_AY8
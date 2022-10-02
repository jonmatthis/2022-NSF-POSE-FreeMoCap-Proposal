# Project Summary (rough)



###### tags: NSF_POSE, Oct2022


> **Quoted text** is phrases copied from - NSF Program Announcement - https://www.nsf.gov/pubs/2022/nsf22572/nsf22572.htm
> 
> Github repo at - https://github.com/jonmatthis/2022-NSF-POSE-FreeMoCap-Proposal

## Context of Open Source Ecosystem (OSE)

> Describing the context and vision of the proposed OSE. This required section must include a description of the 
> 
> - guiding principles and long-term vision for the proposed OSE,
> - the specific societal or national need(s) that the OSE will address,
> - the anticipated broader impacts of the OSE 
> 
JSM NOTE - Pull from front page of freemocap.org and [Epic Grant](https://docs.google.com/document/d/1vjeWHbORkfCzLxIlLJG7HXwrhk5i-JQ15dS-Td2dcgQ/edit)

> The section must have:
> 
> - a pointer to the existing publicly-available open-source product that is being transitioned;

- https://github.com/freemocap
- JSM NOTE - write `README` for freemocap organization

>  - details on: 
>      - the current status of the research product, 
>      - development model, 

- ENDURANCE

>      - methods of dissemination,

- website
  - freemocap 
  - 1500 unique views in last 28 days ?! 😧
- Github
  - 2k+ stars
  - buncha forks
- Twitter
- Twitch
- YouTube
- TikTok Kinda

>         >  -  and user base; and
>      
> - a description of the problem being addressed, and
 
 - Marker based mocap is expensive garbage 90s tech
     - super precise, but low tech solution requires huge labor (setup, post processing) bottlenecks that constrain the kinds of research that can be done (lab bound, equipment bound, etc)
 - modern comp sci makes new methods possible
     - CNN based skeleton tracking, like wow
     - open pose first, but there's a million of themm now
     - 
 - but you gotta do a lot of work to make ML based solutions 'epistemically groundded' (i.e 'reliable') enough to to generate scientific knowledge
     - that 'NN's are easily fooled' paper
     - (basically, NN's don't know when they are wrong, so you can't trust their judgement)
     - Gotta combine their very good estimates with a LOOOOT of other (more traditional) computation methods to shape those 'stats based' data with old school CV and computational geometry (i.e. synchronization, calibation, etc)
 - Also, folks got no mocap out there
     - Many applications for reliable measurements of human movement would open up if it was available to *everyone* 
         - It'd change - 
             - art 
                 - dance/circus performance
             - 3d animation
                 - film
                 - video games
             - science
                 - biomechanics
                 - neuroscience
                 - robotics
             - health
                 - physical therapy 
                 - gait/posture
                 - 'actvities of daily living'
             - 
 - so we should give it to them ✨
 - 
> - the novelty of the intended product being transitioned, including:
>     -  substantiating evidence of the technology's potential to significantly impact/address the problem.

- Lotta people using it:
    - V4Ndlo's vids
    - high school kids (twitter)
    - that other high school teacher that contacted me
    - Robot conductor from Florida
    - Steen Harsted's spinal biomechanics stuff
    - Mac Pribble (mprib)
    - Manitoba Mike
    - Kate's stuff
    - Chen Yu
    - Count up how many clips are in the freemocap server
    - Gotten pings from *14* differnt countries in the GUI
    - The person walking around in an empty room in what looked like a University lab 
    - Whosits at NEU doing sign language research
    - Teddy
- Analysis of website and social media traffic
    - TRENT
    - Need user surveys and whatnot

## Ecosystem Establishment/Growth:
> - Include a well-developed ecosystem` establishment/growth` and `ongoing discovery strategy` that ensures that the proposed OSE will:
>   
>     - further `develop the open-source product within the current technological landscape`, along with
>   
>     - specific plans to identify, engage and support potential users and partners who will serve as early adopters for the product`; 
>   
>         - specific plans to engage 
industrial: 
- Maurizio at IO
- Maybe Boston Dynamics?
- Epic Games
    - got a megagrant :D
    - 
and international collaborators are encouraged; 
- Steen Harsted and his thing
- website traffic very international
- gui pings from 14 countries
> 
## Organization and Governance: 
> - Describe a well-developed and sustainable `organizational`, `coordination`, and `governance` model including :

- copy what `ipython`, `numpy`, `astropy?` etc do
    - https://www.astropy.org/contribute.html
>   
>     - the licensing approach to be employed, 
- AGPLv3 - because this is such a human focused thing, people will have justifiable privacy concerns, esp w.r.t. privacy violations from video-focused social media corps (e.g. facebook, amazon, google, etc)
    - Also, there are services that use this behind a webportal, so we need the AGPL over the GPL
    - It's the same license Blender uses, and we're pretty closely aligned with them 
>     
>     - the specific continuous development, integration and deployment processes and 
 - Everything on/through/in Github
     - Use all the fancy tools and actions
     - Github competence as a 'core competency' of this project
>     - infrastructure that will enable the open, asynchronous, and distributed development of the open-source product and support sustainability goals for the OSE, along with 
>     
>     - metrics to assess and evaluate success, in the longer term, of the development methodology and 
>     
>     - processes for ensuring quality control, 
>     
>     - security and
>     
>     - privacy of new content;

- ENDURANCE 
    
## Community Building: 
- Describe a long-term strategy for community building to `engage`, `incentivize`, and `onboard` potential content contributors who will help in further developing and maintaining the open-source product;
  - Pipeline from low -> high XP contributors
  - Identifying and onboarding power users as moderators
    - Solidifying voting system for mods
    - Identifying votable issues for mods e.g.:
      - tooling
      - process
      - prioritization
    - Determining voting scheduling e.g.
      - weekly?
      - bi-weekly?
      - async?
  - Discord support `help-requests` channel workflow
    1. Initial support request
    2. Thread created via bot integration
    3. Support request handled within thread
    4. When resolved, mark initial SR with ✅
  - One-stop shop as prioritized backlog
    - Bot posts daily/weekly link to Github repo prioritized backlog?
  - Education as community
    - Mentorship and pairing
    - Matching system?
    - Reward and recognition for both mentor and mentee
      - XP
      - Server level-up
      - Roles
      - Channel access unlock
    - Possibilty of pure self-education
    - Streamlined doc/readme requests?

- TLDR Takeaways
  - Multichannel (self-directed, crowdsourced, mentor/mentee) pipeline from low XP -> power user
  - Implement multi-stream reward/level-up framework
  - Implement routine backlog prioritization 
  - Streamline discord support channel workflow
  - Mod voting system formalization

## Sustainability: 
- Articulate clear sustainability goals of the OSE, and 

  - an actionable evaluation plan, along with 
    - metrics to assess and evaluate success, in the longer term, of the development methodology, processes for ensuring quality control, security and privacy of new content, support for users, and onboarding mechanisms for new contributors.



## Time Line and Management Plan

Like a gantt chart or some shit

## Scientific Merit

Stuff and things that will make new knowledge and make science better


## Broader Impacts
- Data Access: Maybe write about you will make data available.

- Student Training: Write about how you will train students.

- Some Other Outreach: Write about more outreach.

- Dissemination: Write about how you will disseminate results (i.e., journal articles, workshops, etc).


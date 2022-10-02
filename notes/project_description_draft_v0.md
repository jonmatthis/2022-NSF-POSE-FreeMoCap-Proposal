# Project Summary (rough)

[![hackmd-github-sync-badge](https://hackmd.io/sXkHmMK6TfyiYrYnIwPycg/badge)](https://hackmd.io/sXkHmMK6TfyiYrYnIwPycg)




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
> - Describe a long-term strategy for community building to `engage`, `incentivize`, and `onboard` potential content contributors who will help in further developing and maintaining the open-source product;
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
>     - Matching system?
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
> - Articulate clear sustainability goals of the OSE, and 
> 
>   - an actionable evaluation plan, along with 
>     - metrics to assess and evaluate success, in the longer term, of the development methodology, processes for ensuring quality control, security and privacy of new content, support for users, and onboarding mechanisms for new contributors.

- ENDURANCE


## Time Line and Management Plan

Like a gantt chart or some shit

```mermaid
    gantt
        title      FreeMoCap Project Timeline
        dateFormat  YYYY-MM-DD
        section Years
          Year 1    :end_yr_1, 2023-07-01, 12m
          Year 2    :end_yr_2, after end_yr_1, 12m

```
## Scientific Merit

> Stuff and things that will make new knowledge and make science better
## IM-1 - Create next generation of motion capture technology
- The current gold standard in motion capture tech (marker based) is garbage
    - huge labor bottlenecks on both  data recording and post processing, which limits the kind of research that can be done and wastes uncountable numbers of labor hours
        - entire careers built on placing markers and manually cleaning recorded data
        - Also hugely expensive, with minimal costs in the 5 figure range and professional labs in the 6-7 figure 
    - IMU stuff can be good, but many  many problems
    - Might be useful for cleaning our data through!
        - orthogonol noise profiles
        - optical  is 'high accuracy low precision' inertial is 'high precision low accuracy'
        - so kalman filter 'em together 
## IM-2 - Build new paradigm of  human centered research (-or- "Laser Skeletons for everyone!")
- Build better tools to interogate the neural bases of the `Activities of daily living`
- Use the tools as training tools for next generation of scientists
    - Equip them for technologically driven research
    - Engage people from diverse backgrounds (e.g. Kiley and Philip)
- Creating these tools as a collaborative community will egender deeper engagement and 'stickiness' of educational aspects
- THe comp sci community creates new techno miracles every day
- But these new technological products are often not suited for reseach purposes blah blah blah
## Broader Impacts
## BI -1 - Now everybody will have motion capture!
- So now they can do things that would previously have cost (at least!) thousands of dollars for like, $40-50  
- SO immediately there are inroads into parts of the technological and scientific world that are no longer behind a massive cost barrier
    - Coaches
    - teach biomechanics
    - teach neurosciences
    - You could put a viable gait lab in every PT's office
    - You could set up little "freemocap" corners in people's homes and record balance assesssments or like, Range of Motion of a joint after surgery 
- And it's free baby! 
## BI-2 - The technical skills that `freemocap` teachers are the tools that will build the future of science and technology
- Set it up so that you don't need to under stand the underlying components to *use* it AND using it teaches you how it works
- Distributed, decentralized, hybrid synchronous/asynchronous
    - open up things to widest spread possible
- Good case studies of 'non traditionaly educational experiences'
    - Kiley
    - Philip
    - Manitoba mike
    - high school kids
    - mac pribble




# Unstructured other notes

## Community Support

- Challenge: AS the project grows, the effort of support increases
    - Solution: Build a strongly interconnected community that can help offset challenges of growth
- Building Mod team from power users
    - training in `Constituent Components` (see Educational Content)
    - 'Entry level' work to support bringing in, on-boarding, and encouraging help from Low/No XP newbs
        - Labs really benefit when there is a lot of meaningful 'low-skill' labor to be done, as it makes a place for new people to meaningfully contribute to the project in a way that *actually* helps
            - Teach them to make tech support tickets and point people towards docs
            - ... which will teach them about the technical issues and the layout and content of the docs!
            - Create an opportunity for self-directed exploration of `Constituent Components`
            - Anyone (from any level) can train someone to do this kind of work
            - `BUDGET` - Pay for this kind of help, somehow...

- Community grants program? 
    - Internal voting via 'eurovision' model
    - Voting rights given to power users, based on accrued XP

## Educational Content
- **"When education is not about liberation, the dream of the oppressed is to become the oppressor" - Paolo Friere**
    - Teaching teachers to teach teachers
    - Education always geared towards supporting autonomy and self-direction
- `Constituent Components`
    - Camera hardware and calibration
        - Lenses framerates etc
        - Capture volume calibration (multi-camera rig calibration)
    - Computer Vision 
        - Computational video analysis
        - Convolutional Neural Networks (skeleton tracking)
        - Classical comptuer vision (calibration)
    - Computer hardware
        - CPU/GPU/RAM/ etc
        - File storage and I/O
        - 'Big Data' management
            - Big Data = 'whenever you have to make plans around data storage, transfer, computational time, etc - you're working with big data' 
    - Machine learning
        - Skeleton tracking using massive trained models
    - 3D Geometry 
        - Multi-Camera capture volume calibration 
    - 3d Kinematic analytics 
        - time series analysis)
    - Programming, Software Architecture, UX/UI (python)

- Pedagogy vs Androgogy
    - Mentor based self learning
    - Apprenticeship models
- Self-directed branching Skill tree
    - Greased rail into heart of the matter (e.g time from 'first discovery' to 'looking at mocap data of *themselves* doing stuff)
        - Hope that studying one's own data will be intinstically motivating
        - Leverage 'healthy narcisism'/'fasicination with self' 
        - Directly tie the deeper contents to the personal self 
        - Part of the `gift freely given` aspect of open source

    - and then provide friendly tutorials branching out to `core compentencies` 
    - like plot hooks, invitations to go deeper, the "Would you like to know more?" model 
- Open source projects live and die by their documentation
    - Diataxis framework
        - Tutorials - Hand-holdy on-boarding
        - How To's - Step by step instructions
        - Explanations - Deep understanding of 'under the hood' tech and related scientific content
        - Reference - Glossary, Python API, etc
    - Directed education (Uses tool to teach REAL science)
        - Lesson Plan - Center of Mass /Balance 
        - Lesson Plan - Ball Catching




## Technical Infrastructure
- Universal Design
    - Usable by both Research Scientists and 13 year old with no technical trainng and not outside assistance
    - When things are accessible to *anyone*, **everyone** benefits
    - Keep the UX slick AF and accessible to people with Zero XP will also avoid bounding specialists (who are Zero XP relative to other fields)


- Software architecture capable of scaling
    - Cleaner code
        - Easier onboarding to projects
        - Easier support, easier to extend
        - Easier accept external support
        - Easier collaboration across fields
            - Good for science
            - Good for training
    - Emphasis on `architecture` 
    - Code written to comply with code standards (e.g. `PEP8 Python Style Guide`, `black` formatter, etc)
    - Paired programming/mentorship model 


- Future Proofing
    - Focus on 'core functionality' 

        - temporal syncronization
        - calibrating
        - UX/UI 
    - remain `hardware and software agnostic`
        - generic cameras ensure greater access
        -  Keep the buy in as low as possible, time to first :D low as possible 
        - Specialized hardware means you're beholden to whoever makes that hardware
            - Story of Kinect
            - Story of Intel RealSense
            - Story of Intel LiDar
            - Now people are building stuff based on iOS Stuff??    
            - Yikes
    - Make it work with generic hardware and then you can integrate more fancy things later using the same calibartion
        - LIke use Stereo cameras and LiDar 
        - Anything that makes `RGBD` data 
        - And just situate the point clouds on top of each other from each camera's location
        - You could probably clean then up with and Iterative Closed Point (ICP) algorithm? 
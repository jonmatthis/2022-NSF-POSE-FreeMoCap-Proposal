# FreeMoCap Project Description

## Community Support

### Challenge: AS the project grows, the effort of support increases
#### Solution: Build a strongly interconnected community that can help offset challenges of growth
### Building Mod team from power users
#### training in `Constituent Components` (see Educational Content)
#### 'Entry level' work to support bringing in, on-boarding, and encouraging help from Low/No XP newbs
##### Labs really benefit when there is a lot of meaningful 'low-skill' labor to be done, as it makes a place for new people to meaningfully contribute to the project in a way that *actually* helps
###### Teach them to make tech support tickets and point people towards docs
###### ... which will teach them about the technical issues and the layout and content of the docs!
###### Create an opportunity for self-directed exploration of `Constituent Components`
###### Anyone (from any level) can train someone to do this kind of work
###### `BUDGET` - Pay for this kind of help, somehow...
v 
### Community grants program? 
#### Internal voting via 'eurovision' model
#### Voting rights given to power users, based on accrued XP

## Educational Content
### **"When education is not about liberation, the dream of the oppressed is to become the oppressor" - Paolo Friere**
#### Teaching teachers to teach teachers
#### Education always geared towards supporting autonomy and self-direction
### `Constituent Components`
#### Camera hardware and calibration
##### Lenses framerates etc
##### Capture volume calibration (multi-camera rig calibration)
#### Computer Vision 
##### Computational video analysis
##### Convolutional Neural Networks (skeleton tracking)
##### Classical comptuer vision (calibration)
#### Computer hardware
##### CPU/GPU/RAM/ etc
##### File storage and I/O
##### 'Big Data' management
###### Big Data = 'whenever you have to make plans around data storage, transfer, computational time, etc - you're working with big data' 
#### Machine learning
##### Skeleton tracking using massive trained models
#### 3D Geometry 
##### Multi-Camera capture volume calibration 
#### 3d Kinematic analytics 
##### time series analysis)
#### Programming, Software Architecture, UX/UI (python)

### Pedagogy vs Androgogy
#### Mentor based self learning
#### Apprenticeship models
### Self-directed branching Skill tree
#### Greased rail into heart of the matter (e.g time from 'first discovery' to 'looking at mocap data of *themselves* doing stuff)
##### Hope that studying one's own data will be intinstically motivating
##### Leverage 'healthy narcisism'/'fasicination with self' 
##### Directly tie the deeper contents to the personal self 
##### Part of the `gift freely given` aspect of open source

#### and then provide friendly tutorials branching out to `core compentencies` 
#### like plot hooks, invitations to go deeper, the "Would you like to know more?" model 
### Open source projects live and die by their documentation
#### Diataxis framework
##### Tutorials - Hand-holdy on-boarding
##### How To's - Step by step instructions
##### Explanations - Deep understanding of 'under the hood' tech and related scientific content
##### Reference - Glossary, Python API, etc
#### Directed education (Uses tool to teach REAL science)
##### Lesson Plan - Center of Mass /Balance 
##### Lesson Plan - Ball Catching




## Technical Infrastructure
### Universal Design
#### Usable by both Research Scientists and 13 year old with no technical trainng and not outside assistance
#### When things are accessible to *anyone*, **everyone** benefits
#### Keep the UX slick AF and accessible to people with Zero XP will also avoid bounding specialists (who are Zero XP relative to other fields)


### Software architecture capable of scaling
#### Cleaner code
##### Easier onboarding to projects
##### Easier support, easier to extend
##### Easier accept external support
##### Easier collaboration across fields
###### Good for science
###### Good for training
#### Emphasis on `architecture` 
#### Code written to comply with code standards (e.g. `PEP8 Python Style Guide`, `black` formatter, etc)
#### Paired programming/mentorship model 


### Future Proofing
#### Focus on 'core functionality' 

##### temporal syncronization
##### calibrating
##### UX/UI 
#### remain `hardware and software agnostic`
##### generic cameras ensure greater access
#####  Keep the buy in as low as possible, time to first :D low as possible 
##### Specialized hardware means you're beholden to whoever makes that hardware
###### Story of Kinect
###### Story of Intel RealSense
###### Story of Intel LiDar
###### Now people are building stuff based on iOS Stuff??    
###### Yikes
#### Make it work with generic hardware and then you can integrate more fancy things later using the same calibartion
##### LIke use Stereo cameras and LiDar 
##### Anything that makes `RGBD` data 
##### And just situate the point clouds on top of each other from each camera's location
##### You could probably clean then up with and Iterative Closed Point (ICP) algorithm? 


# Intellectual Merit
## IM-1 - Create next generation of motion capture technology
### The current gold standard in motion capture tech (marker based) is garbage
#### huge labor bottlenecks on both  data recording and post processing, which limits the kind of research that can be done and wastes uncountable numbers of labor hours
##### entire careers built on placing markers and manually cleaning recorded data
##### Also hugely expensive, with minimal costs in the 5 figure range and professional labs in the 6-7 figure 
#### IMU stuff can be good, but many  many problems
#### Might be useful for cleaning our data through!
##### orthogonol noise profiles
##### optical  is 'high accuracy low precision' inertial is 'high precision low accuracy'
##### so kalman filter 'em together 
## IM-2 - Build new paradigm of  human centered research (-or- "Laser Skeletons for everyone!")
### Build better tools to interogate the neural bases of the `Activities of daily living`
### Use the tools as training tools for next generation of scientists
#### Equip them for technologically driven research
#### Engage people from diverse backgrounds (e.g. Kiley and Philip)
### Creating these tools as a collaborative community will egender deeper engagement and 'stickiness' of educational aspects
### THe comp sci community creates new techno miracles every day
### But these new technological products are often 
# Broader Impacts
## BI -1 - Now everybody will have motion capture!
### So now they can do things that would previously have cost (at least!) thousands of dollars for like, $40-50  
### SO immediately there are inroads into parts of the technological and scientific world that are no longer behind a massive cost barrier
#### Coaches
#### teach biomechanics
#### teach neurosciences
#### You could put a viable gait lab in every PT's office
#### You could set up little "freemocap" corners in people's homes and record balance assesssments or like, Range of Motion of a joint after surgery 
### And it's free baby! 
## BI-2 - The technical skills that `freemocap` teachers are the tools that will build the future of science and technology
### Set it up so that you don't need to under stand the underlying components to *use* it AND using it teaches you how it works


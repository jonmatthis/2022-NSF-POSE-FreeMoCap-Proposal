# FreeMoCap Project

## Community Support

### Challenge: AS the project grows, the effort of support increases
#### Solution: Build a strongly interconnected community that can help offset challenges of growth
### Building Mod team from power users
#### training in core competencies (see Educational Content)
#### 'entry level' work to support brining in help from No XP newbs
#### Teach them to make tickets and point people towards docs

### Community grants program? 
#### Internal voting via 'eurovision' model
#### Voting rights given to power users, based on accrued XP

## Educational Content
### **"When education is not about liberation, the dream of the oppressed is to become the oppressor" - Paolo Friere**
#### Teaching teachers to teach teachers
#### Education always geared towards supporting autonomy and self-direction
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



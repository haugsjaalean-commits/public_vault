 
# OOF 0.1: Building on top of my [[OOF 0.0|original method]] to create a more effective system


## Conceptualizing the system 

### Working through what I need it to do

In my original method, I use [[tags]] to describe a class system. Each class inherits from the root class called "object". This seems ok at first; after all, we *are* trying to describe the very nature of our KU (our notes), but, if we think this, we are forgetting one key detail. The *nature* of the KUs are described by all of their connexions, meaning that it cannot be described with just one linear structure. 

However, this linear structure does prove incredibly useful when it comes to filtering with [[bases]] and also creating structures of inheritance with [[templates]]. 

Therefore, the question is how to maintain the positive aspects of inheritance and tags without the negative drawbacks the strict folder-like structure that they create.  

### How to do it 

I am completely scrapping the idea of using [[tags]]. Tags only become a hinderance. The solution, then, is to use fields for semantic relationships. For starters, I would suggest these two fields:
1. `is a`
2. `has a`

The only problem is that, if C is a B, and B is a A, then C is a A. This means that a [[bases|base]] which searches for all As should also find Cs and Bs. This isn't possible if all that C says is "is a B". What I take from this is that we have to "inherit" all relationships. This means that ,in the *is a* section of C, we will put this text: "is a B, A". That way, when we search for all As we will also find all Cs. I think that this should work the same for all other relations like *has a*. 

N.B. If something *is a* something else, we do not only need to carry over the *is a* information, but we also need to carry of the *has a* information. 

(I do think that, in some complexe situations, my method will probably fall apart, but it's the best thing I've come up with for the time being.)
#### My Syntactic suggestion for doing this

We could use a property of type `list` but I think this would loose us clarity; instead, I suggest simply using a `text` property. This way, we can put inherited attributes in `()`.

##### Example

Let's say that we are creating a file for a Labrador. We would have the following relationships:

`is a: dog, (mammal, animal)`

This way, we clearly see that "dog" is the main thing that we want to showcase, and all of the other things are inherited from dog and simply used for querying in [[bases]]. 


#### Can I programme it? 

Probably, there is a way for me to program a plugin for Obsidian which would allow me to make the workflow work better. Consider I don't really feel like programming anything right now, I will not put too much thought into this for the time being. 


### Thoughts on the system (I can add more here)

I think that this system is definitely not as sophisticated as the one I envisioned in my theory, but it's still better than what I made in my previous OOF. Creating this really challenged my mind, and I think that a smarter person or a smarter Leander could probably understand it better and come up with a better way of implementing it. I'm going to try to not worry about that thought, because I don't think that it will actually help me--baby steps.


## Building the framework



Above, I discussed how we could use properties (attributes) to effectively create lines of inheritance. This is very powerful, so, in this section, I will be going over the system we can build on top of it. 

---

First of all, the [[YAML|frontmatter]] properties will have two different types:
1. ***Characteristics***: These are the things which determine the behaviors. Characteristics are always properties with purely theoretical meaning. 
2. ***Behaviors***: These are things which are given by characteristics. Characteristics can either add or subtract behaviors. Behaviors usually have more literal meanings. 

N.B. All objects have access to all of the characteristic types; however, behavior types need to be given to an object by their characteristics.

Behaviors can only be given by *is a* relationships.  

Using characteristics and behaviors, we can create ***Architypes***. These are like classes, and they serve as collections of characteristics. 

I would suggest creating a note for each Architype, in order to keep track of all of them. Another option would be using PlantUML. If one chooses to make notes to keep track of architypes, they should include the [[templates]] and [[bases]] which they're created for. These Architypes should be kept in a separate `architypes` folder. 

Conversely, instead of making *architype* notes, I could make notes listing characteristics and their behaviors. The architypes folder can simply be used for templates. 



### Dimensions of behaviors 
- ***Dependency*** 
	- ***Internal***: The behavior needs to be inherited
	- ***Global***: The behavior does not need to be inherited
- ***Function***
	- ***Informational***: The behaviors serves the purpose of enriching the object.
	- ***Organizational***: The behaviors aids in the organization or placement of the note in the KG. 


## Working on it












## New 

### What the system needs to do - explanation



### Modeling the system - rules



#### What are the notes?



Notes are KUs. Except, there is one caveat: notes also, in some ways, act like GPs. Because notes can be concepts, we can use concepts to create search paths which resemble those created by GPs, and one that mimics semi-rigid organization. 

What I'm saying is that, instead of having two levels--one level for organization and another for connexions--we have one level where the notes themselves are used for organization. 

What we get from this 











 
# My idea for how to model the different datatypes and semi-objects at play in the organization of notes
This is the toughest part of organization--the true crux of organization. 

As stated above, we want to figure out the simplest and most direct way of representing the complexe mental relationships that exist between objects with this real world tool called Obsidian; this is no easy task indeed. This is the type of thing that one can spend a life time perfecting, and I plan very much on doing so. 

## Describing objects with classes

I think that the most effective way of defining the individual characteristics of objects is by thinking of each note as belonging to a class. We can think of each class type as a compressed search pathway representing the lineage of the class. Since the "type" of each class is supposed to represent the *nature* of the object, I think that each object should only have one class, as it doesn't make sense for an object to have multiple natures: a *thing* cannot be two *things* at once. 

There are definitely many, many different ways of thinking about this, but I have found that a semi-strict class system--almost as if I were programming--leads to very organized outcomes. 

This is definitely something that I want to put more thought into in the future! 

### How to create classes using [[YAML|frontmatter]]

#### Using [[tags]] to describe classes
While I have seen other people use a different method, my current chosen method for describing the type of the class is by using the `tags` parameter in the frontmatter. I have one main reason for this:
- By using tags, the class of the object has a clear hierarchy. This is crucial for keeping things logical, and, on top of that, it makes filtering for a specific object in a [[bases|base]] exceedingly easy. The [[Tag Wrangler]] plugin is crucial for making the workflow work, as it adds functionalities for renaming and changing tag hierarchies.

(The different method I mentioned earlier consists of simply using the `text` property type in the [[YAML|frontmatter]] as the class type. I can understand the desire to do this, but I see some real advantages to using tags.)


#### Adding other crucial frontmatter

Now that we have described what *kind* of object we are dealing with using the tag, we will need to give our object the information that will allow us to sort it in a [[bases|base]] and understand what it is. I would put these types of frontmatter into two main categories:
1. **Organizational frontmatter** is used to sort, filter and group objects in [[bases]]. An example of this would be the use of a `raiting` parameter, which allows us to easily sort our notes in a [[bases|base]]. Moreover, we could use a `gategory` parameter to easily filter notes when creating sub [[bases]].  
2. **Informational frontmatter** is used to tell us crucial information about an object. A good example of this would be a `related` parameter, which is a list of links pointing to related notes. Additionally, we could have a parameter linking to external websites, which enrich the original note, for example a link to an article or a Pinterest board. 


#### Concrete example


A perfect example of my use of [[YAML|frontmatter]] for describing objects is my `Brian Sum.md` note. Brian Sum is an artist who focuses on industrial design, and his note appears in my `artist visual.base` base. 


![[Modeling classes-1.png]]







### What we can do with classes


The most obvious utility of a classe is creating a big list of things that will be displayed in a [[bases|base]], and this is often--if not always--what we're doing, but it's not always in the way you'd expect.

Let's say that we want to create a list of notes that we would like to come back to and improve




To explain what I mean, I am going to go on a small tangent. 


To explain what I mean, I am going to walk you through a practical example. In this example, we wish to create 


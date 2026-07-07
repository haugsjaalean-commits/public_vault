---
aliases:
  - base
---


BASES ARE AMAZING!!! If you remember only one thing I say, I want it to be this. Bases are truly the thing that make Obsidian so powerful and fun.

## Create a base
Canvases can be created using the following methods:
1. Create a `.base` file
2. Use the option in the toolbar (otherwise called the ribbon)
3. Use the command from the command pallet
4. Use the hotkey (if one exists, otherwise create a hotkey)




## How to use bases


Bases are incredibly simple and easy to use, but there are a few tips, tricks, and best practices. That's what I'll be going over in this section.

### The basics of bases 

![[bases.png]]


Above, I have taken a screen shot of my `artist visual.base` base. There are many YouTube videos which explain bases in a very fast and succinct manner, and bases are very intuitive, so I will try to be quick in the section as I explain all of the options of bases.

#### Views
![[bases-1.png]]


In the top left of the base, we have the option to edit the different views of the base. As I will explain in sorting, each view has it's own unique filters. This means that each view can be a more focused version of the greater base. 

---


![[bases-2.png]]

If we click on the options for one of the view, we have the option to change the way it's being displayed (the "layout") and other options which are unique to each layout, like the "image property" for the "cards" layout.

N.B. The **Image property** (used in the **Cards layout**) reads from a given property in the [[YAML|frontmatter]] of each note. This property needs to be of type **text**. You have two options when it comes to the information you put in this field:
1. An image URL from the internet: ![[bases-3.png]]
2. The name of an image which exists in your vault: ![[basesv.png]] N.B. This cannot be a link with `[[...]]`; it must only be the name of the image file. 

#### Sorting
![[bases-4.png]]


This is very intuitive. We can chose a property to group by, and we can have any number of properties used to sort by.  



#### Filtering
![[bases-5.png]]


Filtering is the bread and butter of bases: it's what allows us to decide what we even want to see in our base. Obsidian bases work in a unique manner. In a real database, only a given set of data exists in the base, but in Obsidian, the entire vault exists in every base. We simply filter out the notes we don't want to see by adding filters. 

I won't go into all of the details of filters, as they are very intuitive, but I will explain the main two concepts: 
1. **All views**: Filters added here affect all views (obviously). In most of my bases, this section looks very similar: usually, my first filter looks for my objects with a certain class ([[tags|tag]]); my second filter will then filter out the template, which will also contain this tag; and subsequent filters are optional and will be used to further narrow my base. 
2. **This view**: These filters are used to further narrow down the specific view of a base. In the screen shot above, I use this section to search for only artists who's **medium** property (of type **list**) contains **pen and ink**.




#### Properties & Search
![[bases-6.png]]



I put **Properties** and **Search** together, because they are complimentary to each other. 

The Properties section dictates which properties will be visible in the base. A property *does not* need to be visible in order for it to be used for sorting, grouping, or filtering; however, it *does* need to be visible for it to be used by the quick search option just to the right. For this reason, it's crucial to have important properties visible; that way, it's extremely rapid to search for common files based on these properties. In my `artist visual.base` base, I use this all the time to search for artists with common domains, like *industrial design*. 




### Best practices


As explained in [[Obsidian Bases--Obsidian's Biggest Upgrade (Complete Guide)]], there are a few different best practices, which will help you get the most out of bases:
1. Duplicate views: When creating new views, it's often more efficient to simply duplicate an already existing view. This way, there is no need to redo your property settings, or the image property field for cards, etc. 
2. Go from *general* to *specific* with views: It's always important to start of by trying to make the base itself as general as possible. This way, you have more freedom in creating the individual views in the base, and you are less likely to create multiple bases which do the same or similar things. 








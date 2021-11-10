Di Lu: Houdini Terrain Homework
=================

Pt 1: More Interesting Terrain: 

**bolded nodes are the nodes I added**

1. heightfield1 = plane
2. heightfield_noise1 = noise function over plane
**3. heightfield_noise2** 
4. heightfield_masknoise = mask over height 
5. heightfield_slump1 = smoothed valleys of terrmain
6. attribdelete1 = ??
7. remesh = remeshed the height map
8. facet2?
9. Add primitive scatters to the scene
10. Scatter node = decides scatter pattern of geometry
11. colored scatter nodes = randomly colored scatter nodes? \
12. copytopoints2 = copies primitives to the points and colors them based on their scatter colors
13. Mergenode = with terrain plane
14. output!

# hw05-houdini

## Goal
Explore Houdini and get a basic understanding of the workflow and interface.

For this assignment, our resident Houdini expert Dan will provide a a simple Houdini network that spawns objects on a bit of terrain. It's not a terribly complex or interesting scene! Please experiment to make it more interesting :)

### Terrain (15 pts)
Using at least 6 additional nodes, make the terrain more realistic, or otherwise interesting. Suggestions: layered noise, merging in another shape, sin wave hills.

### Scene Objects (20 pts)
Using the provided set up, change the unit cubes to a more interesting model. Add your chosen models on top of the terrain using more complex scattering logic. Suggestions: import a model and scatter them in an attractively random manner, grow l-system that are more dense in one area than another, model something in Houdini and place them in a summoning circle.

### Make it usable! (15 pts)
Once you're satisfied Make your toy a usable tool by adding at three widgets/parameters that are referenced in your graph. Export your project as an HDA with three exposed parameters to mimic professional packaging.

### Extra spice (20 pts)
Add something extra to your scene! Experiment! If it's wonky, who cares! Google and Youtube are full of interesting resources. Look through the docs pages for ideas too. Suggestions: Add coloring based on some rule. Animate some elements of your scene. 

### Submission
Submit your Houdini file to canvas this time, since this assignment isn't githubable.


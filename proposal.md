# X-Team NN Project Proposal

See https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet#code for tips on using *Markdown* tags to format __.md__ files

## Goal

Work as a team to create a project proposal for your X-team to complete together.
The project does not have to be extremely difficult,
but there must be work to do for each member of your team.
You may reference figures using "See figure 1".  
Be sure to submit corresponding image files, i.e. figure1.png (or figure1.jpg) for each figure.

## Grading: To earn full credit, your team's proposal must include:

* (md) documentation: [this file] describing purpose and use of your program

* Description of a program that has:

  ** a main Java program class in a file named Main.java
  
  ** a custom data structure designed and built by your team
  
  ** comprehensive testing of individual units
  
 Caution: You are not being asked to implement this program, at least not yet. 
 We just want your group to make a proposal or pitch for your program.
 
 Tip: Your custom data structure can be composed of or extensions of data structures that you have learned and used in previous programming assignments.  We're looking for decisions about how to build a high-level data structure that will likely have lower-level components.

## Problem Description
There are too many internet tabs and they are cluttering the window.

Our solution is a google chrome add-on that allows the user to create tab folders and group tabs together according to users preference. This would reduce clutter and make tab management easier.

## Questions to answer for Exercise #2

1. Name: Give your project proposal a name (and edit the top line of this file)

The Google Chrome Tab Inception 

2. Output: Describe the output your program will produce.  Include and example format of the output produced.

A google chrome window that has tabs nested in folders that appear at the top of the window.

3. Input: Describe the data that is needed to solve your problem. Include an example format of the input data.

The URLs for all the tabs and the parent folder for each tab would be required to format the tabs in the window. The folders would also require user-imput names or default names.

4. User Interface: Describe a user interface for your program.  Use text menus or a simple graphic user interface.

It will look very similar to the current Google Chrome layout. Users can drag tabs on top of each other and will be given the option to create a new named tab folder. The folders would be stored from the top left of the tab window. When a folder is selected, a drop-down list will appear that contains all the tabs within that folder. The folder can be collapsed and expanded. It is possible to nest folders.

5. Types List: Break your solution idea down into units that you think can be implemented with a single class.

The data would be a stored in a tree that represents the window-folder-tab hierarchy. The root would be the window node and its children would be either folder nodes or tab nodes. A tab node will always be a leaf node, but a folder node could be a leaf node. A folder as a leaf node would represent an empty named folder. Each folder node class will contain pointers to other nodes. The tab node would contain a list of URLs.

## Edit and Submit this file and any figures referenced by this document.


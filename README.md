This is a dense set of instructions for how to use this vault! I had ChatGPT make a README based on this one which can be found at [[ChatGPT README]]. It misses key points and hallucinated some things about how to use this repo, but if you want a TL;DR, head over there!
# Introduction
I've been using [Obsidian](https://obsidian.md/) for a couple months and really enjoying it, but this past week I read Getting Things Done by David Allen and massively improved my note organization. I recommend reading the updated 2015 version of the book, since a lot of the ideas I'll be referencing in this post may not make sense without having read the book, and he expands on a lot of useful tips for all these steps and other best practices.

This is a basic framework vault for using the Getting Things Done method. The files, folders, and templates I'll be referring to are in this vault. The basic workflow I'm describing here is shown in the flow charts in the [[Inbox]] file.

This file is ideally read in Obsidian, where the [internal links](https://help.obsidian.md/links) to files within the vault will work. Download this vault to your computer, and open the folder as a vault in Obsidian. 

I recommend using [Syncthing](https://github.com/syncthing/syncthing) to sync your vault between your devices, it works very well. 
- [Android app](https://github.com/Catfriend1/syncthing-android?tab=readme-ov-file)
- [iOS app](https://apps.apple.com/us/app/m%C3%B6bius-sync/id1539203216#?platform=iphone)
If you set up Syncthing and don't already have a password manager, I highly recommend setting up a [KeePass](https://keepass.info/) vault. Access it with [KeePassXC](https://keepassxc.org/) on desktop, [KeePassDX](https://www.keepassdx.com/) on Android, and [here are some options for iOS](https://keepassium.com/articles/keepass-apps-for-ios/).

# The workflow
## The [[Inbox]]
To start, any ideas, todos, reminders, etc you think of, put them in the list in the [[Inbox]] file. Then, when you process them, follow the flow charts for how to organize it. 

## Following the [[GTD stuff flowchart.png|flowchart]]
### Non-actionable items
If you have something that isn't actionable, you decide to either delete it, add it to the someday/maybe file, or store it in the `Reference material` folder (See [[Sample reference material]]). You can spin up a project with the project workflow described below when adding things to the someday/maybe file if you want, or you can add it to any non-project section you want. The someday/maybe file is much looser in it's structure, which is fine especially if you're reviewing it weekly. The `Reference material` folder is also pretty loose. Store things in there however you want so you can easily access them if/when you need them.

### Actionable items
If it is actionable, and it would take more than two discrete actions, you spin up a project. Otherwise, skip to the concrete next action stage

#### [[Projects]] (Anything with more than one step to complete)
Go to to the [[Projects]] file, and at the bottom of the list of projects, insert the template called [[Project list template]]. Then, replace the link with a name of the project. The Outcome vision and Next action embeds must also be edited to use the new link (only edit the link before the `#^` part). You can tap or click on them to see and edit the actual link they use. Now tap the Project link header to create and open the file for the project, and insert the template called [[ProjectTemplate]]. Personally, I always fill in the Purpose section and Outcome vision section, since those are key to having a "healthy" project according to the Getting things done method, and I find them useful and worthwhile on every "project" I've spun up. The Brainstorming and Organizing sections depend much more on the specific project, most of mine are easy enough that I don't need to fill those out, but some do need some extra processing and in that case those sections are helpful. Finally, make sure to define at least one Next Action, something that you could do right now if you were in the right context and had nothing else to do. It must be very specific, see the book for the explanation of the importance of concrete next actions. Once you have a concrete next action defined, go to the next step
#### Concrete next action
Once you have the next action defined for your project (or the [[Inbox]] item you're talking about is only a one-step thing anyways), take that and keep going through the flowchart in [[Inbox]]. If it would take <2 minutes, do it right now (if the action is part of a project, once you're finished define the new "next action" and continue the flow chart again). If the next action would take >2 minutes, decide what to do with it. If it's something you're waiting on somebody else for, it will go into the Delegated section of the [[Next actions]] file. If it's something you yourself will do, it will go under the appropriate context in the [[Next actions]] file (feel free to change the contexts however suits you best. The book has great guidance on different ways of organizing your contexts). If it's something you need to be reminded of at a specific day and/or time, put it in your [[README#Calendar|calendar]]. And if it's something you'll do eventually but you're not sure when, the project should probably be listed in the [[Someday maybe file]] instead of the [[Projects]] file, and in that case, you shouldn't add it in the [[Next actions]] file.

##### Adding project next action to [[Next actions]] file.
To add an action from a project to your [[Next actions]] file, copy the next action embed from the [[Projects]] file into the context list, so that way when I check off the item, it also checks it off in the project file and the [[Projects]] list, and when I go in to the project file to set a new next action (by moving `^next-action` to the end of the line of the next action), it updates across [[Projects]] and [[Next actions]] too. There's an example of how this works already set up in the vault, I recommend looking at all the files in [source mode](https://help.obsidian.md/edit-and-read#Source+mode) so you get an idea how it all works.

### Calendar
The only thing missing is a calendar, you'll want a proper calendar app that can generate notifications. I recommend [Fossify Calendar](https://github.com/FossifyOrg/Calendar), because in addition to standard events it can also create "tasks", a time based event that doesn't go away until you mark it as "Completed". This is a pretty key part of my workflow for reminding myself to do stuff at certain times and helping me track whether it's done or not, and keep it in focus till it is. Make sure to follow the GTD method and keep the calendar strictly for things that must be done at a certain time and/or on a certain day. Reviewing your calendar every morning is a helpful habit for getting the most out of it.

## [[Weekly review]]
The [[Weekly review]] file is a condensed, hopefully-self-explanatory checklist derived the book. The book has a lot of good info on why the weekly review is super important. 

## Horizons
The vault is also already set up with a [[Document GTD horizons|project]] to define some of the different horizons the book references (current actions, current projects, areas of focus/responsibility, one to two year goals, long-term visions, and your overall life). This isn't necessary to complete, but it might be helpful, and it gives you an example of how to organize a project file and link it to the other files (again, look through all the files in [source mode](https://help.obsidian.md/edit-and-read#Source+mode) to see how they're set up).

# Using this vault
It really is worth looking at each file in this vault in [source mode](https://help.obsidian.md/edit-and-read#Source+mode). That will make it easier to understand what's going on, and how to move things around effectively. Sometimes it's easier to work in source mode, so that the formatting doesn't jump around while you're doing things. If there's some formatting you don't understand, look in the [Obsidian Documentation](https://help.obsidian.md/)!

Also check out the [graph view](https://help.obsidian.md/plugins/graph) to get an idea of the layout!

# Help make this better
I wrote this guide up pretty quickly and haven't deeply proofread it. If anything's unclear or could be explained better, or I made typos, or whatever, please let me know! Ultimately I want to create a nice polished version of this guide so I can share it with coworkers and friends, but this is the rough draft. Feel free to open an issue or pull request!

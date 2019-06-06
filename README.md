# Sublime Merge vs SourceTree (Git client comparison)

I stopped using Sourcetree (Windows version) a few weeks ago and haven't looked back.

Here are some reasons why [Sublime Merge](https://www.sublimemerge.com) is a far superior Git client:

- It integrates natively with Sublime Text.

  *(You can specify a default editor in Sourcetree)*

- Its lightning fast.

  *(Sourcetree is a turtle in comparison)*

- The entire interface is consistent and elegant.

  *(Sourcetree is clunky)*

- It has a dark theme.

  *(Sourcetree doesn't have this feature)*

- Back/Forward navigation buttons.

  *(Sourcetree doesn't have this feature)*

- `Ctrl`+`Click` any two commits to see a diff of them.

  *(You can do this in Sourcetree but its buggy and doesn't give the correct result most of the time)*

- Cloning a repo is wonderfully simple:

  ![Screen shot](https://crazytim.github.io/sublime-merge-vs-sourcetree/img/merge-005.png)

  *(In Sourcetree there are so many clicks and options, and it is so slow performing the clone)*
  
- The work flow for resolving merge conflicts is vey streamlined:

  ![Screen shot](https://crazytim.github.io/sublime-merge-vs-sourcetree/img/merge-007.png)

  *(The workflow in Sourcetree is vauge and unintuitive)*
  
- Some buttons show what git commands they execute (handy if you're learning how git works).

  ![Screen shot](https://crazytim.github.io/sublime-merge-vs-sourcetree/img/merge-008.png)

  *(Sourcetree is a black box and its difficult to guess what buttons actually do (labels are poorly written too), which makes it scarey for learners to explore)*
  
- There are many handy commands, each showing the associated git commands they run:

  ![Screen shot](https://crazytim.github.io/sublime-merge-vs-sourcetree/img/merge-010.png)

  *(The Sourcetree interface is more GUI-based)*

- The name of checked out branch is prominent:

  ![Screen shot](https://crazytim.github.io/sublime-merge-vs-sourcetree/img/merge-004.png)

  *(Sourcetree only bolds the branch name, which is hard to see with lots of branches)*

- Easily inspect the state of any file as of a certain commit.

- Easy to copy text from the diff view (SourceTree only allows you to copy line-by-line).

  ![Screen shot](https://crazytim.github.io/sublime-merge-vs-sourcetree/img/merge-003.png)

- Hide/show individual local/remote branches.

  ![Screen shot](https://crazytim.github.io/sublime-merge-vs-sourcetree/img/merge-006.png)

- Powerful find (`Ctrl`+`F`), and there is a query syntax:

  ![Screen shot](https://crazytim.github.io/sublime-merge-vs-sourcetree/img/merge-002.png)

  *(Sourcetree search is slow and uninspiring)*

- The layout adjusts well when the window is resized and everything stays in place.

  *(Occasionally the Sourcetree window can't be dragged, panels get stuck and cant be resized, and panels adjust using percentages. Also the commit message panel doesn't resize automatically like Sublime).

- The graph design is nice and simple. You can collapse merged branches as well, which is nice.

  ![Screen shot](https://crazytim.github.io/sublime-merge-vs-sourcetree/img/merge-009.png)
  
- Diff view changes to 2 columns when the window is large enough.

  *(Sourcetree doesn't have this feature)*

- Installing Sublime Merge is dead simple.

  *(Source tree requires you to register with a BitBucket account, plus several other steps)*

- You can see stashes in the graph.

  *(Sourcetree doesn't have this feature)*

- Interactive rebase commands are performed separately, and this works out to be very intuitive. Simply `Ctrl`+`Click` multiple commits, then use the context menu to squash, reorder, amend commit message, etc.

  ![Screen shot](https://crazytim.github.io/sublime-merge-vs-sourcetree/img/merge-001.png)

  *(The Interactive rebase interface in Sourcetree is vauge and unintuitive because it provides an interface to do everything all at once)*

### Sourcetree bugs that make me furious:

- Regular crashes and needs to be reinstalled (or reboot pc), usually just after updating Microsoft Office.

  ![Screen shot](https://crazytim.github.io/sublime-merge-vs-sourcetree/img/merge-011.png)

- Regularly complains about corrupt dictionaries and asks if I want to delete them (??).

- Keeps prompting for authentication for each repo separately (very frustrating).

- Sometimes when you click on a branch it doesn't jump to it in the graph view.

- Doing a diff between two different commits is not always reliable (usually doesnt show all the files that are changed).

So what are you waiting for? [Go and download it now!](https://www.sublimemerge.com)
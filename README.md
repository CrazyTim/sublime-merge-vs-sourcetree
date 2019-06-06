# Sublime Merge vs SourceTree

I stopped using Sourcetree (Windows version) a few weeks ago and haven't looked back.

Here are some reasons why I think [Sublime Merge](https://www.sublimemerge.com) is a far superior Git client:

- Its lightning fast.

  *(Sourcetree is a turtle in comparison)*

- The entire interface is consistent and elegant.

  *(Sourcetree is clunky)*

- It has a dark theme.

  *(Sourcetree doesn't have this feature)*

- Back/Forward navigation buttons.

  *(Sourcetree doesn't have this feature)*

- `Ctrl`+`Click` any two commits to see a diff of them.

  *(Sourcetree can do this, but its buggy and doesn't give the correct result most of the time)*

- Interactive rebase commands are performed separately, and this works out to be very intuitive. Simply `Ctrl`+`Click` multiple commits, then use the context menu to squash, reorder, amend commit message, etc.

  ![Screen shot](https://crazytim.github.io/sublime-merge-vs-sourcetree/img/merge-001.png)

  *(The Interactive rebase interface in Sourcetree is vague and unintuitive)*

- Cloning a repo is wonderfully simple - you can do it in two clicks (seriously):

  ![Screen shot](https://crazytim.github.io/sublime-merge-vs-sourcetree/img/merge-005.png)

  *(In Sourcetree there are so many clicks and options, and it is so slow performing the clone)*
  
- The work flow for resolving merge conflicts is very streamlined:

  ![Screen shot](https://crazytim.github.io/sublime-merge-vs-sourcetree/img/merge-007.png)

  *(The workflow in Sourcetree is vague and unintuitive)*
  
- Tool tips on some buttons show what git commands they execute (handy if you're learning how git works).

  ![Screen shot](https://crazytim.github.io/sublime-merge-vs-sourcetree/img/merge-008.png)

  ![Screen shot](https://crazytim.github.io/sublime-merge-vs-sourcetree/img/merge-010.png)

  *(Sourcetree is a black box and its difficult to guess what buttons actually do. labels are poorly written too, which makes it scarey for learners to explore)*

- The full path to the repo is shown in the Window title.

  *(Sourcetree doesn't have this feature)*

- Its possible to open multiple windows if that's what you need.

  *(Sourcetree opens repos as tabs inside a single window, so you can't do a side-by-side of two repos)*

- Instantly switch to another repo using `Shift`+`Ctrl`+`O`. Sublime Merge will remember any repo you have previously opened.

  *(Sourcetree gets slower the more repo tabs there are. Its just clunkier.)*

- The checked-out branch name is prominent:

  ![Screen shot](https://crazytim.github.io/sublime-merge-vs-sourcetree/img/merge-004.png)

  *(Sourcetree only bolds the branch name, which is hard to see with lots of branches)*

- Easily inspect the state of any file as of a certain commit (`Right-Click` on a commit > `View Tree`).

  *Source tree only shows you files that where modified as part of the commit.*

- Easy to copy text from the diff view (SourceTree only allows you to copy line-by-line).

  ![Screen shot](https://crazytim.github.io/sublime-merge-vs-sourcetree/img/merge-003.png)

- Hide/show individual local/remote branches.

  ![Screen shot](https://crazytim.github.io/sublime-merge-vs-sourcetree/img/merge-006.png)

- Powerful find (`Ctrl`+`F`), and there is a query syntax:

  ![Screen shot](https://crazytim.github.io/sublime-merge-vs-sourcetree/img/merge-002.png)

  *(Sourcetree search is slow and uninspiring)*

- The layout adjusts well when the window is resized and everything stays in place.

  *(Occasionally the Sourcetree window can't be dragged, panels get stuck and cant be resized, and panels adjust using percentages. Also the commit message panel doesn't resize automatically like Sublime Merge).

- The graph design is nice and simple. You can collapse merged branches as well, which is nice.

  ![Screen shot](https://crazytim.github.io/sublime-merge-vs-sourcetree/img/merge-009.png)
  
- Diff view changes to 2 columns when the window is large enough.

  *(Sourcetree doesn't have this feature)*

- You can see stashes in the graph.

  *(Sourcetree doesn't have this feature)*

- Installation is dead simple.

  *(Source tree requires you to register with a BitBucket account, plus several other steps)*


### Sourcetree features that are better:

Sublime Merge can do everything Sourcetree can, well, almost...

- You can adjust the number of lines before and after a diff.

  *(Sublime Merge doesn't have this feature)*


### Sourcetree bugs that make me furious:

- Regularly crashes and needs to be reinstalled (or reboot pc), usually just after updating Microsoft Office.

  ![Screen shot](https://crazytim.github.io/sublime-merge-vs-sourcetree/img/merge-011.png)

- Regularly complains about corrupt dictionaries and asks if I want to delete them (??).

- Keeps prompting for authentication for each repo separately (very frustrating).

- Sometimes when you click on a branch it doesn't jump to it in the graph view.

So what are you waiting for? [Go and download it now!](https://www.sublimemerge.com)
# File Systems Implementation
## Own Approach

### Assignment
Write down things to be done when to implement a file system.
Take into account that you have only the operations ReadBlock() and WriteBlock() on the disk.

### Required Tasks
- What has to be done, when creating a file foo.txt?
- What has to be done, when the file size has to be increased? Especially take care if it needs additional blocks
- What has to be done if a file is read sequentially?
- What has to be done if you want to access foo.txt randomly (seek())? 
- What has to be done when the file size decreases? Especially take care if it needs fewer blocks
- What has to be done when a file is deleted?

### Procedure
1. Preparation
    1. Make teams of 4
    1. Accept the assignment (group assignment) and give your group a name having the last name of all team mates.
    1. Clone the repository on your local machine.
    1. Create a directory named <your_last_name>.md (e.g. `bauer`).
1. Think
    1. Create a markdown file named <your_last_name>.md (e.g., `bauer.md`) and store it in your directory.
    1. Jot down your ideas quickly (30 minutes). You may also do drawings and store them in your directory.
    1. Commit your file, pull, push.
1. Share
    1. Open the files of your team mates, analyse their solutions, and add remarks to an own file called with your own name (e.g., `remarks_bauer.md`). Call a mate if you don't understand things (max. 5 minutes for each).
    1. Pull push.
1. Integrate
    1. Join your team mates in a voice channel and discuss your ideas. Agree on a common solution and write it down in a new file (`final_solution/final_solution.md`).
    1. Push

### Grading Categories
#### Own Solution
| Category | Description |
| --- | --- |
| Elaboration | How detailed is the idea explained? Are all aspects well covered? Did the student think of e.g., free blocks, directories, performance considerations, etc? |
| Idea | How interesting is the solution? Does it have interesting aspects? |

#### Remarks
| Category | Description |
| --- | --- |
| Elaboration | How detailed did the student analyse the other solutions? |

#### Common Solution
| Category | Description |
| --- | --- |
| Understandable | How well understandable and how well structured is the description. Images and drawings available to support understanding? |
| Create | Quality of solution for creating a file. Is the group aware of flaws in their solution? |
| Extend | Quality of solution for extending a file. Is the group aware of flaws in their solution? |
| Sequential | Quality of solution for reading a file sequentially. Is the group aware of flaws in their solution? |
| Random | Quality of solution for navigating in a file (implementation of seek). Is the group aware of flaws in their solution? |
| Reduce | Quality of solution for reducing a file size. Is the group aware of flaws in their solution? |
| Delete | Quality of solution for deleting a file.. Is the group aware of flaws in their solution? |
| Root Dir | Is the implementation of a root directory explained? |
| General Dirs | Is the implementation of general directories explained? |
| Free Blocks | Is the management of free blocks explained? |

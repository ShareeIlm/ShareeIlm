Obsidian is a note taking app which emphasized on creating links between notes. It's like creating your own Wikipedia.

- Website and Download: [Obsidian](https://www.obsidian.md)
- For usage on Phone, Jump [[Syncing Obsidian]]

# Getting started
Download the for your device. upon running you are created by a window asking you to "Open" or "Create" a "Vault"

- A "Vault" is just another fancy name for an Obsidian folder. Right now, you might not have a Vault so go ahead and create one.
- Create a new note by:
	- Ctrl-N
	- Open the Command palette and search "Create new Note" (Ctrl-p)
- Upon executing the command, a new tab opens up with the title "Untitled". this is your file name so edit it to represent the data that is going to be in you note
- Once create, you can start writing your notes
- All the functions you do like bolding text, create a file, deleting a file, creating a heading can be executed in the command palette. It can be opened with the Ctrl-p shortcut. You should learn to get comfortable with using the command palette as expands you ability to do work.
	- You can also see various shortcuts for common functions like bolding text in the command palette

# Part 1: Learning the Syntax
You can start writing now, but your text content will not look organized enough. Obsidian uses the **Markdown syntax** which is like a programming language but for writing notes. It's easy and simple to learn the markdown syntax. Here are some of its basics:

## Headings

| Function         | Text    |
| ---------------- | ------- |
| Headings Level 1 | #       |
| Headings Level 2 | ##      |
| Headings Level 3 | ###     |
| Headings Level 4 | ####    |
| Headings Level 5 | ######  |
| Headings Level 6 | ####### |

Example:
```
# Thursday

## Morning
### Breakfast


## Evening
### Lunch

## Night
### Dinner
```
Make sure to use proper level heading and giving each heading a proper title. you can jump between these heading using the right sidebar

![](Obsidian/Obsidian%20Tutorial%20sidebar.png)

## Formatting

| Function | Text            | Shortcut |
| -------- | --------------- | -------- |
| **Bold** | `**text here**` | Ctrl-b   |
| *Italic* | `*text here*`   | Ctrl-I   |
|==Highlight== | ==text here==| - |
| > Quote | > | -|
|>> Subquote | >> | - |

```
i am **Bolded**
i am *Italicized*
i am ==highlighted==
> i am a quote
>> i am a quote inside a quote
```

### Bullets
You can demote/indent a bullet by pressing "TAB" or promote/unindent it by pressing "SHIFT-TAB"

| Function    | Text    |
| --- | --- |
| Toggle Bullet list     | -    |
| Toggle Numbered list | 1. |
| Checkbox | - [ ] |
| Ticket Checkbox | - [X] |

Example:
```
- Holidays (promoted)
	1. Sunday (demoted)
	2. Friday
	3. Saturday
- Tasks
	- [x] Get lunch 
	- [ ] Make coffee #todo
```

## Misc Syntax

| Function    | Text    |
| --- | --- |
| Spacer | ---    |
| External Links | `[Title](www.url.com)`|

```
Morning Sunrise: [link](www.youtube.com)

---

Evening Sunset: [link](www.youtube.com)
```


# Part 2: Learning the Keyboard Shortcuts
Efficiently learning to use Obsidian requires learning the keyboard shortcuts. You can head in the settings and set the shortcuts. Go to `Setting > Hotkeys`. Lets set a shortcut for headings level 1 to 3.

- Go to Settings > Hotkeys
- Search "Heading"
- Configure the below shortcuts

| Command       | Shortcut |
| ------------- | -------- |
| Set Heading 1 | Alt-1    |
| Set Heading 2 | Alt-2    |
| Set Heading 3 | Alt-3    |

- Now try these shortcuts out!
- It is recommended to set shortcuts of commands you use frequently

# Part 3: Linking
You can link notes just like on Wikipedia.org. It's best to keep each file focused on one topic. This way, it can be referenced anywhere and still make sense on its own. You can view your links by opening the global graph by pressing `Ctrl-g` or running "Open Global Graph" in the command palette `Ctrl-p`.

Syntax:
```
[[filename]]

OR

[[filename|Alternative_Name]]
```

Example: `Morning` file says
```
The [[sun]] rises during this time
```

The `Sun` file says
```
It rises in the [[Morning|morning]]
```

# Part 4: Quick Access
You can quickly access your notes by pressing `Ctrl-O` or running "Open Quick Switcher" in the command palette.

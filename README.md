# lab07
Iterators
In lab we will go over iterators, show solutions to the Iterators asked in Assignments Three and Six, and hopefully clear up some of the confusion surrounding them. Download the IteratorPractice.java into a lab07 package for code examples of when iterators are used. 

Editing
I've also put together a list of some of the shortcuts I use when I'm editing. I'll explain each binding, and give you a tutorial on it. 
 
			Windows 	Mac
* Outline		Ctrl-o		Cmd-0
* AutoComplete	Ctrl-Space	Ctrl-Space
* Delete Line	Ctrl-d		Cmd-d
* Auto-Help	Ctrl-1		Ctrl-1
* Save	Ctrl-s	Cmd-s
* Move-Line	Alt-Up/Alt-Down	Alt-Up/Alt-Down
* Duplicate		Alt+Ctrl+Up/Down	Alt+Ctrl+Up/Down
* Refractor		Alt+Shift+r	Cmd+Alt+r
* Go-to Line	Ctrl-L	Cmd-L
* Min/Max		Ctrl-M	Ctrl-M
* Switch-File	Ctrl-E	Ctrl-E
* Organize Imports	Ctrl-Shift-O	Cmd-Shift-O
 
* Move By word	Ctrl+Left/Right	Alt+Left/Right
* End Of Line	End	Cmd-Right
* Beginning Of Line	Home	Cmd-Left
* "Go Back"	Alt-Left	Cmd-[
* Go Forward	Alt-Right	Cmd-]
To finish up, we'll solve the following interview problem. I'll do some live coding to hopefully show some of the editing commands in action.
 
Given a singly linked list, modify the value of first half nodes such that :
* 1st node’s new value = the last node’s value - first node’s current value
* 2nd node’s new value = the second last node’s value - 2nd node’s current value,
and so on …
Example :
Given linked list 1 -> 2 -> 3 -> 4 -> 5,
You should return 4 -> 2 -> 3 -> 4 -> 5 as
for first node, 5 - 1 = 4
for second node, 4 - 2 = 2
Try to solve the problem using constant extra space. Use this template Solution.java to get started. 

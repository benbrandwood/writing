﻿Ben’s (and other's) laws of DevOps:
	General Principles:
		- You can do DevOps with a white-board, post it notes and a command line.
		- "Shift Left!" (RD) 
		- You build it. You Support it
		- You build it. You Test it
		- You build it. You Secure it.
		- You are creating a product! Do you know what it is?
	People:
		- Fire your test team (but if you have developers who are keen on test pipeline automation great)
		- Fire your BAs (but if you have developers who understand scenario testing languages like gherkin then great)
		- If you write tasks you do tasks
		- Constrain headcount growth. Don’t add new people until every avenue of automation has been explored. Headcount doesn’t allow for explosive growth
	Process:
		- "Agile is about getting your code creation from months to days, DevOps is about getting the deployment of that code down to days from months" (RD)
		- Agile =! DevOps. You can do DevOps on waterfall, or scrum, or Kanban. 
		- Aim for self-reliance as far as is practicable - this naturally constrains scope and keeps focus. 
		- Assume everything you own could vanish in seconds and plan accordingly.
		- Assume any one of your vendors, suppliers or partners may go bust at any time. Architect accordingly.
		- If you have full environments-as-code what does that mean for Disaster Recovery?
	Technology:
		- If it’s not in source control, it doesn’t exist
		- If it doesn’t emit logs, it doesn’t exist
		- If those logs aren’t being captured, it doesn’t exist
		- If it requires clicking or manual interaction it shouldn’t exist. 
		- Patching is boring, make it go away.
		- "Everything is boring! Make it go away" (RD)
		- Separate data from compute. Decoupling is good

Where's the intersection with DataOps?
	DataOps is still a nacent and changing view of the world. For my money this is trying to place the concepts of CI/CD into a data landscape. That's hard, there's little support or acknowledgement from the vendors, there's little in the way of tooling off the shelf, but there are some concpets

	- You know that BA you fired earlier? Yeah, get them back, but don't call them BA's call them "Information Catographers", or "Librarians". Agility is constrained by lack of understanding of the dataspace. The ability to pivot relies on deep, intuitive underdstanding of the information - backed up with good documentation!
	- How do we square the concept of testing with the data world - can we wrap TDD around SQL?!

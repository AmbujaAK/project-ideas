
**Table of Contents**

* [Generate ToC](#generate-toc)  
	* [The Challenge](#the-challenge)  
	* [Additional Notes](#additional-notes)  
	* [Example](#example)  
* [Guidelines](#guidelines)  


# Generate ToC 

**Skills Required**:  HTML, CSS and Javascript and basic familiarity (especially headers) with the Markdown format. 

## The Challenge 

**Prize:** KGISL **Bronze Badge** and upto Rs 2,500 for a working solution. Approach this individually or as a team. **Deadline: Aug 15, 2017**

- It is quite straightforward to generate a table of contents (ToC) in Microsoft Word. Take a look at this video here -  http://bit.ly/gitHubFCC 

- Given a Markdown file (https://daringfireball.net/projects/markdown/syntax#header), make  recommendations on how a table of contents (ToC) can be generated for it. 

- Specifically, codify a solution for generating a ToC for markdown files on github. Enhance the available github editor (https://help.github.com/articles/editing-files-in-your-repository/) so that the ToC can be generated/updated while editing the github repo file from within the browser. To accomplish this, there might be some setup that is required. The less setup that is required, the better. 

## Additional Notes

 - the solution must help generate **ToC** for 
	 - wiki pages (e.g https://github.com/MarkUsProject/Wiki/wiki) when the user clicks on the "Edit" button next to the green "New Page" button, on the right hand side
	 - markdown files in the repo (e.g. https://github.com/MarkUsProject/Wiki/blob/master/Admin_FAQ.md) when the user clicks on the pencil icon next to the History button on the right hand side, below the "Copy path" button
	 - gist pages (e.g. https://gist.github.com/kgashok/1be5157b5c2225b5948cc73d153bf531) when the user clicks the "Edit" button next to the "Delete" icon on the top right hand side 

## Example 

The gist page (https://gist.github.com/kgashok/1be5157b5c2225b5948cc73d153bf531) has a table of contents, which is what we need to create based on any given page (wiki, md file or gist file on **github**). 

> ![tocImage](https://files.gitter.im/kgisl/campsite/wkDQ/Screenshot-2017-07-26-at-13.45.33.png)

The **ToC** in the above image is based on the markdown code that is to be generated by the solution, and it has the format as shown below: 
```
**Table of Contents**

* [Pointers](#pointers)  
	* [Integers and Integer variables (Known)](#integers-and-integer-variables-known)  
	* [Pointers and pointer variables (Unknown)](#pointers-and-pointer-variables-unknown)  
	* [Code Quiz](#code-quiz)  
		* [Quiz 1  - Pointer basics](#quiz-1----pointer-basics)  
		* [Quiz 2  - Pointer basics](#quiz-2----pointer-basics)  
		* [Quiz 3  - Swap using Pointers](#quiz-3----swap-using-pointers)  
		* [Quiz 4  - Bug Finder](#quiz-4----bug-finder)  
		* [Quiz 5  - Printer Arithmetic](#quiz-5----printer-arithmetic)  
			* [Question 5.1](#question-51)  
			* [Question 5.2](#question-52)  
	* [What next?](#what-next)  
```


# Guidelines

- Finding existing solutions/projects/tools (open source or otherwise) and re-purposing them to achieve the below objective is highly encouraged. Don't reinvent something that is also working well. 
- Hack on something that already works but has some quirks and does not match what is exactly required 
- Simplify the problem to something that you think you can get going right away

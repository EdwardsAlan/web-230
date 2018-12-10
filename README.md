# web-231
Introduction to JavaScript
#contributors
Professor Krasso - Bellevue University 
Alan Edwards - Bellevue University 
/*
============================================
; Title:  header.js
; Author: Alan Edwards		
; Date:   9 December 2018
; Modified By: Alan Edwards
; Description: Displays a formatted header
;===========================================
*/

/**
* Params: firstName, lastName, assignment
* Response: output 
* Description: Returns a well-formatted string header
*/
exports.display = function (firstName, lastName, assignment) {
	let output = '\n' + firstName + ' ' + lastName + '\n' + assignment + '\nDate: ' + 
	new Date().toLocaleDateString('en-US')

	return output  
}

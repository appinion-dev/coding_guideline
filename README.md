Categories
* Coding Guideline
    * Web Development
	* Basic Coding Conventions
		* Basic coding should follow PSR-12 including PSR-2 .
		* All kinds of typos and spelling mistakes should be avoided at any cost. Codes should not be merged with typos and spelling mistakes and no excuses should be entertained in this case. Same thing should be applied in the database also. 
		* In addition to PSR-2 and PSR-12, all classes, variables, objects, models names should be noun or noun equivalents. All method names should start with a verb. 
		* Code uniformity should be maintained in all cases. 
		* There should be a file type wise format for file names. Ex: Controller, models, views, libraries, helpers, traits, other class names. 
		* For framework specific development, framework documentation should be followed as long as possible. If any framework documentation contradicts the above mentioned statements, it needs to be discussed and set a new one instead. 
		* Proper analysis of codes before starting to code in an existing project is mandatory. Proper analysis means noticing how the previous authors have structured the code. 
	* Git Conventions
		* Prefix common verbs in commit messages. 
		* Updating dependencies with a note. 
		* Avoid pushing to master branch directly or cloning master branch. 
		* Maintaining a change log. 
		* This repo can be followed to get a more specific idea.
	* Code Quality:
		* Variable variables should not be used
		* Functions should not be nested too deeply
		* References should not be passed to function calls
		* String literals should not be duplicated
		* Ternary operators should not be nested
		* Unused assignments should be removed
		* Local variables should not have the same name as class fields
		* Local variables should not be declared and then immediately returned or thrown
		* Class constructors should not create other objects
		* Comments should not be located at the end of lines of code
		* Lines should not end with trailing whitespaces
		* Hard-coded credentials are security-sensitive
		* Using weak hashing algorithms is security-sensitive
		* Using regular expressions is security-sensitive
		* Manual generation of session ID is security-sensitive
		* Using hardcoded IP addresses is security-sensitive
		* References used in "foreach" loops should be "unset"
		* Variables should be initialized before use
		* Array values should not be replaced unconditionally
		* Files should not contain characters before "<?php".
		* Errors should not be silenced.

		You can check out this page for more rules…….
    * Admin Panel
        * Boilerplate
        * Database
            * MySql version 5.7
    * Front End
        * Bootstrap
        * Vue JS
    * Third Party Library
* App Development
    * Language
	    * Kotlin
    * Architecture
        * MVVM
        * Jetpack
    * Ui/Ux
        * Material Design
    * Network
        * Retrofit 2
    * Third Party Library
* API Development
    * Boilerplate
    * Sails.js
    * Postman
    * JWT(Authentication)
* Git Guideline

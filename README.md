README

Goal

Create a common archive for PHP Static Analysis challenges, to test and improve the current tools available. 

Installation

Pre-requisite : one PHP version must be installed. Preferably, PHP 8.0. 

1. clone the respository at http://
2. install the dependencies with `composer require`
3. generate the tests with PHP `php scripts/generate`
4. run the tests `php scripts/run`
5. enjoy the results in the `results` folder
6. read the stats in the `stats` folder

Contribution

You can contribute by providing new tests for this archive. The more, the better. 

The test format is the following  : 

1. Find a category, in the sources dictionary. 
2. In the category, select a unique name for this source, with the scphp extension. 
3. Edit your code with the following overhead
	1. # -----------------
	2. # Name        : Name of the file
	3. # Description : Plain English explanation
	4. # PHP         : PHP version compatibility. Use MAJOR.MINOR version syntax. Add + or - to mention 'and more recent' or 'and older '.
	5. # -----------------
	2. There, the code, with opening PHP tags. It must be valid with the PHP versions specified
	3. # -----------------
	4. There, the result of the analysis : it shall include code, line, or a error code. 
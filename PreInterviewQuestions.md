# Pre-Interview Questions  
The pre-interview test has no time limit, and should be completed to the highest standard possible as this will factor into the selection process.

## Pre-requisites
1. Fork this repository to your own GitHub account
2. Clone your fork of this repository to your local computer

## Scenario 1
You need to create a nested set of folders based on the `directories.json` file.  
In each subdirectory you must create a text file named `random.txt` which contains a random number from 8-100.
You must be able to re-run the script multiple times without errors, with each run updating the random number in the previously created files.

### Success Criteria
1. Folders created in accordance with `directories.json`
2. At least one `random.txt` file created
3. All created `random.txt` files contain a random number between 8-100
4. Running the script multiple times updates the random numbers in the `random.txt` files
5. Running the script multiple times does not create new `random.txt` files
6. The script must be tested with [Pester](https://github.com/pester/Pester)
7. The script must pass by [PSScriptAnalyzer](https://github.com/PowerShell/PSScriptAnalyzer)

## Scenario 2 
You need to retrieve a count of the number of times the word `PowerShell` appears in the [PowerShell Wikipedia Page](https://en.wikipedia.org/wiki/PowerShell).
The script must also retrieve a list of links from the same page which point to the domain `microsoft.com`.
The script must generate an HTML file which contains clickable links of each URL identified for `microsoft.com`.

### Success criteria
1. Script must output a number to console reflecting the number of times the word `PowerShell` is mentioned on the page
2. Script must output an HTML file which contains clickable links of each URL identified for `microsoft.com` on the page
3. The script must be tested with [Pester](https://github.com/pester/Pester)
4. The script must pass by [PSScriptAnalyzer](https://github.com/PowerShell/PSScriptAnalyzer)

## Completion
1. Submit a Pull Request to this repository and inform the recruiter that you have completed the Pre-Interview questions

## Bonus Round
Using [appveyor.com](http://appveyor.com), automate the execution of your Pester tests and PSScriptAnalyzer.
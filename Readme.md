# Basic PowerShell Practical Interview

## Pre-requisites
1. Clone this repository to your local computer

## Scenario 1
You have a csv file containing a list of users' names incorrectly.  
You need to output a JSON file containing the users' names properly capitalised, with at least one user assigned the property "Administrator" at random.

### Acceptance Criteria

1. Valid JSON file
2. Correctly capitalised names
3. One user assigned the property administrator

## Scenario 2
You need to retrieve a list of all *running* services on a computer, including the user the service runs as.  
This needs to be output to a CSV file, with headers, but without any extraneous metadata.

### Acceptance Criteria

1. Valid CSV file
2. CSV file has headers
3. CSV file does not contain extraneous metada


## Completion Scenario
Commit each script to a new branch of this repository with an appropriate commit message and branch name based on gitflow.

### Acceptance Criteria

1. One branch per script
2. Appropriate commit message
3. Appropriate branch name


## Bonus Scenario
Create Pester tests for the first script and commit to its branch, and submit a pull request to [https://github.com/Sam-Martin/PowerShell-Interview-Practical](https://github.com/Sam-Martin/PowerShell-Interview-Practical)

### Acceptance Criteria

1. Pester tests covering randomised input to script #1
2. Committed to the scripts' branch with an appropriate commit message
3. Pull request submitted to [https://github.com/Sam-Martin/PowerShell-Interview-Practical](https://github.com/Sam-Martin/PowerShell-Interview-Practical)
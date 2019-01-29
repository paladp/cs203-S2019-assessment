# Assessment for Team-Based Project Work

## Assessment Key

* N = None
* I = Inadequate
* A = Adequate
* G = Good
* E = Excellent

## Technical Skills

### Software Development with Python

* Configuring a development environment for Python
* Running Python programs with `pyenv` and `pipenv`
* Linting Python programs with `pylint` and `flake8`
* Formatting Python programs with `black`
* Basic testing of Python programs with `pytest`
* Advanced testing of Python programs with `pytest`
* Calculating code coverage of a `pytest` test suite
* Reporting code coverage through an online provider
* Using docstrings to document a Python program
* Adopting and applying appropriate naming conventions
* Using exception handling to create a robust Python program
* Refactoring a Python program to improve its characteristics
* Debugging Python programs using logging and other methods
* Adopting and using appropriate Python language constructs

### Project Management with GitHub

* Using the issue tracker
  * N = None would indicate that someone did not use the issue tracker.
  * I = Inadequate would indicate that an issue is posted but it is either redundant or incomprehensible.
  Ex. "Ajssjdjssd"(incomprehensible) or posting that a program's main method is broken when three other people have done the same thing.
  * A = Adequate would indicate that the issue posted is neither redundant nor incomprehensible, but isn't  
  descriptive or clear.
  Ex. "Your program is broken."
  * G = Good would indicate that the issue posted is neither redundant nor incomprehensible, and is moderately
  descriptive and clear. Ex. "Your math function is broken."
  * E = Excellent would indicate that the issue posted is neither redundant nor incomprehensible, and is detailed and
  easy to understand and follow. Ex. "Your math function is broken because you forgot a semi-colon." Error
  messages from the terminal can also be incorporated. Ex "Terminal said that the function was given too
  many arguments."

* Using the GitHub flow model*
  * N = None would indicate that someone pushed directly to the master branch instead of pushing to one of the
  subbranches. Additionally, they had nonsensical commit messages, and did not create or use repository
  branches or forks correctly, and also performed incorrect merges and pull requests.  
  * I = Inadequate would indicate that forks, and repositories are made correctly. Additionally, merges and pull requests are done correctly and the commit messages can be understood, but the programmer pushed to the master branch.  Good would indicate that the issue posted is neither redundant nor incomprehensible, and is moderately
  descriptive and clear.
  * A = Adequate would indicate that the programmer correctly made subbranches and did not push to the master branch. Merge and pull requests are done correctly, commit messages can be understood. Additionally, all forks and repositories were made correctly as well.
  * E = An excellent branch would be a purposeful branch that has a descriptive label. Had strong commit
    messages, in addition to using and creating repository branches, forks, and pull request correctly.
* Creating and using a repository branch
  * N = Routinely committing edits to the master branch or not pushing to correct branches receives a none grade
  * I = Creating branches with unclear names and no descriptions will receive an inadequate grade
  * A = Branches named sensibly with unique code and descriptions that adequately describe the branch's purpose receive an adequate grade
  * G = Well documented changes to correct well-named and necessary branches will receive a good grade
  * E = Immaculately documented changes on branches that serve extremely important purposes will receive an excellent grade
* Creating and using a repository fork
  * N = Pushing to the wrong fork or making forks that serve no purpose will receive a non grade
  * I = Forks with unclear names and purposes will receive an inadequate grade
  * A = Creating and pushing to forks that are necessary to our design that have detailed annotations will receive an adequate grade
  * G = Highly detailed forks with well-kept history and well-annotated code will receive a good grade
  * E = Immaculately detailed forks with an impeccably annotated history will receive an excellent grade
* Merging a branch or a fork to another branch or fork
  * N = Not communicating changes before merging branches and forks receives a none grade
  * I = Merging with lackluster communication with the team or merging faulty code receives an inadequate grade
  * A = Communicating changes with the team and reconciling differences between code receives and adequate grade
  * G = Merging branches after extensive communication with the team receives a good grade
  * E = Immaculately detailed code and communication with the team before merging receives an excellent grade
* Creating and reviewing a pull request
  * N = no PR was made
  * I = a PR was made but does not tag the related issues it is trying to close, does not fully describe the proposed changes within the PR, and does not update documentation to reflect the changes within the PR
  * A = a PR was made that tags any related issues it is trying to close, fully describes all of the proposed changes within the PR with no review being made by a person
  * G = a PR was made that tags any related issues it is trying to close, fully describes all of the proposed changes within the PR with a review of it that partially discusses the ramifications of the PR after successfully building with Travis CI
  * E = a PR was made that tags any related issues it is trying to close, fully describes all of the proposed changes within the PR with a review of it that fully discusses the ramifications of the PR after successfully building with Travis CI
* Using appropriate commit messages*
  * N = None would indicate that the commit message was nonsensical. An example of this would be random strings of letters 'sdhjhsdjsd'.
  * I = Inadequate would indicate that the commit message wasn't nonsensical, but ultimately uninformative. An example of this would be "I am so angry" or "Please work".
  * A = Adequate would indicate that the commit message both made sense and was descriptive, to an extent. An example of this would be "X.py is broken." or "I added lines to the main method"
  * G = Good would indicate that the commit message was both clear, and moderately descriptive. "The main method
  of X.py is broken." or "created three new variables in the main method"
  * E = Excellent indicates a adequately detailed and clear commit message. "The main method isn't calling correctly" or "created three ints in the main method"


### Continuous Integration with Travis

* Setup and configure Travis CI
  * N = Fails to perform any setup and configuration of Travis CI
  * I = Setting up and configuring Travis CI which performs no checks
  * A = Sets up and configures Travis CI without performing checks on all relevant project deliverables
  * G = Sets up and configures Travis CI to perform most relevant checks on project deliverables
  * E = Correctly sets up and configures Travis CI to perform all relevant checks for project deliverables
* Perform secure releases of project deliverables
  * N = Does not utilize Travis CI when releasing project deliverables
  * I = Performs a release through Travis CI which is not secured
  * A = Performs a release through Travis CI which is mostly secured
  * G = Performs a secure release through Travis CI while failing to sign commits
  * E = Utilizes a fully-encrypted Travis CI to perform a secure release
* Create third-party integrations with Travis CI (e.g., codecov.io)
  * N = No attempt to incorporate a third party integration
  * I = Third party integrations were implemented but unsuccessful
  * A = A minority of third party integrations were implemented with many errors
  * G = A majority of the third party integrations  are successfully implemented with little to no error
  * E = All necessary third party integrations are successfully created without error
* Add README badges that show status of Travis CI builds
  * N = nothing related to badges was added to the README
  * I = an attempt was made to add a status badge for Travis CI builds but does not work or show up
  * A = a status badge for Travis CI builds is in the README but is not in an appropriate location
  * G = a status badge for Travis CI builds is in the README and is in an appropriate location but not in relation to any other status badges
  * E = a status badge for Travis CI builds is in the README and is in an appropriate location in relation to any other status badges
* Add README badges that show project characteristics (e.g., coverage and
  language)
   * N = no status badges were added besides one for the build status of Travis CI
   * I = only some of the relevant status badges were added besides one for the build status of Travis CI
   * A = all relevant status badges were added but are not in appropriate locations
   * G = all relevant status badges were added and are in an appropriate location but not in relation to each other
   * E = all relevant status badges were added and are in an appropriate location in relation to each other and a potentially present status badge for Travis CI builds

### Foundations of Software Engineering

* Requirements engineering
* Software architecture
* Software design
* Software documentation
* Programming styles
* Managing software complexity
* Mitigating software risk

## Professional Skills

### Individual

* Continuous learning about
  * Python software development
  * Project management with GitHub
  * Continuous integration with Travis
  * Foundations of software engineering
* Understanding and avoiding red flags
* Understanding and adopting best practices

### Group

* Attendance
* Deadlines
* Communication
* Participation
* Conduct
* Decisions
* Postmortems
* Conflicts
* Infractions

### Interactions

* Interaction with the customer
* Interaction with the team leaders
* Interaction with the course instructor
* Interaction with the teaching assistants

## Revision of Guides

* Revising the assessment form
* Revising the code of conduct

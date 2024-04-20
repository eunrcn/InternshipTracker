---
  layout: default.md
  title: "Ashley's Project Portfolio Page"
---

### Project: InternHub

InternHub is a desktop address book application used for teaching Software Engineering principles. The user interacts with it using a CLI, and it has a GUI created with JavaFX. It is written in Java, and has about 10 kLoC.

Given below are my contributions to the project.

* **New Feature**: Allow users to add new contacts to InternHub
  * What it does: Enables users to input information about the internships they have applied for.
  * Justification: This feature enables users to conveniently store all relevant internship details in one centralized location alongside their other contacts. This helps them stay organized and easily access internship information when needed.
  * Credits: The feature builds upon the robust foundation of AB3, optimizing the code to accommodate new parameters.

* **Code contributed**: [RepoSense link](https://nus-cs2103-ay2324s2.github.io/tp-dashboard/?search=ashleygoh1&sort=groupTitle&sortWithin=title&timeframe=commit&mergegroup=&groupSelect=groupByRepos&breakdown=true&checkedFileTypes=docs~functional-code~test-code~other&since=2024-02-23&tabOpen=false)

* **Project management**:
  * Managed releases `v1.3` (1 releases) on GitHub

* **Enhancements to existing features**:
  * Enhanced test cases for existing features, achieving a test coverage of 78.571% (Pull requests [\#9](https://github.com/AY2324S2-CS2103T-F14-1/tp/pull/9), [\#48](https://github.com/AY2324S2-CS2103T-F14-1/tp/pull/48)).
  * Designed an intuitive UI for the PersonCard to display essential information only (Pull request [\#71](https://github.com/AY2324S2-CS2103T-F14-1/tp/pull/71)).
  * Added descriptive labels to the UI PersonCard (Pull request [\#71](https://github.com/AY2324S2-CS2103T-F14-1/tp/pull/71)).
  * Implemented a '-' display in the UI when the note or interview date is empty (Pull request [\#83](https://github.com/AY2324S2-CS2103T-F14-1/tp/pull/83)).
  * Updated the compareInterviewDates() function in Person.java to prevent app crashes (Pull request [\#190](https://github.com/AY2324S2-CS2103T-F14-1/tp/pull/190)).

* **Documentation**:
  * User Guide:
    * Added documentation for the features `add` and `edit` [\#16](https://github.com/AY2324S2-CS2103T-F14-1/tp/pull/16), [\#104](https://github.com/AY2324S2-CS2103T-F14-1/tp/pull/104)
    * Added documentation for the features `delete` [\#108](https://github.com/AY2324S2-CS2103T-F14-1/tp/pull/108)
    * Added documentation related to bugs [\#189](https://github.com/AY2324S2-CS2103T-F14-1/tp/pull/189)
    * Added a new section 'understanding each parameter' [\#189](https://github.com/AY2324S2-CS2103T-F14-1/tp/pull/189)
    * Updated images [\#200](https://github.com/AY2324S2-CS2103T-F14-1/tp/pull/200)

  * Developer Guide:
    * Update DG to include add command feature description [\#79](https://github.com/AY2324S2-CS2103T-F14-1/tp/pull/79)
    * Added more manual test cases, update implementation for add command and add planned enhancement [\#206](https://github.com/AY2324S2-CS2103T-F14-1/tp/pull/206)
    * Add `add`, `edit`, `filter` activity diagrams, `filter` sequence diagram [\#221](https://github.com/AY2324S2-CS2103T-F14-1/tp/pull/221)

* **Community**:
  * PRs reviewed (with non-trivial review comments): [\#78](https://github.com/AY2324S2-CS2103T-F14-1/tp/pull/78#discussion_r1540881872), [\#32](), [\#70](https://github.com/AY2324S2-CS2103T-F14-1/tp/pull/70#discussion_r1541268786)
  * Reported bugs and suggestions for other teams in the class (examples: [1](https://github.com/ashleygoh1/CS2103-T-PE-Dry-run/issues/1), [2](https://github.com/ashleygoh1/CS2103-T-PE-Dry-run/issues/2), [3](https://github.com/ashleygoh1/CS2103-T-PE-Dry-run/issues/3),
  [4](https://github.com/ashleygoh1/CS2103-T-PE-Dry-run/issues/4), 
  [5](https://github.com/ashleygoh1/CS2103-T-PE-Dry-run/issues/5),
  [6](https://github.com/ashleygoh1/CS2103-T-PE-Dry-run/issues/6),
  [7](https://github.com/ashleygoh1/CS2103-T-PE-Dry-run/issues/7),
  [8](https://github.com/ashleygoh1/CS2103-T-PE-Dry-run/issues/8),
  [9](https://github.com/ashleygoh1/CS2103-T-PE-Dry-run/issues/9), 
  [10](https://github.com/ashleygoh1/CS2103-T-PE-Dry-run/issues/10))

* **Challenges and Problem Solving**:
  * I was tasked with adding new fields to the person model, which required extensive changes throughout the project. This involved creating classes for the additional fields and test cases for each one. Additionally, I had to modify all existing test cases to accommodate the new fields. Initially, I underestimated the complexity of this task, and upon running the code, I encountered many errors, with over 20% of all test cases failing. Instead of attempting to edit everything at once, I broke down the errors into smaller, manageable chunks. This approach allowed me to test each change as I progressed, identifying errors early and minimizing debugging efforts. After two days of diligent work, I successfully updated the code, passed all test cases, and improved the code coverage from 75.26% to 78.571%.

  * During a pull request (PR) submission, I created a PR at the same time as one teammate.
    I merged my teammate's PR first and as I tried to merge my PR, there was merge conflict.
    I was panicking as I was accustomed to resolving conflicts on the GitHub website and this conflict was too complex and required resolution on my local machine. Maintaining composure, I communicated the issue with my team members. Thankfully, one of my team members was able to resolve the merge conflict by pulling the latest changes from the main branch to her local repository, manually resolving the conflict using a code editor, before successfully merging the PR without further issues.

* **Tools**:
  * Configured codecov for the team repository.
  * Set up UserGuide.md and DeveloperGuide.md.
  * Set up the team's GitHub repository.



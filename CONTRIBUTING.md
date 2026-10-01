All contributions, bug reports, bug fixes, documentation improvements, enhancements, and ideas are welcome.
Contributing
When contributing a major change to this repository, please first discuss the change you wish to make via an issue or via Slack in the #racial-justice-legit-info channel in the Call for Code Slack workspace. Minor issues can simply be addressed by sending by a pull request.

All pull requests will require you to ensure the change is certified via the Developer Certificate of Origin (DCO). The DCO is a lightweight way for contributors to certify that they wrote or otherwise have the right to submit the code they are contributing to the project.

Please note we have a Code of Conduct, please follow it in all your interactions with the project and its community.
Coding Standards
This project adheres to the PEP 8 Python Coding Style Guidelines, Django naming conventions, and other standards. See STYLE.md for details.

Programming Languages
Scripts are written for "bash" shell. Python code is written at the Python 3.6 level.

Managing Dependencies
Install or uninstall all dependencies using these commands while you are in the pipenv shell:

(cfc) $ pipenv install <program>"
(cfc) $ pipenv lock -r > requirements.txt"
The pipfile, pipfile.lock and requirements.txt will be part of the git commit/pull-request to be reviewed.

Pull Request Process
Fork the repository.
Commit your changes to your fork.
Submit a pull request. Don't forget to add yourself in the Authors file!
Handle any feedback before the request is merged.
Accept our sincere Thank You!
Code of Conduct
Our Pledge
In the interest of fostering an open and welcoming environment, we as contributors and maintainers pledge to making participation in our project and our community a harassment-free experience for everyone, regardless of age, body size, disability, ethnicity, gender identity and expression, level of experience, nationality, personal appearance, race, religion, or sexual identity and orientation.

Our Standards
Examples of behavior that contributes to creating a positive environment include:

Using welcoming and inclusive language
Being respectful of differing viewpoints and experiences
Gracefully accepting constructive criticism
Focusing on what is best for the community
Showing empathy towards other community members
Examples of unacceptable behavior by participants include:

The use of sexualized language or imagery and unwelcome sexual attention or advances
Trolling, insulting/derogatory comments, and personal or political attacks
Public or private harassment
Publishing others' private information, such as a physical or electronic address, without explicit permission
Other conduct which could reasonably be considered inappropriate in a professional setting
Our Responsibilities
Project maintainers are responsible for clarifying the standards of acceptable behavior and are expected to take appropriate and fair corrective action in response to any instances of unacceptable behavior.

Project maintainers have the right and responsibility to remove, edit, or reject comments, commits, code, wiki edits, issues, and other contributions that are not aligned to this Code of Conduct, or to ban temporarily or permanently any contributor for other behaviors that they deem inappropriate, threatening, offensive, or harmful.

Scope
This Code of Conduct applies both within project spaces and in public spaces when an individual is representing the project or its community. Examples of representing a project or community include using an official project e-mail address, posting via an official social media account, or acting as an appointed representative at an online or offline event. Representation of a project may be further defined and clarified by project maintainers.

Enforcement
Instances of abusive, harassing, or otherwise unacceptable behavior may be reported by contacting the project team on Slack in the #racial-justice-legit-info channel.

All complaints will be reviewed and investigated and will result in a response that is deemed necessary and appropriate to the circumstances. The project team is obligated to maintain confidentiality with regard to the reporter of an incident.Further details of specific enforcement policies may be posted separately.

Project maintainers who do not follow or enforce the Code of Conduct in good faith may face temporary or permanent repercussions as determined by other members of the project's leadership.

Contributing to OpenEEW
OpenEEW is an open source project and we are always happy to receive contributions from our community. You can contribute in different ways:

Writing tutorials and blog posts
Improving the documentation
Submitting bug reports and feature requests
Forking this repository and submitting a pull request
Hosting a seismic sensor to expand the network (send us an email at hello@openeew.com)
Please read our contributing guide here.

Technical Steering Committee (TSC)
The TSC will be responsible for all technical oversight of the OpenEEW project. Participation in the Project through becoming a Contributor and Committer is open to anyone.

The TSC may (1) establish work flow procedures for the submission, approval, and closure/archiving of projects, (2) set requirements for the promotion of Contributors to Committer status, as applicable, and (3) amend, adjust, refine and/or eliminate the roles of Contributors, and Committers, and create new roles, and publicly document any TSC roles, as it sees fit.

Responsibilities
The TSC will be responsible for all aspects of oversight relating to the Project, which may include:

Coordinating the technical direction of the Project.
Approving project or system proposals (including, but not limited to, incubation, deprecation, and changes to a sub-project’s scope).
Organizing sub-projects and removing sub-projects.
Creating sub-committees or working groups to focus on cross-project technical issues and requirements.
Appointing representatives to work with other open source or open standards communities.
Establishing community norms, workflows, issuing releases, and security issue reporting policies.
Approving and implementing policies and processes for contributing.
The TSC voting members are initially the Project’s Committers. At the inception of the project, the Committers of the Project will be as set forth within the CONTRIBUTING file within the Project’s code repository. The TSC may choose an alternative approach for determining the voting members of the TSC, and any such alternative approach will be documented in this CONTRIBUTING file. Any meetings of the Technical Steering Committee are intended to be open to the public, and can be conducted electronically, via teleconference, or in person.

TSC Voting
While the Project aims to operate as a consensus-based community, if any TSC decision requires a vote to move the Project forward, the voting members of the TSC will vote on a one vote per voting member basis.

Quorum for TSC meetings requires at least fifty percent of all voting members of the TSC to be present. The TSC may continue to meet if quorum is not met but will be prevented from making any decisions at the meeting.

Reporting Bugs
This section guides you through submitting a bug report for Atom. Following these guidelines helps maintainers and the community understand your report 📝, reproduce the behavior 💻 💻, and find related reports 🔎.

Before creating bug reports, please check this list as you might find out that you don't need to create one. When you are creating a bug report, please include as many details as possible. Fill out the required template, the information it asks for helps us resolve issues faster.

Note: If you find a Closed issue that seems like it is the same thing that you're experiencing, open a new issue and include a link to the original issue in the body of your new one.

Before Submitting A Bug Report
Check the debugging guide. You might be able to find the cause of the problem and fix things yourself. Most importantly, check if you can reproduce the problem in the latest version of Atom, if the problem happens when you run Atom in safe mode, and if you can get the desired behavior by changing Atom's or packages' config settings.
Check the faq and the discussions for a list of common questions and problems.
Determine which repository the problem should be reported in.
Perform a cursory search to see if the problem has already been reported. If it has and the issue is still open, add a comment to the existing issue instead of opening a new one.
How Do I Submit A (Good) Bug Report?
Bugs are tracked as GitHub issues. After you've determined which repository your bug is related to, create an issue on that repository and provide the following information by filling in the template.

Explain the problem and include additional details to help maintainers reproduce the problem:

Use a clear and descriptive title for the issue to identify the problem.
Describe the exact steps which reproduce the problem in as many details as possible. For example, start by explaining how you started Atom, e.g. which command exactly you used in the terminal, or how you started Atom otherwise. When listing steps, don't just say what you did, but explain how you did it. For example, if you moved the cursor to the end of a line, explain if you used the mouse, or a keyboard shortcut or an Atom command, and if so which one?
Provide specific examples to demonstrate the steps. Include links to files or GitHub projects, or copy/pasteable snippets, which you use in those examples. If you're providing snippets in the issue, use Markdown code blocks.
Describe the behavior you observed after following the steps and point out what exactly is the problem with that behavior.
Explain which behavior you expected to see instead and why.
Include screenshots and animated GIFs which show you following the described steps and clearly demonstrate the problem. If you use the keyboard while following the steps, record the GIF with the Keybinding Resolver shown. You can use this tool to record GIFs on macOS and Windows, and this tool or this tool on Linux.
If you're reporting that Atom crashed, include a crash report with a stack trace from the operating system. On macOS, the crash report will be available in Console.app under "Diagnostic and usage information" > "User diagnostic reports". Include the crash report in the issue in a code block, a file attachment, or put it in a gist and provide link to that gist.
If the problem is related to performance or memory, include a CPU profile capture with your report.
If Chrome's developer tools pane is shown without you triggering it, that normally means that you have a syntax error in one of your themes or in your styles.less. Try running in Safe Mode and using a different theme or comment out the contents of your styles.less to see if that fixes the problem.
If the problem wasn't triggered by a specific action, describe what you were doing before the problem happened and share more information using the guidelines below.
Provide more context by answering these questions:

Can you reproduce the problem in safe mode?
Did the problem start happening recently (e.g. after updating to a new version of Atom) or was this always a problem?
If the problem started happening recently, can you reproduce the problem in an older version of Atom? What's the most recent version in which the problem doesn't happen? You can download older versions of Atom from the releases page.
Can you reliably reproduce the issue? If not, provide details about how often the problem happens and under which conditions it normally happens.
If the problem is related to working with files (e.g. opening and editing files), does the problem happen for all files and projects or only some? Does the problem happen only when working with local or remote files (e.g. on network drives), with files of a specific type (e.g. only JavaScript or Python files), with large files or files with very long lines, or with files in a specific encoding? Is there anything else special about the files you are using?
Include details about your configuration and environment:

Which version of Atom are you using? You can get the exact version by running atom -v in your terminal, or by starting Atom and running the Application: About command from the Command Palette.
What's the name and version of the OS you're using?
Are you running Atom in a virtual machine? If so, which VM software are you using and which operating systems and versions are used for the host and the guest?
Which packages do you have installed? You can get that list by running apm list --installed.
Are you using local configuration files config.cson, keymap.cson, snippets.cson, styles.less and init.coffee to customize Atom? If so, provide the contents of those files, preferably in a code block or with a link to a gist.
Are you using Atom with multiple monitors? If so, can you reproduce the problem when you use a single monitor?
Which keyboard layout are you using? Are you using a US layout or some other layout?
Suggesting Enhancements
This section guides you through submitting an enhancement suggestion for Atom, including completely new features and minor improvements to existing functionality. Following these guidelines helps maintainers and the community understand your suggestion 📝 and find related suggestions 🔎.

Before creating enhancement suggestions, please check this list as you might find out that you don't need to create one. When you are creating an enhancement suggestion, please include as many details as possible. Fill in the template, including the steps that you imagine you would take if the feature you're requesting existed.

Before Submitting An Enhancement Suggestion
Check the debugging guide for tips — you might discover that the enhancement is already available. Most importantly, check if you're using the latest version of Atom and if you can get the desired behavior by changing Atom's or packages' config settings.
Check if there's already a package which provides that enhancement.
Determine which repository the enhancement should be suggested in.
Perform a cursory search to see if the enhancement has already been suggested. If it has, add a comment to the existing issue instead of opening a new one.
How Do I Submit A (Good) Enhancement Suggestion?
Enhancement suggestions are tracked as GitHub issues. After you've determined which repository your enhancement suggestion is related to, create an issue on that repository and provide the following information:

Use a clear and descriptive title for the issue to identify the suggestion.
Provide a step-by-step description of the suggested enhancement in as many details as possible.
Provide specific examples to demonstrate the steps. Include copy/pasteable snippets which you use in those examples, as Markdown code blocks.
Describe the current behavior and explain which behavior you expected to see instead and why.
Include screenshots and animated GIFs which help you demonstrate the steps or point out the part of Atom which the suggestion is related to. You can use this tool to record GIFs on macOS and Windows, and this tool or this tool on Linux.
Explain why this enhancement would be useful to most Atom users and isn't something that can or should be implemented as a community package.
List some other text editors or applications where this enhancement exists.
Specify which version of Atom you're using. You can get the exact version by running atom -v in your terminal, or by starting Atom and running the Application: About command from the Command Palette.
Specify the name and version of the OS you're using.
Your First Code Contribution
Unsure where to begin contributing to Atom? You can start by looking through these beginner and help-wanted issues:

Beginner issues - issues which should only require a few lines of code, and a test or two.
Help wanted issues - issues which should be a bit more involved than beginner issues.
Both issue lists are sorted by total number of comments. While not perfect, number of comments is a reasonable proxy for impact a given change will have.

If you want to read about using Atom or developing packages in Atom, the Atom Flight Manual is free and available online. You can find the source to the manual in atom/flight-manual.atom.io.

Local development
Atom Core and all packages can be developed locally. For instructions on how to do this, see the following sections in the Atom Flight Manual:

Hacking on Atom Core
Contributing to Official Atom Packages
Pull Requests
The process described here has several goals:

Maintain Atom's quality
Fix problems that are important to users
Engage the community in working toward the best possible Atom
Enable a sustainable system for Atom's maintainers to review contributions
Please follow these steps to have your contribution considered by the maintainers:

Follow all instructions in the template
Follow the styleguides
After you submit your pull request, verify that all status checks are passing
What if the status checks are failing?
While the prerequisites above must be satisfied prior to having your pull request reviewed, the reviewer(s) may ask you to complete additional design work, tests, or other changes before your pull request can be ultimately accepted.
Styleguides
Git Commit Messages
Use the present tense ("Add feature" not "Added feature")
Use the imperative mood ("Move cursor to..." not "Moves cursor to...")
Limit the first line to 72 characters or less
Reference issues and pull requests liberally after the first line
When only changing documentation, include [ci skip] in the commit title
Consider starting the commit message with an applicable emoji:
🎨 :art: when improving the format/structure of the code
🐎 :racehorse: when improving performance
🚱 :non-potable_water: when plugging memory leaks
📝 :memo: when writing docs
🐧 :penguin: when fixing something on Linux
🍎 :apple: when fixing something on macOS
🏁 :checkered_flag: when fixing something on Windows
🐛 :bug: when fixing a bug
🔥 :fire: when removing code or files
💚 :green_heart: when fixing the CI build
✅ :white_check_mark: when adding tests
🔒 :lock: when dealing with security
⬆️ :arrow_up: when upgrading dependencies
⬇️ :arrow_down: when downgrading dependencies
👕 :shirt: when removing linter warnings
JavaScript Styleguide
All JavaScript code is linted with Prettier.

Prefer the object spread operator ({...anotherObj}) to Object.assign()
Inline exports with expressions whenever possible
// Use this:
export default class ClassName {

}

// Instead of:
class ClassName {

}
export default ClassName
Place requires in the following order:
Built in Node Modules (such as path)
Built in Atom and Electron Modules (such as atom, remote)
Local Modules (using relative paths)
Place class properties in the following order:
Class methods and properties (methods starting with static)
Instance methods and properties
Avoid platform-dependent code
CoffeeScript Styleguide
Set parameter defaults without spaces around the equal sign
clear = (count=1) -> instead of clear = (count = 1) ->
Use spaces around operators
count + 1 instead of count+1
Use spaces after commas (unless separated by newlines)
Use parentheses if it improves code clarity.
Prefer alphabetic keywords to symbolic keywords:
a is b instead of a == b
Avoid spaces inside the curly-braces of hash literals:
{a: 1, b: 2} instead of { a: 1, b: 2 }
Include a single line of whitespace between methods.
Capitalize initialisms and acronyms in names, except for the first word, which should be lower-case:
getURI instead of getUri
uriToOpen instead of URIToOpen
Use slice() to copy an array
Add an explicit return when your function ends with a for/while loop and you don't want it to return a collected array.
Use this instead of a standalone @
return this instead of return @
Place requires in the following order:
Built in Node Modules (such as path)
Built in Atom and Electron Modules (such as atom, remote)
Local Modules (using relative paths)
Place class properties in the following order:
Class methods and properties (methods starting with a @)
Instance methods and properties
Avoid platform-dependent code
Specs Styleguide
Include thoughtfully-worded, well-structured Jasmine specs in the ./spec folder.
Treat describe as a noun or situation.
Treat it as a statement about state or how an operation changes state.

How to contribute to Ruby on Rails
Did you find a bug?
Do not open up a GitHub issue if the bug is a security vulnerability in Rails, and instead refer to our security policy.

Ensure the bug was not already reported by searching on GitHub under Issues.

If you're unable to find an open issue addressing the problem, open a new one. Be sure to include a title and clear description, as much relevant information as possible, and a code sample or an executable test case demonstrating the expected behavior that is not occurring.

If possible, use the relevant bug report templates to create the issue. Simply copy the content of the appropriate template into a .rb file, make the necessary changes to demonstrate the issue, and paste the content into the issue description:

Active Record (models, encryption, database) issues
Active Record Migrations issues
Action View (views, helpers) issues
Active Job issues
Active Storage issues
Action Mailer issues
Action Mailbox issues
Action Pack (controllers, routing) issues
Generic template for other issues
For more detailed information on submitting a bug report and creating an issue, visit our reporting guidelines.

Did you write a patch that fixes a bug?
Open a new GitHub pull request with the patch.

Ensure the PR description clearly describes the problem and solution. Include the relevant issue number if applicable.

Before submitting, please read the Contributing to Ruby on Rails guide to know more about coding conventions and benchmarks.

Did you fix whitespace, format code, or make a purely cosmetic patch?
Changes that are cosmetic in nature and do not add anything substantial to the stability, functionality, or testability of Rails will generally not be accepted (read more about our rationales behind this decision).

Do you intend to add a new feature or change an existing one?
Suggest your change in the rubyonrails-core forum and start writing code.

Do not open an issue on GitHub until you have collected positive feedback about the change. GitHub issues are primarily intended for bug reports and fixes.

We generally reject changes to Active Support core extensions. Those changes should be proposed in the Ruby issue tracker instead, as we don't want to conflict with future versions of Ruby.

Do you have questions about the source code?
Ask any question about how to use Ruby on Rails in the rubyonrails-talk mailing list.
Do you want to contribute to the Rails documentation?
Please read Contributing to the Rails Documentation.
Ruby on Rails is a volunteer effort. We encourage you to pitch in and join the team!

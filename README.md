[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=18363898&assignment_repo_type=AssignmentRepo)
# SE_Day1
Software Engineering Day1 Assignment

#Part 1: Introduction to Software Engineering

Explain what software engineering is and discuss its importance in the technology industry.

Software engineering is a branch of computer science used to develop, test, and maintain software.
Reliability- it ensures software performs as expected without bias, especially for critical applications like healthcare  and finance. 
Efficiency - it helps optimize developer workflow while maintaining high-quality standards.
 Scalability and flexibility - This ensures the system can handle an increased load without affecting performance.
 security - implement protection practice like authentication, authorization and encryption to secure users information.
 
Identify and describe at least three key milestones in the evolution of software engineering.

mastering complexity
As software systems grew more complex, early software engineers struggled with "spaghetti code"—unstructured and difficult-to-maintain programs. The structured programming paradigm emerged to address this:
Key Development: Edsger Dijkstra introduced structured programming principles and advocated for the elimination of the "goto" statement.
Impact: This led to more readable, maintainable, and modular code using constructs like loops, conditionals, and functions.
Example: The rise of procedural languages like C, Pascal, and Fortran, which enforced structured programming.

Mastering process
As software projects grew in scale, engineers realized the need for systematic processes to manage development efficiently. This led to the formalization of software development life cycles (SDLCs) and methodologies:

Key Development: The rise of structured methodologies such as Waterfall, Spiral, and later Agile to improve project management.
Impact: Defined phases like requirements analysis, design, coding, testing, and maintenance, reducing failures and improving quality.
Example: The Agile Manifesto (2001) revolutionized software engineering with iterative, customer-focused development, leading to frameworks like Scrum and Kanban.

Mastering machine
Early software development was limited to low-level programming languages (assembly and machine code), making coding tedious and error-prone. The evolution of high-level programming languages and automation tools helped bridge the gap between human thinking and machine execution.

Key Development: Creation of languages like Fortran (1957), Lisp (1958), COBOL (1959), C (1972), and Java (1995) that improved abstraction and automation.
Impact: Enabled faster development, better portability, and higher productivity, reducing dependence on hardware-specific coding.
Example: Modern software engineering benefits from compilers, interpreters, and AI-driven tools like GitHub Copilot, which automate coding tasks.


List and briefly explain the phases of the Software Development Life Cycle.
planning - identify the software requirement or purpose and scope.
requirement analysis - identify the final user specification. 
design - building the framework. 
coding - converting software design into tangible code.
testing - examine the software for any bugs and glitches


Compare and contrast the Waterfall and Agile methodologies. Provide examples of scenarios where each would be appropriate.
waterfall methodology - Linear and sequential, each phase is completed before moving on. 
- there is Low flexibility,
 changes are hard to incorporate once a phase is complete.
 - Customer feedback comes late after the product is developed.
 - Testing is done at the end of the development process.


agile methodology - Iterative and incremental, with multiple cycles (sprints). 
- High flexibility, adapts to changing requirements. 
- Regular customer feedback is incorporated into every sprint. 
- Testing is continuous and done after each iteration.


Describe the roles and responsibilities of a Software Developer, a Quality Assurance Engineer, and a Project Manager in a software engineering team.

Software Developer - developing applications, programs, and systems using programming languages and frameworks.
 - maintaining and updating software to keep it functional. 
- collaborating with other team members to ensure best practices when developing software.
 - Report to the project manager about the progress of software development.
Quality Assurance Engineer - collaborate with stakeholders to understand and clarify software requirements.
 - create development standards and procedures for the programmers to follow
 - confirm that the software meets the requirements before deployment. 
- analyze the product to identify bugs and suggest changes to make them more efficient. 
- develop and execute automation scripts using open-source tools.
Project Manager - assembles and leads the software development team.
 - discuss the project and its requirements with the client and software developers.
 - create a blueprint for the project.
 - Track and communicate information regarding the project milestone.
 - deliver the complete software to the client and regularly check its performance.

Discuss the importance of Integrated Development Environments (IDEs) and Version Control Systems (VCS) in the software development process. Give examples of each.

An integrated development environment (IDE) is a software platform that facilitates the creation of other software applications by providing a space to write, compile, and debug code, sometimes with value-adding tools that reduce development efforts. eg Visual Studio Code (VSCode)
importance:
Programming languages have rules for how statements must be structured. Because an IDE knows these rules, it contains many intelligent features for automatically writing or editing the source code.
An IDE can format the written text by automatically making some words bold or italic or by using different font colors. These visual cues make the source code readable and give instant feedback about accidental syntax errors.
An IDE can suggest completing a code statement when the developer begins typing.
IDEs increase programmer productivity by performing repeatable development tasks that are typically part of every code change. An IDE carries out The following examples of regular coding tasks.
An IDE compiles or converts the code into a simplified language that the operating system can understand. - Some programming languages implement just-in-time compiling, in which the IDE converts human-readable code into machine code from within the application.
The IDE allows developers to automate unit tests locally before integrating the software with other developers' code and running more complex integration tests.
A debugging IDE enables the developer to step through the code, line by line, as it runs and inspects code behavior. IDEs also integrate several debugging tools that highlight bugs caused by human error in real time, even as the developer is typing.

Version Control Systems (VCS) - are software tools that help software teams manage changes to source code over time. eg Git
importance:
Collaboration: Enables multiple developers to work on the same codebase without conflicts.
Change Tracking: Records detailed history of changes, allowing easy analysis of each modification. 
-Branching and Merging: Supports creating branches for new features and merging them back into the main code.
Error Recovery: Allows reverting to previous versions if new changes introduce errors


What are some common challenges faced by software engineers? Provide strategies to overcome these challenges.

-rapid technological advancement places considerable pressure on software engineers to stay current.
 Solution: adopt continuous learning practices and use agile methodologies to adapt to emerging trends, keeping their skills sharp in an ever-evolving industry. -
Time Constraints - Software engineering is demanding and time-intensive, often requiring engineers to work under high pressure to meet tight deadlines.
 Solution: adopt agile methodologies, such as Scrum, to streamline workflows by dividing large projects into manageable sprints 
-Limited Infrastructure - limited high-performance software engineering tools, computing platforms, and inefficient data storage architectures. 
 Solution: Software engineers must rely heavily on a robust infrastructure to perform their jobs effectively.
Changing Software Requirements - Software requirements are often dynamic and subject to frequent changes, making it challenging for engineers to design and develop solutions that meet users' needs while accounting for future updates and bug fixes. 
Solution: engineers can adopt approaches like agile development, which emphasizes iterative progress and adaptability, and modular design, which enables flexibility by breaking systems into manageable, independent components.
Software Security - Programming secure software is a complex and challenging task. 
Solution: research ways to defend against hacking, malware, phishing, insider and third-party threats
Software Accessibility and Usability - Overly complex software can frustrate or confuse users. 
Solution: Use scalable architecture and emphasize reliability.


Explain the different types of testing (unit, integration, system, and acceptance) and their importance in software quality assurance.

Unit tests - are close to the source of an application; they consist of testing individual methods and functions of the classes, components, or modules used by your software. - It ensures that each unit performs its intended function correctly and is isolated from other components.
 Integration tests - verify that your application's different modules or services work well together.
 - Help to ensure data flows smoothly between modules and interfaces and works as expected.
 System testing -Focus on the entire software system as a whole, including all functionalities and interactions.
 -It helps to verify that the system meets all functional and non-functional requirements, including performance, usability, and security.
Acceptance tests - are formal tests that verify if a system satisfies business requirements. They require the entire application to run while testing and focus on replicating user behaviors. 
- Whether the software meets the end-user's needs and is ready for deployment.


#Part 2: Introduction to AI and Prompt Engineering


Define prompt engineering and discuss its importance in interacting with AI models.

prompt engineering  is the process of guiding generative AI solutions to generate desired outputs.
Importance:
Improved user experience - Prompt engineering makes it easy for users to obtain relevant results in the first prompt. It helps mitigate bias that may be present from existing human bias in the large language models’ training data.
Increased flexibility - A prompt engineer can create prompts with domain-neutral instructions highlighting logical links and broad patterns.
developer control - Prompt engineering gives developers more control over users' interactions with the AI. Effective prompts provide intent and establish context to the large language models. Provide an example of a vague prompt and then improve it by making it clear, specific, and concise.



Provide an example of a vague prompt and then improve it by making it clear, specific, and concise. Explain why the improved prompt is more effective.

Tell me about data science.

Improved Prompt:
Provide a brief overview of data science, including its key components (such as data cleaning, machine learning, and data visualization) and a real-world example of its application in business.

More Specific – Instead of a broad request, the improved prompt clarifies what aspects of data science should be covered.
More Concise – It avoids unnecessary words while still conveying clear instructions.
More Actionable – It provides a clear direction for the response by mentioning specific topics and requiring a real-world example.



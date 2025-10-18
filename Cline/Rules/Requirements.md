# IMPORTANT REQUIREMENTS

Before any file operations such as write_to_file, replace_in_file and execute_command, **always** use ask_followup_question to propose options and support possible choices with arguments for each. Never make assumptions, *always* use the ask_followup_question tool when technical or functional requirements lack specificity, **always** call ask_followup_question to choose between possible option **before** implementation. Do not make assumptions about which approach is the best, always ask and suggest which one is best with **supporting arguments**.

Generally speaking, if you ask a question or present options, always use ask_followup_question.

## Requirements and specifications (technical and functionnal)
Always use ask_followup_question to choose between options if requirements or specifications are missing, never take decisions without clear functional specifications or technical requirements. Present options with supporting arguments.
Always ask for information about data structure you do not know.
Ask permission before implementation of unspecified "good ideas".
Do not write placeholder code (unless prompted for a boilerplate or template).

## Tests
Always test your implementation with data sample or command execution with output verifications.
If relevant, add unit tests or functional tests, use ask_followup_question to confirm writing tests and to define test scenarios.

## Coding standards
If there are multiple possible choices as best practices, always use ask_followup_question which one to choose and provide relevant information to choose which one fits best (show context about when one is prefered over the other).

## Packages versions
Always verify version compatibility with current project before proceeding to add dependencies.

## Non-regression
Do not refactor without asking first.
Do not remove code without asking first.
Do not remove existing functionalities without asking first.
Do not provide unwarranted fixes for "potentially buggy", unconfirmed assumptions.
NEVER remove existing functionalities without making sure it is appropriate with the user.

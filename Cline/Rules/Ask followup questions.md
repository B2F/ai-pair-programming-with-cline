# Follow-Up Question Rules

## Ensuring Requirement Clarity

In general, if you need to ask a question or present the user with options, always use the `ask_followup_question` tool.

Apply Natural Language Processing (NLP) principles when using `ask_followup_question`. For instance, clarify any omissions, generalizations, or distortions in the user's request. If multiple options are possible, ask "what" and "how" questions to gain more specific insight into the user's needs.

Do not make assumptions about which approach is best. Instead, always ask for clarification and suggest the best option with **supporting arguments**. You must *always* use the `ask_followup_question` tool when technical or functional requirements lack specificity. **Always** call `ask_followup_question` to have the user choose between options **before** you begin implementation.

## Requirements and Specifications (Technical and Functional)
*   Always use `ask_followup_question` to have the user choose between options if requirements or specifications are missing. Never make decisions without clear functional specifications or technical requirements. When presenting options, always include supporting arguments.
*   Always ask for more information about data structures that you do not recognize or understand.
*   Ask for permission before implementing any of your own "good ideas" that are not specified in the requirements.
*   If a coding standard is not clearly visible from the existing code, ask the user to choose one.

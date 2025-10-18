# CLINE LOGS WORKFLOW

When this workflow is called, update the log file (cline-logs.md or the file specified, create the file if it doesn't exist), using the following structure:

    # FEATURES LIST

    *System instructions*:
    List implemented project features under this section.
    If we update a pre-existing feature specifications during another task, update its description.
    Track files context within a "files: " line below each feature description.
    Suffix [✔] automatically after the title when the feature is completed.

    # TECHNICAL ARCHITECTURE

    *System instructions*:
    Track all relevant architectural decisions specific to this project under "# TECHNICAL ARCHITECTURE".

    # TECHNICAL DEBTS

    *System instructions*:
    If any hacks are found or significative improvements can be made to improve maintainability or security, note them under "#TECHNICAL DEBTS".

Do not include *System instructions* in the output.

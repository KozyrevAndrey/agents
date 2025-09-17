description: Create a git commit with clean message (no Claude credentials or co-authored-by)
allowed-tools:

    bash argument-hint: "[commit message]"

Please create a git commit with the following requirements:

    Use the provided commit message: $ARGUMENTS
    Do NOT include any Claude credentials or authentication information
    Do NOT include any "Co-authored-by" lines
    Keep the commit message clean and professional
    Stage any unstaged changes before committing

If no commit message is provided, create an appropriate commit message based on the staged changes.

Execute the git commit command following these guidelines.


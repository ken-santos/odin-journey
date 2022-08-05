# My-Odin-Journey
* A storage of my knowledge on web development.

# 7 rules of a great Git commit message.
- Source: https://cbea.ms/git-commit/#separate

1. Separate subject from body with a blank line.
    * The first line will be treated as the title and then followed by a blank line and then a more thorough description.

2. Limit the subject line to 50 characters.
    * If you're having a hard time summarizing the subject, you might be commiting too much changes. Strive for atomic commits.
    * Github UI truncates subject line that's too long. The latter of your subject line that goes past 75 character will look like "This function's removed beca...". (It didn't goes past the limits, I know)

3. **Capitalize subject** line.

4. Do not end the subject with a period.

5. Use the imperative mood in the subject line.
    Imperative mood just means “spoken or written as if giving a command or instruction”. A few examples:

        ** Clean your room
        ** Close the door
        ** Take out the trash
6. Wrap the body at 72 characters.

7. Use the body to explain the **what** and **why** vs. how.


- Other things to keep in mind when making a commit message.
    * Pick one convention and stick with it. Be consistent with your style, because everything will be chaotic if you don't.

    * Explain the problem that this commit is solving. Focus on why you
    are making this change as opposed to how (the code explains that).
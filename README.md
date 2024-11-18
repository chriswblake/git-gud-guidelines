# Git Gud Guidelines
A public space for sharing tips and lessons learned on your coding journey.

- Playful, yet serious.
- Be respectful and helpful.

This is a sort of playground, a place for my webinar attendees to safely practice their first attempt at contributing to a pulic repository. Or, for experienced attendees to quickly share their wisdom with others in the moment.

Did you just attend a webinar or similar event with Christopher? Or... are you in it right now?
Maybe he introduced the idea of forking a repo, creating a branch, making some changes, and submitting a pull request (PR)? Here is your place to give it a try!

# Let's Git Gud

## Tips from a data scientist that made that mistake already
Mistakes I made (or saw) from scientists learning to code.

- Do NOT store data in your repo.
    -Instead, clone your repo to where your data is, not the other way.
    - Reference datasets in your README.
- Jupyter Notebooks store the results internally and dirty the change history.
    - Double check the comparison. Be careful what you commit. You might include sensitive info.
    - There are dedicated extensions for comparing notebooks.
- Many Matlab scripts can be ran using the open-source project [Octave](https://octave.org/).
    - Octave works in GitHub Actions. No need for additional paid licenses.

## Tips from a GitHub user that made that mistake already
- Don't share your Personal Access Token (PAT).
- As a new user, carefully consider your github handle. It will be the face of your future profile!

## Tips from a Git user that made that mistake already
- Never store sensitive information in your repo. (passwords, tokens, keys, urls)
- Commits are for small logical chunks of a bigger goal.
    - Branches are for (big) features. 
- Branches are not folders. They are temporary copies for reaching a single goal.
- OneDrive doesn’t like repos. Don’t do it.
- Start every project with the `.gitignore`.

## Tips from a coder that made that mistake already
- Ignore GitHub Desktop. Use the integrated tools in your IDE. It's way better!
- OMG, create a README and add at least 1 non-generic sentence.
    - Describing the project breifly.
    - Clarify any acronyms in the repo name.

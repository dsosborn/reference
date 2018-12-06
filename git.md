#USEFUL GIT SNIPPETS

# Export files changed since specified commit
git archive -o diff/patch.zip HEAD $(git diff --name-only 77d39ed^ HEAD -- src/)

# Generate diff file for changes between 2 commits in specified directory
git diff 77d39ed^ HEAD -- src/ > diff/myq-tend_2.diff

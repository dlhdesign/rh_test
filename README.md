# GitHub Interview Challenge

This repo is designed as a problem solving challenge. There are numerous ways to reach a satisfactory state, so the approach taken is as much part of the challenge as getting a correct solution. Your approach and results will be reviewed and discusse as part of the interview process.

- **Who is this for**: Developers and managers
- **What you'll do**: Prepare a patch release and resolve any merge conflicts.
- **What you'll need**: You will need to know how to work with branches, commits, tagging, and possibly other GitHub features.
- **How long**: This challenge should take less than 30 minutes to complete.

## Repository Outline

This repository represents an application that has undergone numerous changes - both features and bug fixes, all within the "main" branch. The commit messages have followed a naming convention to represent commits for features and commits for fixes. Release states have been marked using tags.

## Challenge Scenario

The currently released version of the application is "v1.0". The developer has prepared a "v2.0" and delivered it to QA for testing, but it has not yet been deployed to production. The business owner has decided that the critical bug fixes need to be deployed as a patch release without any of the new features.

## Success Criteria

1. A branch containing code in a "v1.1" state - defined as based on "v1.0" and including all of the "BUG" commits but none of the "FEATURE" ones
2. A clear history of the steps taken
3. Any merge conflicts should be resolved
4. The application code should be functional

Note: This is an overly simplified application where it very well may be more practical to just manually make the target changes in a single commit. That would not be considered a success.

## Starting The Challenege

1. Create an empty public repo in your account.
2. Run the following in your terminal from your working directory:
```
git clone --bare git@github.com:rh-innovation/rh_github_challenge.git
cd rh_github_challenge.git
git push --mirror git@github.com:YOUR-USER/NEW-REPOSITORY.git
cd ..
rm -rf rh_github_challenge.git
```
You are now ready to begin the challenge.

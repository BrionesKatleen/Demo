# GIT RULES
## 1. Branching Rules
- Main Branch (main) is always stable - only tested code goes here.
- Feature Branch
-- Name format: feature/<feature-name>

## 2. Commit Rules
- Always write clear, descriptive commit titles.
-- Format: <type>: <short description(minimum of 4 words>
-- Example: feature: add login button functionality

## 3. Pull Request / Merge Rules
- PR must be REVIEWED by atleast 2 teammates or the techlead before merging.
- Pass any test
### Avoid pushing directly to main. Always use feature branches → PR → merge

## 4. Code Style / Formatting
- Follow standard naming conventions
- Avoid committing compiled file, .vs, bin/, obj/ add them to .gitignore

## 5. File Changes / Testing
- Always pull the lastest changes before starting work.
- Test your code locally before pushing or making a PR. 

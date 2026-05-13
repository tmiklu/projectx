## 2.4.0
Released on 2026-05-13

### Feat

- Implement git tag collision check ([`368f135`](https://github.com/tmiklu/projectx/commit/368f135ed5d4221a0d66fbdde8d54e95f446aa10)) [`tmiklu`](https://github.com/tmiklu)



## 2.3.0
Released on 2026-05-13

### Feat

- Check for git tag collisions in release workflow ([`2641267`](https://github.com/tmiklu/projectx/commit/2641267164c0c1c045f73ac6d7124be59497d25f)) [`tmiklu`](https://github.com/tmiklu)

### Fix

- Modify GET_NEXT assignment in release.yml ([`a5e3007`](https://github.com/tmiklu/projectx/commit/a5e300757591e8a744c8d9347b8e5ccd411b0579)) [`tmiklu`](https://github.com/tmiklu)
- Fix command execution for version bump in release.yml ([`2b323b5`](https://github.com/tmiklu/projectx/commit/2b323b523d103b9fbd230d878d69118814a16d7c)) [`tmiklu`](https://github.com/tmiklu)
- Fix tag collision check in release workflow ([`b736d74`](https://github.com/tmiklu/projectx/commit/b736d747c63edd01d9c3597a5a09017d50f21598)) [`tmiklu`](https://github.com/tmiklu)
- Fix git tag collision check command ([`ea1b6f4`](https://github.com/tmiklu/projectx/commit/ea1b6f403f3af8aae2dfa6f22fc26ccbea8bd7cb)) [`tmiklu`](https://github.com/tmiklu)
- Fix indentation for git tag collision check step ([`9abb290`](https://github.com/tmiklu/projectx/commit/9abb2901af8766c62fae839e91ffb056875c8446)) [`tmiklu`](https://github.com/tmiklu)



## 2.2.0
Released on 2026-05-13

### Feat

- Refactor CHANGELOG to use dynamic GitHub URL ([`83e615f`](https://github.com/tmiklu/projectx/commit/83e615fced7ce216d13fc99366647772aad6eae1)) [`tmiklu`](https://github.com/tmiklu)
- Add author info to CHANGELOG entries ([`8a88f17`](https://github.com/tmiklu/projectx/commit/8a88f174e760ec3a98857dcb52263bc23b8ea733)) [`tmiklu`](https://github.com/tmiklu)
- Enhance release workflow with changelog dry run ([`548bc33`](https://github.com/tmiklu/projectx/commit/548bc33fc015b351b53d5eaac35080e3edf44707)) [`tmiklu`](https://github.com/tmiklu)
- Fix repository link in CHANGELOG.md.j2 ([`bd4b4cc`](https://github.com/tmiklu/projectx/commit/bd4b4cc187b8f0fad89c0bb2737f2e0e52a9fa03)) [`tmiklu`](https://github.com/tmiklu)

### Fix

- Fix formatting of changelog entries ([`4b1f08a`](https://github.com/tmiklu/projectx/commit/4b1f08aeaa6e43fcb93224bb4c8f25468c55d13d)) [`tmiklu`](https://github.com/tmiklu)
- Fix author link format in CHANGELOG template ([`39447ac`](https://github.com/tmiklu/projectx/commit/39447ac67b25e2d29814b90fd693be66b6f7ef4f)) [`tmiklu`](https://github.com/tmiklu)
- Remove 'archive' option from upload-artifact step ([`e37b8b0`](https://github.com/tmiklu/projectx/commit/e37b8b070f1f9c1cd788d777e927d2d89811da9e)) [`tmiklu`](https://github.com/tmiklu)
- Update upload-artifact action to version v7 ([`c72b8dd`](https://github.com/tmiklu/projectx/commit/c72b8dd2a6db2254da162cf567ae39cdab869acb)) [`tmiklu`](https://github.com/tmiklu)
- Upgrade actions/checkout from v4 to v5 ([`8ef16ba`](https://github.com/tmiklu/projectx/commit/8ef16ba029b035c53fc7f7fbc4ae920fbf103670)) [`tmiklu`](https://github.com/tmiklu)
- Fix formatting in CHANGELOG template ([`46047e0`](https://github.com/tmiklu/projectx/commit/46047e017d06bcad62b4151d34bbccbff064481a)) [`tmiklu`](https://github.com/tmiklu)
- Update changelog dry run command to use tee ([`a3bb9bb`](https://github.com/tmiklu/projectx/commit/a3bb9bb5e52c2a5379d6185d383f5a8d867883bf)) [`tmiklu`](https://github.com/tmiklu)
- Fix path for changelog-dry-run artifact ([`1a1ead4`](https://github.com/tmiklu/projectx/commit/1a1ead42425003382eb775ae94c5f723e146f62f)) [`tmiklu`](https://github.com/tmiklu)
- Update changelog artifact name to include .md extension ([`5fbb490`](https://github.com/tmiklu/projectx/commit/5fbb490b1eb03ba37fdef964c8a218933a81a1ab)) [`tmiklu`](https://github.com/tmiklu)
- revert ([`5f1f9ae`](https://github.com/tmiklu/projectx/commit/5f1f9ae703d465d7bbb67b66d7c6b1f3cb60a06d)) [`tmiklu`](https://github.com/tmiklu)
- Clean up release.yml by removing commented TAG line ([`0fefd67`](https://github.com/tmiklu/projectx/commit/0fefd67aa30c20b7c21b460fd0de1a2f1aaa2e21)) [`tmiklu`](https://github.com/tmiklu)
- Clean up release.yml by removing comments ([`9979019`](https://github.com/tmiklu/projectx/commit/9979019104fa21d033537afc94e098075f53cddf)) [`tmiklu`](https://github.com/tmiklu)
- Remove repo_url from commitizen settings ([`5786cb5`](https://github.com/tmiklu/projectx/commit/5786cb57d8e876be301fa050cefc912d71b98ab4)) [`tmiklu`](https://github.com/tmiklu)
- Fix link format for commit SHA in CHANGELOG ([`ac90729`](https://github.com/tmiklu/projectx/commit/ac90729fdb8b81b1dae797a2bd69027ec06520f1)) [`tmiklu`](https://github.com/tmiklu)



## 2.1.1
Released on 2026-05-13

### Fix

- Update commit link format in CHANGELOG template ([`8857e97`](/commit/8857e975664a8435ddd30c98f13d0ff798fb3cc4))
- Enhance changelog format with release date ([`09ea8f7`](/commit/09ea8f7e092a7d9cd6ae7b179696d4538635e99c))



## 2.1.0 (2026-05-13)
### Feat

- Refactor release notes extraction logic in release.yml ([`c243d3e`](https://github.com/tmiklu/projectx/commit/c243d3e98448eaaba87c162dd47bcd811d1022ab))
- Create CHANGELOG.md.j2 for release notes ([`049d511`](https://github.com/tmiklu/projectx/commit/049d511557a23a3e31539f3b36c2403a6525dd84))

### Fix

- Refactor changelog output logic in release.yml ([`a51b55f`](https://github.com/tmiklu/projectx/commit/a51b55f79d5f27f9dd1c24a4f54d3d0d9b1c2aa1))
- Simplify bump logic in release workflow ([`b1d196c`](https://github.com/tmiklu/projectx/commit/b1d196ce1dbfa598d652c39683018f8583aab945))



## 2.0.1 (2026-05-13)

### Fix

- Add repo_url to commitizen in pyproject.toml

## 2.0.0 (2026-05-13)

### Feat

- Add print statement for breaking change notice

## 1.9.0 (2026-05-13)

### Feat

- Clean up release.yml by removing commented lines

### Fix

- Clean up release workflow by removing comments
- Fix working-directory reference in release workflow
- Set default shell and working directory for jobs
- Fix working directory reference in release workflow
- Refactor working directory settings in release workflow

## 1.8.1 (2026-05-13)

### Fix

- Update print statements for clarity and fixes

## 1.8.0 (2026-05-13)

### Feat

- Set GH_TOKEN for GitHub Release step

## 1.7.2 (2026-05-13)

### Fix

- Remove GITHUB_TOKEN from release workflow

## 1.7.1 (2026-05-13)

### Fix

- Modify CI bot environment variables

## 1.7.0 (2026-05-13)

### Feat

- Modify release.yml to comment out token and permissions

### Fix

- Update CI bot names in release workflow
- Update CI bot names and email in release workflow
- Add environment variable for GH_TOKEN in release workflow

## 1.6.2 (2026-05-13)

### Fix

- Update CI bot names and email in release workflow

## 1.6.1 (2026-05-13)

### Fix

- Fix print statement for new feature extension

## 1.6.0 (2026-05-12)

### Feat

- Update feature version in main.py

## 1.5.0 (2026-05-12)

### Feat

- Extend new feature with additional print statement
- Add print statement for new feature 2.0.0

## 1.4.0 (2026-05-12)

### Fix

- Fix typo in new login form print statement
- Clarify contact form typo fix message

## 1.3.0 (2026-05-05)

### Feat

- Update breaking change message for clarity

## 1.2.1 (2026-05-05)

### Fix

- message for breaking change in main.py
- Fix message for another breaking change

## 1.2.0 (2026-05-04)

### Feat

- Refactor breaking change message in main.py

### Fix

- Fix message for breaking change notification
- Fix spam protection message in main.py

## 1.1.0 (2026-05-04)

### Feat

- Update email contact print statement for clarity

## 1.0.1 (2026-04-29)

### Fix

- **main.py**: Fix typo in calendar option print statement

## 1.0.0 (2026-04-29)

### BREAKING CHANGE

- new release

### Feat

- **main.py**: new major release

## 0.8.0 (2026-04-29)

### Feat

- **main.py**: another breaking change
- **main.py**: add breaking change

## 0.7.0 (2026-04-29)

### Feat

- **main.py**: Add spam protection feature to the login system

## 0.6.0 (2026-04-28)

### Feat

- **main.py**: Fix typo in new login form message
- **main.py**: Add new print statement for login form

## 0.5.0 (2026-04-28)

### Feat

- **main.py**: Add calendar option to main.py
- **main.py**: Add email contact feature

## 0.4.0 (2026-04-28)

### Feat

- **main.py**: Add SSO login feature to main.py

## 0.3.0 (2026-04-28)

### Feat

- **main.py**: Add login feature print statement

### Fix

- **main.py**: Correct typo in contact form print statement

## 0.2.0 (2026-04-28)

### Feat

- Remove third feature print statement
- **main.py**: Add third feature print statement
- Add second feature print statement
- **main.py**: add first feature

## 0.1.0 (2026-04-28)

### Feat

- **main.py**: add first feature print statement
- add commitizen
- init projectx

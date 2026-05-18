## 2.5.0
Released on 2026-05-15

### Feat

- Update release tag format in workflow ([`4ad36a6`](https://github.com/tmiklu/projectx/commit/4ad36a6d96ce3e13ca5a860f78d334ca8d38ba66)) [`tmiklu`](https://github.com/tmiklu)



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

## release/orchestrator/9.5.0
📅 Released on 2026-05-18

### ✨ Feat

- Validate increment strategy in release.yml ([`faf802e`](https://github.com/tmiklu/projectx/commit/faf802e863f47854fac5f7c7031f62d7a89df908)) 👤 [`tmiklu`](https://github.com/tmiklu)



## release/orchestrator/9.4.2
📅 Released on 2026-05-18

### ♻️  Refactor

- hotfix branch policy validation ([`6f93944`](https://github.com/tmiklu/projectx/commit/6f93944e97362d6d5b131f7a6127caff2d1b7aa3)) 👤 [`tmiklu`](https://github.com/tmiklu)



## release/orchestrator/9.4.1
📅 Released on 2026-05-18

### ♻️  Refactor

- increment strategy handling in release workflow ([`6dfdc1b`](https://github.com/tmiklu/projectx/commit/6dfdc1bba133c847b8f23b59314f7a11038ad111)) 👤 [`tmiklu`](https://github.com/tmiklu)



## release/orchestrator/9.4.0
📅 Released on 2026-05-18

### ✨ Feat

- increment detection in release workflow ([`8bb2651`](https://github.com/tmiklu/projectx/commit/8bb2651dc0db83818d99408b79a309312b7387fc)) 👤 [`tmiklu`](https://github.com/tmiklu)



## release/orchestrator/9.3.0
📅 Released on 2026-05-18

### ✨ Feat

- Update changelog file references in release workflow ([`2695de7`](https://github.com/tmiklu/projectx/commit/2695de7b0ab2b3b076db5d17f0406494f57e619d)) 👤 [`tmiklu`](https://github.com/tmiklu)
- awk command for extracting changelog entries ([`08c3698`](https://github.com/tmiklu/projectx/commit/08c3698e7cf73110a891c2f0cc8ad8b94deec8fc)) 👤 [`tmiklu`](https://github.com/tmiklu)



## release/orchestrator/9.2.0
📅 Released on 2026-05-18

### ✨ Feat

- awk command syntax in release workflow ([`7193f87`](https://github.com/tmiklu/projectx/commit/7193f87f35fdcbf61fd824292b823e832ffa7d2d)) 👤 [`tmiklu`](https://github.com/tmiklu)



## release/orchestrator/9.1.0
📅 Released on 2026-05-18

### ✨ Feat

- Remove push triggers from release workflow ([`0b9d9e1`](https://github.com/tmiklu/projectx/commit/0b9d9e113bc1825706ddeaef49bd8b626499657b)) 👤 [`tmiklu`](https://github.com/tmiklu)
- Add push triggers for main and release branches ([`bfe6b0d`](https://github.com/tmiklu/projectx/commit/bfe6b0dd1b746a300e98ee1fdca2879e88baf348)) 👤 [`tmiklu`](https://github.com/tmiklu)

### 🐛 Fix

- awk command to use variable for release tag ([`565e191`](https://github.com/tmiklu/projectx/commit/565e1916859b6b0bcfbd064be30d92f9ba039d2d)) 👤 [`tmiklu`](https://github.com/tmiklu)
- concurrency group syntax in release.yml ([`4bbf20e`](https://github.com/tmiklu/projectx/commit/4bbf20e9794d340809ba5611539ea999dd22b665)) 👤 [`tmiklu`](https://github.com/tmiklu)



## release/orchestrator/9.0.0
📅 Released on 2026-05-18

### ✨ Feat

- Update release workflow to use RELEASE_TAG ([`8a4a7ee`](https://github.com/tmiklu/projectx/commit/8a4a7ee77a865810beaded6f016e8743470d1113)) 👤 [`tmiklu`](https://github.com/tmiklu)

### 🐛 Fix

- syntax error in release.yml for RELEASE_NAME ([`662974b`](https://github.com/tmiklu/projectx/commit/662974bbd29318194056694e7c0ab80a44cc0686)) 👤 [`tmiklu`](https://github.com/tmiklu)



## release/orchestrator/8.5.1
📅 Released on 2026-05-18

### 🐛 Fix

- syntax error in release.yml for RELEASE_NAME ([`662974b`](https://github.com/tmiklu/projectx/commit/662974bbd29318194056694e7c0ab80a44cc0686)) 👤 [`tmiklu`](https://github.com/tmiklu)



## release/orchestrator/8.5.0
📅 Released on 2026-05-18

### ✨ Feat

- GitHub release tag and name assignment ([`0e2bff4`](https://github.com/tmiklu/projectx/commit/0e2bff4c83ed2c2be0597a950815b51893d14e1b)) 👤 [`tmiklu`](https://github.com/tmiklu)
- Add log for no tag collision detection ([`329186c`](https://github.com/tmiklu/projectx/commit/329186c3a269cae7fb328fd55cbfa86b062487d6)) 👤 [`tmiklu`](https://github.com/tmiklu)
- Add 'refactor' change type to changelog template ([`caf1faf`](https://github.com/tmiklu/projectx/commit/caf1faf157c4684c43b0b2c93e49b6ec65adcf41)) 👤 [`tmiklu`](https://github.com/tmiklu)
- output redirection for GET_NEXT variable ([`455b2f5`](https://github.com/tmiklu/projectx/commit/455b2f5893df2c05c1bdc3d723b0c7b8a4c58278)) 👤 [`tmiklu`](https://github.com/tmiklu)

### ♻️  Refactor

- changelog bump command to use variable ([`1bf8500`](https://github.com/tmiklu/projectx/commit/1bf850008ea8c86bf88c3423a0c098a3c94b094e)) 👤 [`tmiklu`](https://github.com/tmiklu)
- command substitution for changelog generation ([`1403eec`](https://github.com/tmiklu/projectx/commit/1403eece866d7367040bb050d7213a83c0976c6d)) 👤 [`tmiklu`](https://github.com/tmiklu)
- Refactor changelog generation commands in release.yml ([`aa20303`](https://github.com/tmiklu/projectx/commit/aa2030333d5727d14a7602619cf7cdaf85269f79)) 👤 [`tmiklu`](https://github.com/tmiklu)



## release/orchestrator/8.4.0
📅 Released on 2026-05-18

### ✨ Feat

- variable assignment for CHANGE_LOG in release.yml ([`79f37ec`](https://github.com/tmiklu/projectx/commit/79f37ecc63cb95f52b5bdadb9d9cf20407ebc681)) 👤 [`tmiklu`](https://github.com/tmiklu)
- changelog handling in release workflow ([`2b6c0bf`](https://github.com/tmiklu/projectx/commit/2b6c0bff86b419243b8e8a0cb39a2fca3fc457ba)) 👤 [`tmiklu`](https://github.com/tmiklu)



## release/orchestrator/8.3.0
📅 Released on 2026-05-18

### ✨ Feat

- Update release branch naming convention for tags ([`8d2181e`](https://github.com/tmiklu/projectx/commit/8d2181e60ee475ec22431884b8db46b4180b1057)) 👤 [`tmiklu`](https://github.com/tmiklu)
- release branch creation in workflow ([`124df55`](https://github.com/tmiklu/projectx/commit/124df559405d91466b7602f79e2dd19386fab06a)) 👤 [`tmiklu`](https://github.com/tmiklu)



## release/orchestrator/8.2.0
📅 Released on 2026-05-18

### ✨ Feat

- Update print statement for new feature clarity ([`452000d`](https://github.com/tmiklu/projectx/commit/452000de5f7b677871275c8ab10c31cf991a9866)) 👤 [`tmiklu`](https://github.com/tmiklu)

### 🐛 Fix

- print statement for new feature extension ([`61275e1`](https://github.com/tmiklu/projectx/commit/61275e1f9461d5fd52297bdee478c923dec94a43)) 👤 [`tmiklu`](https://github.com/tmiklu)

### ⚡ Perf

- message for new feature 1.6.0 ([`453e9f9`](https://github.com/tmiklu/projectx/commit/453e9f950d6be44806822bae7bd9e094eaf60bfb)) 👤 [`tmiklu`](https://github.com/tmiklu)



## release/orchestrator/8.1.0
📅 Released on 2026-05-18

### ✨ Feat

- Update changelog header format ([`16ec127`](https://github.com/tmiklu/projectx/commit/16ec127a22219610b2be0a173bc978d722b5ebba)) 👤 [`tmiklu`](https://github.com/tmiklu)

### ⚡ Perf

- Refine print statement for new feature 1.6.0 ([`c8aeb7c`](https://github.com/tmiklu/projectx/commit/c8aeb7cd40aeb3d5cdbecf372e87797868545021)) 👤 [`tmiklu`](https://github.com/tmiklu)



## 🚀 release/orchestrator/8.0.2
📅 Released on 2026-05-18

### 🐛 Fix

- echo command for GET_NEXT in release workflow ([`85892b7`](https://github.com/tmiklu/projectx/commit/85892b77e2dfd2128d89930e4a54c8c9ed75ec99)) 👤 [`tmiklu`](https://github.com/tmiklu)
- Update release workflow to skip changelog generation ([`55ea810`](https://github.com/tmiklu/projectx/commit/55ea8104a9f26c8f69d4d170681fccc068442cd7)) 👤 [`tmiklu`](https://github.com/tmiklu)



## 🚀 release/orchestrator/8.0.1
📅 Released on 2026-05-18

### 🐛 Fix

- Comment out dry-run for cz bump in release workflow ([`787a56c`](https://github.com/tmiklu/projectx/commit/787a56c8da9b2f7f47d5a6d1e4656caf7439cf10)) 👤 [`tmiklu`](https://github.com/tmiklu)



## 🚀 release/orchestrator/8.0.0
📅 Released on 2026-05-18

### ✨ Feat

- Add breaking change note for SSO login feature ([`bf703a4`](https://github.com/tmiklu/projectx/commit/bf703a4005b90d93371028b5e54f40dacfc1f622)) 👤 [`tmiklu`](https://github.com/tmiklu)

### 🐛 Fix

- typo in email contact feature message ([`bb2db06`](https://github.com/tmiklu/projectx/commit/bb2db064dcae38b3f3174623afa59000cfa0d881)) 👤 [`tmiklu`](https://github.com/tmiklu)

### ⚡ Perf

- Modify print statement for new feature 1.6.0 ([`516dab2`](https://github.com/tmiklu/projectx/commit/516dab28e923e95a79f070cf6965b8289028236e)) 👤 [`tmiklu`](https://github.com/tmiklu)



## 🚀 release/orchestrator/7.1.0
📅 Released on 2026-05-18

### ✨ Feat

- create emotikons in pipeline ([`9d78a4a`](https://github.com/tmiklu/projectx/commit/9d78a4ab633bfcea429840bb11d585b378b851d2)) 👤 [`tmiklu`](https://github.com/tmiklu)

### 🐛 Fix

- Refactor changelog template conditionals ([`95b10ef`](https://github.com/tmiklu/projectx/commit/95b10efff6edb7b684ad6829d9a38f71ec7ee5d9)) 👤 [`tmiklu`](https://github.com/tmiklu)
- message for new feature 1.6.0 ([`fdfeb6a`](https://github.com/tmiklu/projectx/commit/fdfeb6a4cf38d89d24b7ad74c94f8b5aa0b1d126)) 👤 [`tmiklu`](https://github.com/tmiklu)

### ⚡ Perf

- Modify print statement for extended feature ([`5534b1d`](https://github.com/tmiklu/projectx/commit/5534b1d3dbc70d309bf628fc09d13a2e5285d28c)) 👤 [`tmiklu`](https://github.com/tmiklu)



## release/orchestrator/7.0.0
Released on 2026-05-15

### Feat

- Simplify changelog output and upload steps ([`8b83442`](https://github.com/tmiklu/projectx/commit/8b83442a656e01ca1edd7897b9d519d0b5bc2d05)) [`tmiklu`](https://github.com/tmiklu)



## release/orchestrator/6.1.0
Released on 2026-05-15

### Feat

- branch creation and push in release workflow ([`f7805dd`](https://github.com/tmiklu/projectx/commit/f7805dda9d31ba1a8beb4ceb6e805c18788faa10)) [`tmiklu`](https://github.com/tmiklu)



## release/orchestrator/6.0.0
Released on 2026-05-15

### Feat

- git push command to use 'origin' for release branch ([`5424004`](https://github.com/tmiklu/projectx/commit/5424004275a19ab4fdbb709f6b530e9a034faf3d)) [`tmiklu`](https://github.com/tmiklu)
- release branch creation and push command ([`cf0e862`](https://github.com/tmiklu/projectx/commit/cf0e8627bc9c137eb3d78b3a83c1416c8f3db69b)) [`tmiklu`](https://github.com/tmiklu)



## release/orchestrator/5.1.0
Released on 2026-05-15

### Feat

- release branch creation and push command ([`cf0e862`](https://github.com/tmiklu/projectx/commit/cf0e8627bc9c137eb3d78b3a83c1416c8f3db69b)) [`tmiklu`](https://github.com/tmiklu)



## release/orchestrator/5.0.0
Released on 2026-05-15

### Feat

- Simplify release branch creation in workflow ([`d329e2c`](https://github.com/tmiklu/projectx/commit/d329e2ce279f95f774d5e6d2a5b7d04a5575d2f1)) [`tmiklu`](https://github.com/tmiklu)



## release/orchestrator/4.1.0
Released on 2026-05-15

### Feat

- Enhance release workflow with branch creation logic ([`bcc6a86`](https://github.com/tmiklu/projectx/commit/bcc6a86187672bb7a152409a1cfb882e25bbfd4b)) [`tmiklu`](https://github.com/tmiklu)



## release/orchestrator/4.0.2
Released on 2026-05-15

### Fix

- Enhance print statement for new feature clarity ([`67bfd7a`](https://github.com/tmiklu/projectx/commit/67bfd7aff0bd6d489cbed51f7e5e0590ab2a6ebe)) [`tmiklu`](https://github.com/tmiklu)



## release/orchestrator/4.0.1
Released on 2026-05-15

### Fix

- Enhance release workflow to detect next version ([`048bc13`](https://github.com/tmiklu/projectx/commit/048bc1325ab1946ff5f5438d2fdccd54c47ca6eb)) [`tmiklu`](https://github.com/tmiklu)



## release/orchestrator/4.0.0
Released on 2026-05-15

### Feat

- Make 'dry-run' input optional in release workflow ([`d81a232`](https://github.com/tmiklu/projectx/commit/d81a2320d589ce0c4d21599b18a3f3016dd1ed52)) [`tmiklu`](https://github.com/tmiklu)
- Update release workflow for changelog output ([`3e6f5af`](https://github.com/tmiklu/projectx/commit/3e6f5af710b1090bb9ff43a5f2a0d6470abed2c0)) [`tmiklu`](https://github.com/tmiklu)
- Fix dry-run step in release workflow ([`1d2d47d`](https://github.com/tmiklu/projectx/commit/1d2d47de16d9a3d88903feb881624d0bc07cade5)) [`tmiklu`](https://github.com/tmiklu)
- Update release workflow to use GITHUB_OUTPUT ([`8150b14`](https://github.com/tmiklu/projectx/commit/8150b149515163e93679d30c93df625a024142b6)) [`tmiklu`](https://github.com/tmiklu)

### Fix

- branch creation command in release workflow ([`a575a66`](https://github.com/tmiklu/projectx/commit/a575a6678d4e2c0284b6fac0709e935e2c4bf35d)) [`tmiklu`](https://github.com/tmiklu)
- Implement git tag collision detection ([`0912c02`](https://github.com/tmiklu/projectx/commit/0912c02e7803dc8b7ad1a5b995ae3b1259100508)) [`tmiklu`](https://github.com/tmiklu)
- Define GET_TAG for checking git tag collisions ([`0218c9a`](https://github.com/tmiklu/projectx/commit/0218c9a5249d7516652b6a7c47ec76d94d9fb048)) [`tmiklu`](https://github.com/tmiklu)
- Update tag collision check in release workflow ([`9797526`](https://github.com/tmiklu/projectx/commit/979752698fa59244d59649b1e79419bf9bf0b00e)) [`tmiklu`](https://github.com/tmiklu)
- git tag collision check command ([`8dca1b7`](https://github.com/tmiklu/projectx/commit/8dca1b71b45306984fb36028deb003b683b40bc2)) [`tmiklu`](https://github.com/tmiklu)
- git tag collision check syntax ([`32ecb88`](https://github.com/tmiklu/projectx/commit/32ecb88595e5ffc0722bb781f4f35fb4d2ed1f3b)) [`tmiklu`](https://github.com/tmiklu)
- regex for checking git tag collision ([`8ca017b`](https://github.com/tmiklu/projectx/commit/8ca017bec903415983601c3e8c6d08b656cfaa3e)) [`tmiklu`](https://github.com/tmiklu)
- git tag collision check in release workflow ([`84c0690`](https://github.com/tmiklu/projectx/commit/84c06908913fba37c8f7ec4ba84a1d2d5466b970)) [`tmiklu`](https://github.com/tmiklu)
- git tag collision check in release workflow ([`64fef91`](https://github.com/tmiklu/projectx/commit/64fef91b2a9f7bb3a8158a82790d88cef57d6388)) [`tmiklu`](https://github.com/tmiklu)
- Refactor git tag collision check in release workflow ([`5225b3e`](https://github.com/tmiklu/projectx/commit/5225b3ed84340dde3881ae4a61ff3fe0c7c787ab)) [`tmiklu`](https://github.com/tmiklu)
- Refactor dry-run logic in release workflow ([`ce067c9`](https://github.com/tmiklu/projectx/commit/ce067c91f8aef6257be662f25ffda064086d2eff)) [`tmiklu`](https://github.com/tmiklu)
- changelog dry run command in release workflow ([`85f34f4`](https://github.com/tmiklu/projectx/commit/85f34f4859ebb2eee3425ac6a93de1653157456c)) [`tmiklu`](https://github.com/tmiklu)
- Modify changelog output in release.yml ([`d2ef900`](https://github.com/tmiklu/projectx/commit/d2ef9008c56ce3ba987b11fa9c536da721771fb4)) [`tmiklu`](https://github.com/tmiklu)
- git tag collision check in release workflow ([`a6c5ec3`](https://github.com/tmiklu/projectx/commit/a6c5ec3f7e14557c595d5fcaeafb1ffabed48b4f)) [`tmiklu`](https://github.com/tmiklu)
- regex for checking git tag collisions ([`ecf5b2c`](https://github.com/tmiklu/projectx/commit/ecf5b2ca4be25bf35f6f9ca29a2392454fd13e2c)) [`tmiklu`](https://github.com/tmiklu)
- Make 'dry-run' input required and adjust logic ([`83cb3ce`](https://github.com/tmiklu/projectx/commit/83cb3ced8707d6c6d4d87de875e10dfc894e4c1b)) [`tmiklu`](https://github.com/tmiklu)
- Improve git tag collision check message ([`ec99cb7`](https://github.com/tmiklu/projectx/commit/ec99cb7443801549b690fa0656acfe6224ab2e3b)) [`tmiklu`](https://github.com/tmiklu)
- Update release workflow to not create changelog file ([`849dd62`](https://github.com/tmiklu/projectx/commit/849dd6296ec011a676818635b31d1d534486061d)) [`tmiklu`](https://github.com/tmiklu)
- Remove blank line in release workflow ([`138c2ff`](https://github.com/tmiklu/projectx/commit/138c2ffe3314373663306246af15cb95655eb067)) [`tmiklu`](https://github.com/tmiklu)
- Refactor release workflow to remove next_version output ([`10ed289`](https://github.com/tmiklu/projectx/commit/10ed2896016a13346fead15b3e6afecc0a1a17dc)) [`tmiklu`](https://github.com/tmiklu)
- Refactor release workflow to simplify environment setup ([`0b1bb55`](https://github.com/tmiklu/projectx/commit/0b1bb55f434fe996c33ac35420c4aa9eee692654)) [`tmiklu`](https://github.com/tmiklu)



## release/orchestrator/3.1.0
Released on 2026-05-15

### Feat

- Make 'dry-run' input optional in release workflow ([`d81a232`](https://github.com/tmiklu/projectx/commit/d81a2320d589ce0c4d21599b18a3f3016dd1ed52)) [`tmiklu`](https://github.com/tmiklu)
- Update release workflow for changelog output ([`3e6f5af`](https://github.com/tmiklu/projectx/commit/3e6f5af710b1090bb9ff43a5f2a0d6470abed2c0)) [`tmiklu`](https://github.com/tmiklu)
- Fix dry-run step in release workflow ([`1d2d47d`](https://github.com/tmiklu/projectx/commit/1d2d47de16d9a3d88903feb881624d0bc07cade5)) [`tmiklu`](https://github.com/tmiklu)
- Update release workflow to use GITHUB_OUTPUT ([`8150b14`](https://github.com/tmiklu/projectx/commit/8150b149515163e93679d30c93df625a024142b6)) [`tmiklu`](https://github.com/tmiklu)

### Fix

- Implement git tag collision detection ([`0912c02`](https://github.com/tmiklu/projectx/commit/0912c02e7803dc8b7ad1a5b995ae3b1259100508)) [`tmiklu`](https://github.com/tmiklu)
- Define GET_TAG for checking git tag collisions ([`0218c9a`](https://github.com/tmiklu/projectx/commit/0218c9a5249d7516652b6a7c47ec76d94d9fb048)) [`tmiklu`](https://github.com/tmiklu)
- Update tag collision check in release workflow ([`9797526`](https://github.com/tmiklu/projectx/commit/979752698fa59244d59649b1e79419bf9bf0b00e)) [`tmiklu`](https://github.com/tmiklu)
- git tag collision check command ([`8dca1b7`](https://github.com/tmiklu/projectx/commit/8dca1b71b45306984fb36028deb003b683b40bc2)) [`tmiklu`](https://github.com/tmiklu)
- git tag collision check syntax ([`32ecb88`](https://github.com/tmiklu/projectx/commit/32ecb88595e5ffc0722bb781f4f35fb4d2ed1f3b)) [`tmiklu`](https://github.com/tmiklu)
- regex for checking git tag collision ([`8ca017b`](https://github.com/tmiklu/projectx/commit/8ca017bec903415983601c3e8c6d08b656cfaa3e)) [`tmiklu`](https://github.com/tmiklu)
- git tag collision check in release workflow ([`84c0690`](https://github.com/tmiklu/projectx/commit/84c06908913fba37c8f7ec4ba84a1d2d5466b970)) [`tmiklu`](https://github.com/tmiklu)
- git tag collision check in release workflow ([`64fef91`](https://github.com/tmiklu/projectx/commit/64fef91b2a9f7bb3a8158a82790d88cef57d6388)) [`tmiklu`](https://github.com/tmiklu)
- Refactor git tag collision check in release workflow ([`5225b3e`](https://github.com/tmiklu/projectx/commit/5225b3ed84340dde3881ae4a61ff3fe0c7c787ab)) [`tmiklu`](https://github.com/tmiklu)
- Refactor dry-run logic in release workflow ([`ce067c9`](https://github.com/tmiklu/projectx/commit/ce067c91f8aef6257be662f25ffda064086d2eff)) [`tmiklu`](https://github.com/tmiklu)
- changelog dry run command in release workflow ([`85f34f4`](https://github.com/tmiklu/projectx/commit/85f34f4859ebb2eee3425ac6a93de1653157456c)) [`tmiklu`](https://github.com/tmiklu)
- Modify changelog output in release.yml ([`d2ef900`](https://github.com/tmiklu/projectx/commit/d2ef9008c56ce3ba987b11fa9c536da721771fb4)) [`tmiklu`](https://github.com/tmiklu)
- git tag collision check in release workflow ([`a6c5ec3`](https://github.com/tmiklu/projectx/commit/a6c5ec3f7e14557c595d5fcaeafb1ffabed48b4f)) [`tmiklu`](https://github.com/tmiklu)
- regex for checking git tag collisions ([`ecf5b2c`](https://github.com/tmiklu/projectx/commit/ecf5b2ca4be25bf35f6f9ca29a2392454fd13e2c)) [`tmiklu`](https://github.com/tmiklu)
- Make 'dry-run' input required and adjust logic ([`83cb3ce`](https://github.com/tmiklu/projectx/commit/83cb3ced8707d6c6d4d87de875e10dfc894e4c1b)) [`tmiklu`](https://github.com/tmiklu)
- Improve git tag collision check message ([`ec99cb7`](https://github.com/tmiklu/projectx/commit/ec99cb7443801549b690fa0656acfe6224ab2e3b)) [`tmiklu`](https://github.com/tmiklu)
- Update release workflow to not create changelog file ([`849dd62`](https://github.com/tmiklu/projectx/commit/849dd6296ec011a676818635b31d1d534486061d)) [`tmiklu`](https://github.com/tmiklu)
- Remove blank line in release workflow ([`138c2ff`](https://github.com/tmiklu/projectx/commit/138c2ffe3314373663306246af15cb95655eb067)) [`tmiklu`](https://github.com/tmiklu)
- Refactor release workflow to remove next_version output ([`10ed289`](https://github.com/tmiklu/projectx/commit/10ed2896016a13346fead15b3e6afecc0a1a17dc)) [`tmiklu`](https://github.com/tmiklu)
- Refactor release workflow to simplify environment setup ([`0b1bb55`](https://github.com/tmiklu/projectx/commit/0b1bb55f434fe996c33ac35420c4aa9eee692654)) [`tmiklu`](https://github.com/tmiklu)



## release/orchestrator/3.0.0
Released on 2026-05-15

### Feat

- Rename changelog output step to bump output ([`0376dcb`](https://github.com/tmiklu/projectx/commit/0376dcbc4e625c44190b39204091234964e79383)) [`tmiklu`](https://github.com/tmiklu)
- Fix syntax for conditional branch creation ([`c21c38c`](https://github.com/tmiklu/projectx/commit/c21c38c03eaa7e035885d4ebb76e977331cae5eb)) [`tmiklu`](https://github.com/tmiklu)


## release/orchestrator/2.8.1
Released on 2026-05-15

### Fix

- Ensure release branch exists for minor/major versions ([`d6edd1f`](https://github.com/tmiklu/projectx/commit/d6edd1fab6213df7b4d035f9a1f269b607b71d33)) [`tmiklu`](https://github.com/tmiklu)



## release/orchestrator/2.9.0
Released on 2026-05-15

### Feat

- Fix syntax for conditional branch creation ([`c21c38c`](https://github.com/tmiklu/projectx/commit/c21c38c03eaa7e035885d4ebb76e977331cae5eb)) [`tmiklu`](https://github.com/tmiklu)



## release/orchestrator/2.8.1
Released on 2026-05-15

### Fix

- Ensure release branch exists for minor/major versions ([`d6edd1f`](https://github.com/tmiklu/projectx/commit/d6edd1fab6213df7b4d035f9a1f269b607b71d33)) [`tmiklu`](https://github.com/tmiklu)



## release/orchestrator/2.8.0
Released on 2026-05-15

### Feat

- Fix environment variable assignment in release.yml ([`68f6a7f`](https://github.com/tmiklu/projectx/commit/68f6a7f379e2b178232a36b4797e717eb83f1159)) [`tmiklu`](https://github.com/tmiklu)
- Update increment detection in release workflow ([`56fd641`](https://github.com/tmiklu/projectx/commit/56fd6416d23b4f1819a54d0e7f9fd1146bf827ba)) [`tmiklu`](https://github.com/tmiklu)



## release/orchestrator/2.7.1
Released on 2026-05-15

### Fix

- Update release workflow to detect version increment ([`a5ac508`](https://github.com/tmiklu/projectx/commit/a5ac5081495a55ef9bbb1004c930e5dfd9fcc504)) [`tmiklu`](https://github.com/tmiklu)



## release/orchestrator/2.7.0
Released on 2026-05-15

### Feat

- Update release workflow to handle increment detection ([`cb89f27`](https://github.com/tmiklu/projectx/commit/cb89f276ae7201e133e814eacfe6d30240fb0fef)) [`tmiklu`](https://github.com/tmiklu)
- Add dry run output for changelog generation ([`8c0b533`](https://github.com/tmiklu/projectx/commit/8c0b5335a26ac0d4e33f0623cef030088bb04028)) [`tmiklu`](https://github.com/tmiklu)

### Fix

- Update changelog generation in release workflow ([`ffc614f`](https://github.com/tmiklu/projectx/commit/ffc614fccaaa5c98fd58c599a7aa077e9cb63b0d)) [`tmiklu`](https://github.com/tmiklu)
- Remove dry-run condition for git tag collision check ([`37e311d`](https://github.com/tmiklu/projectx/commit/37e311d5c51c5a7b60b304329dfc6652688fa329)) [`tmiklu`](https://github.com/tmiklu)



## release/orchestrator/2.6.0
Released on 2026-05-15

### Feat

- Rename project from 'abc' to 'ai-orchestrator' ([`b1d7d5c`](https://github.com/tmiklu/projectx/commit/b1d7d5c735e07bc999e1cd75d652c764368fdf99)) [`tmiklu`](https://github.com/tmiklu)

### Fix

- Rename package option from 'ai-orchestrator' to 'orchestrator' ([`e74f0e8`](https://github.com/tmiklu/projectx/commit/e74f0e816ea9c1b0c4fb13fd1e32cc1d5a58da35)) [`tmiklu`](https://github.com/tmiklu)
- Update tag format in pyproject.toml ([`7ad9c88`](https://github.com/tmiklu/projectx/commit/7ad9c882020648687ec5f70a4e04c203afbb2397)) [`tmiklu`](https://github.com/tmiklu)
- Rename orchestrator to ai-orchestrator in release.yml ([`e377d39`](https://github.com/tmiklu/projectx/commit/e377d3969ed34408df6d85acc7120479b3917afe)) [`tmiklu`](https://github.com/tmiklu)
- Update tag_format in pyproject.toml ([`00e85d9`](https://github.com/tmiklu/projectx/commit/00e85d9244e8d812baa8d59cfc03953c7796be2c)) [`tmiklu`](https://github.com/tmiklu)
- Add condition for git tag collision check ([`c5e2cf8`](https://github.com/tmiklu/projectx/commit/c5e2cf81293456beb515445a159e3d9265476c9d)) [`tmiklu`](https://github.com/tmiklu)
- spacing in GitHub release tag definition ([`20ebdc1`](https://github.com/tmiklu/projectx/commit/20ebdc12c0628f2ee85dffb431be011da17b442b)) [`tmiklu`](https://github.com/tmiklu)


## release/orchestrator/2.5.0
Released on 2026-05-15

### BREAKING CHANGE

- new release ([`bf5eaa6`](https://github.com/tmiklu/projectx/commit/bf5eaa6dd366fe21999774ec26ea808157a7c0d5)) [`tmiklu`](https://github.com/tmiklu)

### Feat

- Update release tag format in workflow ([`4ad36a6`](https://github.com/tmiklu/projectx/commit/4ad36a6d96ce3e13ca5a860f78d334ca8d38ba66)) [`tmiklu`](https://github.com/tmiklu)
- Implement git tag collision check ([`368f135`](https://github.com/tmiklu/projectx/commit/368f135ed5d4221a0d66fbdde8d54e95f446aa10)) [`tmiklu`](https://github.com/tmiklu)
- Check for git tag collisions in release workflow ([`2641267`](https://github.com/tmiklu/projectx/commit/2641267164c0c1c045f73ac6d7124be59497d25f)) [`tmiklu`](https://github.com/tmiklu)
- Refactor CHANGELOG to use dynamic GitHub URL ([`83e615f`](https://github.com/tmiklu/projectx/commit/83e615fced7ce216d13fc99366647772aad6eae1)) [`tmiklu`](https://github.com/tmiklu)
- Add author info to CHANGELOG entries ([`8a88f17`](https://github.com/tmiklu/projectx/commit/8a88f174e760ec3a98857dcb52263bc23b8ea733)) [`tmiklu`](https://github.com/tmiklu)
- Enhance release workflow with changelog dry run ([`548bc33`](https://github.com/tmiklu/projectx/commit/548bc33fc015b351b53d5eaac35080e3edf44707)) [`tmiklu`](https://github.com/tmiklu)
- Fix repository link in CHANGELOG.md.j2 ([`bd4b4cc`](https://github.com/tmiklu/projectx/commit/bd4b4cc187b8f0fad89c0bb2737f2e0e52a9fa03)) [`tmiklu`](https://github.com/tmiklu)
- Refactor release notes extraction logic in release.yml ([`c243d3e`](https://github.com/tmiklu/projectx/commit/c243d3e98448eaaba87c162dd47bcd811d1022ab)) [`tmiklu`](https://github.com/tmiklu)
- Create CHANGELOG.md.j2 for release notes ([`049d511`](https://github.com/tmiklu/projectx/commit/049d511557a23a3e31539f3b36c2403a6525dd84)) [`tmiklu`](https://github.com/tmiklu)
- Add print statement for breaking change notice ([`18b69b9`](https://github.com/tmiklu/projectx/commit/18b69b916408f216897d2c5e2b319cd13dbcbd8a)) [`tmiklu`](https://github.com/tmiklu)
- Clean up release.yml by removing commented lines ([`4fe6a46`](https://github.com/tmiklu/projectx/commit/4fe6a462faae9139511c635e91610a9ac0885b67)) [`tmiklu`](https://github.com/tmiklu)
- Set GH_TOKEN for GitHub Release step ([`eeedb33`](https://github.com/tmiklu/projectx/commit/eeedb332ad98c926f45562b8329404c893381d6c)) [`tmiklu`](https://github.com/tmiklu)
- Modify release.yml to comment out token and permissions ([`64c5846`](https://github.com/tmiklu/projectx/commit/64c58460aa59c75d7d9633eaf5c0deaff02e23ce)) [`tmiklu`](https://github.com/tmiklu)
- Update feature version in main.py ([`ff8c7af`](https://github.com/tmiklu/projectx/commit/ff8c7af1bbec6b176d181519cf87c6681699f10f)) [`tmiklu`](https://github.com/tmiklu)
- Extend new feature with additional print statement ([`e64c976`](https://github.com/tmiklu/projectx/commit/e64c976360acff85ab17f37d47adb867c9934d7e)) [`tmiklu`](https://github.com/tmiklu)
- Add print statement for new feature 2.0.0 ([`013a8ac`](https://github.com/tmiklu/projectx/commit/013a8ac5aa5523dd9e8fc68c913dd68075369a79)) [`tmiklu`](https://github.com/tmiklu)
- Update breaking change message for clarity ([`d3d7077`](https://github.com/tmiklu/projectx/commit/d3d707700d56d014e4f8d5287d8c145b4e52882a)) [`tmiklu`](https://github.com/tmiklu)
- Refactor breaking change message in main.py ([`c0333cf`](https://github.com/tmiklu/projectx/commit/c0333cf80b26d1ca6a5cb67d0b29cad5122893e8)) [`tmiklu`](https://github.com/tmiklu)
- Update email contact print statement for clarity ([`19bbbbb`](https://github.com/tmiklu/projectx/commit/19bbbbb97d08e206d9fb210a62c7c64c39cec274)) [`tmiklu`](https://github.com/tmiklu)
- new major release ([`bf5eaa6`](https://github.com/tmiklu/projectx/commit/bf5eaa6dd366fe21999774ec26ea808157a7c0d5)) [`tmiklu`](https://github.com/tmiklu)
- another breaking change ([`f2109a9`](https://github.com/tmiklu/projectx/commit/f2109a974b0b5500fab0553ae36449c3bef24fe4)) [`tmiklu`](https://github.com/tmiklu)
- add breaking change ([`efd8ed8`](https://github.com/tmiklu/projectx/commit/efd8ed8c0cb68a84a948260d2e8cf528a0086778)) [`tmiklu`](https://github.com/tmiklu)
- Add spam protection feature to the login system ([`f7a25ed`](https://github.com/tmiklu/projectx/commit/f7a25ed613857bd77f9c0821678a275c196a302b)) [`tmiklu`](https://github.com/tmiklu)
- Fix typo in new login form message ([`169169d`](https://github.com/tmiklu/projectx/commit/169169ddb3d56c94331c2b03fe963dbfa49f02d6)) [`tmiklu`](https://github.com/tmiklu)
- Add new print statement for login form ([`1f61601`](https://github.com/tmiklu/projectx/commit/1f61601625e018fa0be69798a8f95745d4bfad44)) [`tmiklu`](https://github.com/tmiklu)
- Add calendar option to main.py ([`fd381ba`](https://github.com/tmiklu/projectx/commit/fd381ba799f3f4eccb36b976dd853ab1c718f6a9)) [`tmiklu`](https://github.com/tmiklu)
- Add email contact feature ([`ca9d580`](https://github.com/tmiklu/projectx/commit/ca9d580fb9cbe46bb4085035e12e09899d04d9cc)) [`tmiklu`](https://github.com/tmiklu)
- Add SSO login feature to main.py ([`eabc95d`](https://github.com/tmiklu/projectx/commit/eabc95d572aad3552a12639978793d257ae2a93e)) [`tmiklu`](https://github.com/tmiklu)
- Add login feature print statement ([`ad5414f`](https://github.com/tmiklu/projectx/commit/ad5414f87d8c2fd47064571c1a2ff8c156f83c52)) [`tmiklu`](https://github.com/tmiklu)
- Remove third feature print statement ([`26c6f8e`](https://github.com/tmiklu/projectx/commit/26c6f8ec12d2c7b991a2417c1e7ec90daf2edfcd)) [`tmiklu`](https://github.com/tmiklu)
- Add third feature print statement ([`28f6eb7`](https://github.com/tmiklu/projectx/commit/28f6eb7d0c8875faa0099f949eed68a75b99c940)) [`tmiklu`](https://github.com/tmiklu)
- Add second feature print statement ([`4809f80`](https://github.com/tmiklu/projectx/commit/4809f801e5d4f48df015bb8722c889ddfe966fbe)) [`tmiklu`](https://github.com/tmiklu)
- add first feature ([`38ecccb`](https://github.com/tmiklu/projectx/commit/38ecccb2535558bc38e4013cbdb9533f6508acb8)) [`tmiklu`](https://github.com/tmiklu)
- Add third feature print statement ([`7e00d8f`](https://github.com/tmiklu/projectx/commit/7e00d8fb2f49cd61c2dbcb48a33b1c3f294c5fc0)) [`tmiklu`](https://github.com/tmiklu)
- Add second feature print statement ([`338eb44`](https://github.com/tmiklu/projectx/commit/338eb4452b2d9f4d40f42493bb7b23d6826a0a46)) [`tmiklu`](https://github.com/tmiklu)
- add first feature print statement ([`cc1cab7`](https://github.com/tmiklu/projectx/commit/cc1cab768514fa63780c92812819a648dca4ca16)) [`tmiklu`](https://github.com/tmiklu)
- add commitizen ([`df8337b`](https://github.com/tmiklu/projectx/commit/df8337be745a6d309466777b87770328ed0ca16b)) [`tmiklu`](https://github.com/tmiklu)
- init projectx ([`898f3de`](https://github.com/tmiklu/projectx/commit/898f3de842ec6cbfe29224f85ff8b7f4cfe5fce0)) [`tmiklu`](https://github.com/tmiklu)

### Fix

- Modify GET_NEXT assignment in release.yml ([`a5e3007`](https://github.com/tmiklu/projectx/commit/a5e300757591e8a744c8d9347b8e5ccd411b0579)) [`tmiklu`](https://github.com/tmiklu)
- Fix command execution for version bump in release.yml ([`2b323b5`](https://github.com/tmiklu/projectx/commit/2b323b523d103b9fbd230d878d69118814a16d7c)) [`tmiklu`](https://github.com/tmiklu)
- Fix tag collision check in release workflow ([`b736d74`](https://github.com/tmiklu/projectx/commit/b736d747c63edd01d9c3597a5a09017d50f21598)) [`tmiklu`](https://github.com/tmiklu)
- Fix git tag collision check command ([`ea1b6f4`](https://github.com/tmiklu/projectx/commit/ea1b6f403f3af8aae2dfa6f22fc26ccbea8bd7cb)) [`tmiklu`](https://github.com/tmiklu)
- Fix indentation for git tag collision check step ([`9abb290`](https://github.com/tmiklu/projectx/commit/9abb2901af8766c62fae839e91ffb056875c8446)) [`tmiklu`](https://github.com/tmiklu)
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
- Update commit link format in CHANGELOG template ([`8857e97`](https://github.com/tmiklu/projectx/commit/8857e975664a8435ddd30c98f13d0ff798fb3cc4)) [`tmiklu`](https://github.com/tmiklu)
- Enhance changelog format with release date ([`09ea8f7`](https://github.com/tmiklu/projectx/commit/09ea8f7e092a7d9cd6ae7b179696d4538635e99c)) [`tmiklu`](https://github.com/tmiklu)
- Refactor changelog output logic in release.yml ([`a51b55f`](https://github.com/tmiklu/projectx/commit/a51b55f79d5f27f9dd1c24a4f54d3d0d9b1c2aa1)) [`tmiklu`](https://github.com/tmiklu)
- Simplify bump logic in release workflow ([`b1d196c`](https://github.com/tmiklu/projectx/commit/b1d196ce1dbfa598d652c39683018f8583aab945)) [`tmiklu`](https://github.com/tmiklu)
- Add repo_url to commitizen in pyproject.toml ([`6edb75f`](https://github.com/tmiklu/projectx/commit/6edb75fa6fcd0680a29b56d75ea9f5778bf13041)) [`tmiklu`](https://github.com/tmiklu)
- Clean up release workflow by removing comments ([`b8ef890`](https://github.com/tmiklu/projectx/commit/b8ef8902591c22d66c8c3a96694fb85791543278)) [`tmiklu`](https://github.com/tmiklu)
- Fix working-directory reference in release workflow ([`c1d9556`](https://github.com/tmiklu/projectx/commit/c1d9556c7c8e7844e67b7a268a6dde81f3680560)) [`tmiklu`](https://github.com/tmiklu)
- Set default shell and working directory for jobs ([`72d7600`](https://github.com/tmiklu/projectx/commit/72d7600200a32718b6cdc7196c4eb8f7196d7eda)) [`tmiklu`](https://github.com/tmiklu)
- Fix working directory reference in release workflow ([`2561816`](https://github.com/tmiklu/projectx/commit/25618162ce8d594fcade3576fd9be92afbd9a86f)) [`tmiklu`](https://github.com/tmiklu)
- Refactor working directory settings in release workflow ([`40199e8`](https://github.com/tmiklu/projectx/commit/40199e82bdecc1af31c4fab1e6b79b22ee6dd1f4)) [`tmiklu`](https://github.com/tmiklu)
- Update print statements for clarity and fixes ([`98938f0`](https://github.com/tmiklu/projectx/commit/98938f08eccab9bb3ad52f102894108fc2a5ba6e)) [`tmiklu`](https://github.com/tmiklu)
- Remove GITHUB_TOKEN from release workflow ([`3fce6a8`](https://github.com/tmiklu/projectx/commit/3fce6a85166f2574fd4907617fa1c884838e1d29)) [`tmiklu`](https://github.com/tmiklu)
- Modify CI bot environment variables ([`d769497`](https://github.com/tmiklu/projectx/commit/d7694974bd62f814d58c8dc6dfd66e29520f3d5b)) [`tmiklu`](https://github.com/tmiklu)
- Update CI bot names in release workflow ([`9161a71`](https://github.com/tmiklu/projectx/commit/9161a710345a0a7def4e1f5c33b3349ffe8c8a1d)) [`tmiklu`](https://github.com/tmiklu)
- Update CI bot names and email in release workflow ([`9dc8485`](https://github.com/tmiklu/projectx/commit/9dc8485f2f42294c791e84f7122091a10ba1ed19)) [`tmiklu`](https://github.com/tmiklu)
- Add environment variable for GH_TOKEN in release workflow ([`e2752f1`](https://github.com/tmiklu/projectx/commit/e2752f11d2f070dd20924b9b6b40b4288023e36b)) [`tmiklu`](https://github.com/tmiklu)
- Update CI bot names and email in release workflow ([`9ae20b7`](https://github.com/tmiklu/projectx/commit/9ae20b758ec431b6deee6bbfba8bc5a916b5fc2c)) [`tmiklu`](https://github.com/tmiklu)
- Fix print statement for new feature extension ([`89c39f9`](https://github.com/tmiklu/projectx/commit/89c39f9349bd4e6a4392d845980ba5672a5da5a9)) [`tmiklu`](https://github.com/tmiklu)
- Fix typo in new login form print statement ([`26007a6`](https://github.com/tmiklu/projectx/commit/26007a6bfd31c71d8a1fb5fe683bdb35177ec715)) [`tmiklu`](https://github.com/tmiklu)
- Clarify contact form typo fix message ([`a423494`](https://github.com/tmiklu/projectx/commit/a42349492b672747568a48c4d6ccb69abdc88c1d)) [`tmiklu`](https://github.com/tmiklu)
- message for breaking change in main.py ([`465abe1`](https://github.com/tmiklu/projectx/commit/465abe1f0e60671a0aeb8c0a0942bf3101d6bd35)) [`tmiklu`](https://github.com/tmiklu)
- Fix message for another breaking change ([`01eb1ed`](https://github.com/tmiklu/projectx/commit/01eb1ed5deca2ecfc67fcac53bc39dd7661651ce)) [`tmiklu`](https://github.com/tmiklu)
- Fix message for breaking change notification ([`27ec02a`](https://github.com/tmiklu/projectx/commit/27ec02ad4a00de5384b434df3bcf901c8a18166b)) [`tmiklu`](https://github.com/tmiklu)
- Fix spam protection message in main.py ([`4fd8810`](https://github.com/tmiklu/projectx/commit/4fd8810884ec7d5af5a0742a6e0e2224590f375a)) [`tmiklu`](https://github.com/tmiklu)
- Fix typo in calendar option print statement ([`5b7f119`](https://github.com/tmiklu/projectx/commit/5b7f11915abe9787698c5a5602c83b5f1a11aac5)) [`tmiklu`](https://github.com/tmiklu)
- Correct typo in contact form print statement ([`b4cf6c4`](https://github.com/tmiklu/projectx/commit/b4cf6c497dadeaace2012903bd9357cf5347bf39)) [`tmiklu`](https://github.com/tmiklu)



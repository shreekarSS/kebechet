# Changelog for the Kebechet - a Thoth bot

## Release 1.11.1 (2022-11-18T16:26:42)
* cb1ba6b Update OWNERS
* 74b3aff Update README.rst
* 53af1d3 ':arrow_up: Automatic update of dependencies by Kebechet for the rhel-8 environment'
* 4c2564f Update repo
* baaf8ea  - Add pyproject.toml to maintain version from Kebechet's version manager  - Update Messages ISSUE_BODY_NO_VERSION_IDENTIFIER_FOUND variable with    pyproject.toml related
* a20a7d8 add default in case there are no runtime environments
* 3538b19 make PR description independent of issue description
* 7ea414a Release of version 1.11.0
* 8c49688 :arrow_up: Automatic update of dependencies by Kebechet for the rhel-8 environment
* 661b908 remove branch creation
* 1c69fea add signing to kebechet commits
* 16c8374 New feature update : Add 'allow' and 'disallow' setting to each manager
* e087552 Add 'env_allow_list' and 'env_disallow_list' setting to each manager
* 6e76af7 :arrow_up: Automatic update of dependencies by Kebechet for the rhel-8 environment
* cb7e541 add line to checkout default branch after pushing changes
* 3b8352c :arrow_up: Automatic update of dependencies by Kebechet for the rhel-8 environment
* a76af37 Create function which respects gh body limits
* 735fffb :arrow_up: Automatic update of dependencies by Kebechet for the rhel-8 environment
* 385bbd0 add check for no PRs opened
* 03bf872 :arrow_up: Automatic update of dependencies by Kebechet for the rhel-8 environment
* 3e697b5 :arrow_up: Automatic update of dependencies by Kebechet for the rhel-8 environment
* e9adaad :arrow_up: Automatic update of dependencies by Kebechet for the rhel-8 environment
* 7211c21 Remove checks for git and local path from pipfile
* bc612c8 :arrow_up: Automatic update of dependencies by Kebechet for the rhel-8 environment
* b81b18f Format package names in GitHub issues
* b76a191 Release of version 1.10.5
* eca1171 Type cast the type to pass typechecking
* 6b679bc Release of version 1.10.4 (#1136)
* e4f0671 :arrow_up: Automatic update of dependencies by Kebechet for the rhel-8 environment (#1134)
* a9c3bc5 :arrow_up: Automatic update of dependencies by Kebechet for the rhel-8 environment
* ea8dec8 check to make sure pr exists before attempting rebase on remote branch
* 40f30fe Use lock when updating the dependencies to avoid resource limitations
* 4e5fa9d :arrow_up: Automatic update of dependencies by Kebechet for the rhel-8 environment
* c3b0e8f :arrow_up: Automatic update of dependencies by Kebechet for the rhel-8 environment
* 6d6a243 :arrow_up: Automatic update of dependencies by Kebechet for the rhel-8 environment
* 30e76d2 - Add environment details in PR body with <details> tag (#1120)
* 8f5927d Mask git clone https token from logs (#1124)
* a42f419 Point the closing comment with Pull request link (#1119)
* 3d0eb13 Fix _construct_branch_name() method to avoid conflict while creating branches for different analysis ids
* 07e302b :arrow_up: Automatic update of dependencies by Kebechet for the rhel-8 environment
* 32f580f Release of version 1.10.3
* 53c6a73 :arrow_up: Automatic update of dependencies by Kebechet for the rhel-8 environment
* 03b509a :arrow_up: Automatic update of dependencies by Kebechet for the rhel-8 environment
* 20fab3b download owners file from repo
* ba8a06d remove hidden files during os walk
* 3661bd9 call sync when generating dependency graph
* fd5c20a Add configuration for support issue creation
* 0f907e2 :arrow_up: Automatic update of dependencies by Kebechet for the rhel-8 environment (#1105)
* 0c6ac2f Update Dockerfile with cmake dependency
* cdab57c add type annotations for urllib3.util.Url unpacking
* 924d3d0 :arrow_up: Automatic update of dependencies by Kebechet for the rhel-8 environment (#1103)
* 6a3133c Release of version 1.10.2 (#1104)
* bf81dd2 Fix: Kebechet advise manager starting multiple advice requests Update run() method to prevent adding duplicate runtime_environments from .thoth.yaml
* bbdbd34 :arrow_up: Automatic update of dependencies by Kebechet for the rhel-8 environment
* b405c22 Fix for  referencing incorrect dict keys and Piplock file path
* 5c5238a :arrow_up: Automatic update of dependencies by Kebechet for the rhel-8 environment
* c88a1a0 fix: change the import method of managerbase in release_version
* be9ceae :arrow_up: Automatic update of dependencies by Kebechet for the rhel-8 environment
* b4ccdc0 Process direct dependencies to remove any extra deps
* 6781b02 :arrow_up: Automatic update of dependencies by Kebechet for the rhel-8 environment
* c13e8c6 bugfix: make labels for update manager default to empty list
* f3420d7 :arrow_up: Automatic update of dependencies by Kebechet for the rhel-8 environment
* eb784d3 Release of version 1.10.1
* 0bb79f6 Issue: Kebechet was picking approvers from it's own OWNERS file
* 521b82f :arrow_up: Automatic update of dependencies by Kebechet for the rhel-8 environment
* 656f71e Fix: Refer key 'parameters' directly
* c8e715d A more informative version manager message around wrong versions
* 3e391b4 :arrow_up: Automatic update of dependencies by Kebechet for the rhel-8 environment
* 18e28dc Issue: https://github.com/thoth-station/kebechet/issues/1050
* db9596f :arrow_up: Automatic update of dependencies by Kebechet for the rhel-8 environment
* 137e855 fetch branch using git.fetch before trying to use it
* 5042936 add documentation for PR labels for version manager
* 8d09e3c Release of version 1.10.0
* 7e7d2c6 :arrow_up: Automatic update of dependencies by Kebechet for the rhel-8 environment
* 4e141c0 :arrow_up: Automatic update of dependencies by Kebechet for the rhel-8 environment (#1066)
* 3fdd416 Issue: Delete the branch if the pr is merged and tag is created
* f8905e7 :arrow_up: Automatic update of dependencies by Kebechet for the rhel-8 environment
* 493eabe :arrow_up: Automatic update of dependencies by Kebechet for the rhel-8 environment
* 65f2936 Address https://github.com/thoth-station/kebechet/pull/1058#pullrequestreview-1001902393
* a3edba2 Update run() method to check the merge PR ,to create TAG and publish
* 3bfa558 Add new util functions
* a6b0e8d :arrow_up: Automatic update of dependencies by Kebechet for the rhel-8 environment (#1057)
* a5aeffe Release of version 1.9.0
* 64f0859 :arrow_up: Automatic update of dependencies by Kebechet for the rhel-8 environment
* ba55d4b Add behave tests to Kebechet for 'integration' tests
* 29e8a08 :arrow_up: Automatic update of dependencies by Kebechet for the rhel-8 environment
* bc985bd fix: adjust pipenv cmd limit downward (leave space for dep graph)
* 2148a7f fix: open issue in the case of uninitialized overlay dir
* 18bdf88 fix: cleanup any unused changes to avoid merge conflicts
* eecb7db Fixing repo typing bug so tests can pass.
* 7c6d9de various bugfixes for keb-advise-manager
* d648580 :arrow_up: Automatic update of dependencies by Kebechet for the rhel-8 environment (#1040)
* b2fabb2 :arrow_up: Automatic update of dependencies by Kebechet for the rhel-8 environment
* 52e1438 :arrow_up: Automatic update of dependencies by Kebechet for the rhel-8 environment (#1034)
* 55665f6 env for format
* 057a13a clearer github comment for up to date dependencies
* bfaac03 add more info to no v found issue
* c060090 :arrow_up: Automatic update of dependencies by Kebechet for the rhel-8 environment
* 1a9f59d :arrow_up: Automatic update of dependencies by Kebechet for the rhel-8 environment
* 5afd12f fix mypy precommit errs
* fafbe4c add comment to update issue with PR id
* df78e41 Release of version 1.8.0
* c4732ff :arrow_up: Automatic update of dependencies by Kebechet for the rhel-8 environment
* 9abcded close duplicate release issues when manager is run (#1000)
* bce7391 :arrow_up: Automatic update of dependencies by Kebechet for the rhel-8 environment
* 1be3cb4 :arrow_up: Automatic update of dependencies by Kebechet for the rhel-8 environment
* f2d4cfa Add links to manager docs in config initialization
* 6e267b0 freshness check to avoid duplicating PR
* cef66cf place limit on chars from pipenv command. leave ~5000 for the rest of the issue
* 5faed21 wrong location for keb metadata was used
* 7b87695 env_name->env
* 8f23a42 :arrow_up: Automatic update of dependencies by Kebechet for the rhel-8 environment
* 67c7364 Update OWNERS
* b1e443c handle case where no packages section exists in Pipfile
* 040abfd :arrow_up: Automatic update of dependencies by Kebechet for the rhel-8 environment
* ae8137d :arrow_up: Automatic update of dependencies by Kebechet for the rhel-8 environment
* 9cbc118 open issue if no pipenv files are found
* 6764590 :arrow_up: Automatic update of dependencies by Kebechet for the rhel-8 environment
* cac8310 :arrow_up: Automatic update of dependencies by Kebechet for the rhel-8 environment
* 7f07f40 Update the label to use on issue creation
* dc7e927 Update GitHub issue templates for bugs and features
* e46039c Update pre-commit plugins
* f0153f9 :arrow_up: Automatic update of dependencies by Kebechet for the rhel-8 environment
* d1003c7 Add commit hashes to the changelog entries
* 0616f5e handle case where no runtime_envs are defined
* f7177ee use consistent name for 'has_prev_release'
* 8455bf8 :arrow_up: Automatic update of dependencies by Kebechet for the rhel-8 environment
* cd7fbf5 :arrow_up: Automatic update of dependencies by Kebechet for the rhel-8 environment
* 1268243 :medal_sports: set badges for easy access to content
* aec4de6 :arrow_up: Automatic update of dependencies by Kebechet for the rhel-8 environment
* 28b8f92 :arrow_up: Automatic update of dependencies by Kebechet for the rhel-8 environment
* 4f53d80 :arrow_up: Automatic update of dependencies by Kebechet for the rhel-8 environment (#984)
* e354f59 :ship: Release of version 1.7.3
* a627555 use previous tag for computing changelog
* 87a2348 :ship: Release of version 1.7.2 (#979)
* c24eb0d :arrow_up: Automatic update of dependencies by Kebechet for the rhel-8 environment
* 69f3a76 :arrow_up: Automatic update of dependencies by Kebechet for the rhel-8 environment
* 3dac675 pop enabled config
* 2031b8a check before trying to unshallow a repo
* 7d02ecd Enable TLS verification
* 230d21b Enable TLS verification in the sample default configuration
* f9d733d Release of version 1.7.1
* c58c3d1 remove all references to get user
* 4c3be7f Unpin fasttext version from Pipfile
* fc2ae4f :arrow_up: Automatic update of dependencies by Kebechet for the rhel-8 environment
* ce154cb :arrow_up: Automatic update of dependencies by Kebechet for the rhel-8 environment
* 274844a Release of version 1.7.0
* 7ccf8d5 :arrow_up: Automatic update of dependencies by Kebechet for the rhel-8 environment
* dc1b116 use analysis-id 4 branch name to avoid collisions
* 6570681 Add branch for if thoth configuration blocks advise submission
* c8d05ff add documentation for advise issue
* 87a063c :arrow_up: Automatic update of dependencies by Kebechet for the rhel-8 environment
* e8565f6 add link to manager doc above managers block in minimal yaml
* 8b97239 update version manager to act on PR merge with labels
* 839c3fa Suggest users to use Thamos CLI to create requirements file
* 836766f :arrow_up: Automatic update of dependencies by Kebechet for the rhel-8 environment
* b41b624 Release of version 1.6.8
* 88c879a Fix the links to each manager's README
* 85faf52 :arrow_up: Automatic update of dependencies by Kebechet for the rhel-8 environment
* 2ecf813 :arrow_up: Automatic update of dependencies by Kebechet for the rhel-8 environment
* fabb4dd create_pr for manager class with default value for forknamespace
* 5287496 check if update needs rebase
* 6992ee1 use env variable for kebechets name
* cab06ad :arrow_up: Automatic update of dependencies by Kebechet for the rhel-8 environment
* d71873f :arrow_up: Automatic update of dependencies by Kebechet for the rhel-8 environment
* 0b0cdf5 Release of version 1.6.7 (#932)
* dce8022 Runtime environment name must not use colon
* 51bee61 :arrow_up: Automatic update of dependencies by Kebechet for the rhel:8 environment
* 3f32a9e Fix format string reference to environment name
* 13587f0 :arrow_up: Automatic update of dependencies by Kebechet for the rhel:8 environment
* bf52e61 :arrow_up: Automatic update of dependencies by Kebechet for the rhel:8 environment
* 47d86db remove kebechet- prefix from version branch (used for image tag)
* 6a2b106 :boat: Release of version 1.6.6
* 1dbd454 if no depth is passed fetch full history
* 8a70071 add kebechet- to all branch names
* 1f03d42 :boat: Release of version 1.6.5
* 186a626 clean repo after using
* be967cb :arrow_up: Automatic update of dependencies by Kebechet for the rhel:8 environment
* 45ff002 :boat: Release of version 1.6.4
* 9fdc35c check if .git exists so that we don't catch all gitcommand exceptions (#909)
* 6d03399 if we have already cloned to dir, return repo from dir
* fc3f43e :boat: Release of version 1.6.3
* 2812394 :fire: patch the circuler import fix for keb version in utils
* 0670cd5 Release of version 1.6.2
* 8594b09 Remove the maintainers section from .thoth.yaml
* 5bbbb0b :arrow_up: Automatic update of dependencies by Kebechet for the rhel:8 environment
* b33bfba Track advise status using GitHub issue
* 56652d7 patch the fasttext version for build fix
* b80a79b Release of version 1.6.1 (#897)
* 40ec92f add keb version to issue body
* 16bd1e3 Release of version 1.6.0
* aaeb9a8 add triage/accepted labels to release issue template to prevent Prow from starting a traige
* bb08e18 :arrow_up: Automatic update of dependencies by Kebechet for the rhel:8 environment
* 58ddafc Add Goern, Harshad and Pep as approvers
* 99604e5 :bomb: use https based url in the pre-commit
* e79d822 :turtle: Support python 3.9 in kebechet dependency management
* ab8d44d reraise github server exception
* 43c9949 allow clone dir to be passed as environment variable
* b4f0d60 use approvers section of OWNERS file as default maintainers
* 9a3903d do not report dependency manager exception on support (#878)
* 559d170 add custom exception for known failure cases and open issues for failed manager
* 6638269 change key value for getting results from advise endpoint
* 619789e use sphinx for Kebechet documentation
* 0ffac1c Release of version 1.5.5
* 2556614 checks for num lines to avoid out-of-bounds exception
* fa6c784 :turtle: patch read write method for changelog update
* 895d46b set self.runtime_environment and use for all issue titles
* e7aa4e2 :arrow_up: Automatic update of dependencies by Kebechet for the rhel:8 environment
* 728e406 Release of version 1.5.4
* 8c4da0e check if issue already exists
* 2441af8 Release of version 1.5.3
* aa10c3a catch ssl errors as it is a networking issue
* e1159a7 :arrow_up: Automatic update of dependencies by Kebechet for the rhel:8 environment
* 0c316c2 create changelog file if it doesn't exist
* de5fb05 :arrow_up: Automatic update of dependencies by Kebechet for the rhel:8 environment
* 80d9c9c make changelog not smart by default
* d41784c add enabled flag to manager configuration
* 7ff18c7 don't require locked version for old deps
* 971ea07 :arrow_up: Automatic update of dependencies by Kebechet for the rhel:8 environment
* 0cc1274 add checks for local installations and pkgs bundled by pipenv
* 83b84ed check for none indicating function failed
* 61de998 create issue if no requirements found for runtime env
* 0e96c6e if PR already exists warn and continue
* ac75fb2 Release of version 1.5.2
* 7c5b549 :arrow_up: Automatic update of dependencies by Kebechet for the rhel:8 environment (#837)
* fed9840 add KPostOffice to approvers
* c1bc58c only create one issue per exc per line
* 51e0949 Release of version 1.5.1
* 5734ab1 :arrow_up: Automatic update of dependencies by Kebechet for the rhel:8 environment
* 4bd0f86 Fix markdown format for table rows
* 57e007a :arrow_up: Automatic update of dependencies by Kebechet for the rhel:8 environment
* 303e841 :arrow_up: Automatic update of dependencies by Kebechet for the rhel:8 environment
* 0f77413 :bug: fix some typos
* 5b95913 do not raise issue for conn error
* 73136df :arrow_up: Automatic update of dependencies by Kebechet for the rhel:8 environment
* 06b4274 add link to repository which caused exception
* bf1eaad :arrow_up: Automatic update of dependencies by Kebechet for the rhel:8 environment
* 29f9180 :arrow_up: Automatic update of dependencies by Kebechet for the rhel:8 environment
* 7671b39 get relative path of overlay currently being updated for link
* 65eb02f Release of version 1.5.0
* 3818067 instead of opening issues in user repo open in thoth-station/support
* 5d0603f updated README files to reflect current state of Kebechet
* 0d44c76 Minor format improvements in the README
* 3d621ad log if issue creation is disabled
* f3853c3 add unregistered manager which adds thoth-config
* 2412165 convert README from RST to MD
* d46ecbf add return statement
* 4b7c68e pull runtime_environment directly from advise results
* 6f801de if requirements.txt does not exist it must be created
* fd0b528 Format traceback with Python backtick code
* 83a98f3 Release of version 1.4.1
* a8e87a1 Empty commit for a new release
* d477b9f removed unused -dev dependencies
* 7f325bd advise manager with overlays
* 6af3f0b Release of version 1.4.0 (#773)
* d236e9a :arrow_up: Automatic update of dependencies by Kebechet (#768)
* 5e42cc2 add args to get access token
* 3ad74f5 open issues on repo when managers fail
* 463c9b1 make update manager work with overlays
* 29856c8 :arrow_up: Automatic update of dependencies by Kebechet
* a7883a5 Release of version 1.3.3
* 5c07238 :arrow_up: Automatic update of dependencies by Kebechet
* d451afe :sparkles: add some Kubernetes-inspired Labels to Issues opened by Kebechet
* e215ce4 fix issue 746
* 6bebf1c :arrow_up: Automatic update of dependencies by Kebechet
* 70a99e7 :arrow_up: Automatic update of dependencies by Kebechet
* c932a96 fixed bug with unrelated histories where khebhut doesn't create PR
* 70d197f pass environment name to managers and add documentation for expected manager behaviour
* 1aa56e2 update from template project
* 7241950 add priority/critical-urgent label to all bot related issue templates
* 20368a1 use upstream solution for adding assignees
* b58fa85 :arrow_up: Automatic update of dependencies by Kebechet
* 4c5ed88 Release of version 1.3.2
* aac846f use ogr to get app auth token
* 4b9334a :arrow_up: updated labels of issue templates
* 6c14824 pre-commit issue
* 8192e51 Update kebechet/managers/version/version.py
* 6733305 Fixed prepending when Title exists
* 2b7b32b Fixed small bug in which original changelog was removed
* aee38e3 Fixed README to remove legacy example configuration
* c2e429a changed appending changelog to prepending changelog
* b140006 :arrow_up: Automatic update of dependencies by Kebechet
* f319d82 Release of version 1.3.1
* 3b5f95d add docs for locally running Kebechet
* 8e85295 Update OWNERS
* bb41c79 add ogr dep to Pipfile
* 0c115ab :arrow_up: Automatic update of dependencies by Kebechet
* 926f75d :arrow_up: Automatic update of dependencies by Kebechet
* 96b3dcc Release of version 1.3.0
* 52eec5b remove thoth-sourcemanagement from Kebechet (#725)
* cf3c2c4 :arrow_up: Automatic update of dependencies by Kebechet (#724)
* f6c9c62 :hatched_chick: update the prow resource limits (#723)
* f63750c :arrow_up: Automatic update of dependencies by Kebechet
* df1f127 :arrow_up: Automatic update of dependencies by Kebechet
* 61ab9fb use thamos.lib.write_files
* fbd122d :zap: pre-commit fixes for the master branch
* 9614e16 :arrow_up: Automatic update of dependencies by Kebechet (#716)
* 2b1229d :arrow_up: Automatic update of dependencies by Kebechet (#713)
* 662e2ae :arrow_up: Automatic update of dependencies by Kebechet
* 4f57eea :arrow_up: Automatic update of dependencies by Kebechet (#709)
* c80d314 add kebechet metadata when sending request to thamos (#699)
* bf6df81 :arrow_up: Automatic update of dependencies by Kebechet (#708)
* 3597c94 remove todo
* 7dafb80 :arrow_up: Automatic update of dependencies by Kebechet (#706)
* 9020a2a :arrow_up: Automatic update of dependencies by Kebechet (#703)
* 9d8b030 :arrow_up: fix some formatting and update pre-commit plugins
* 20623e5 :sparkles: reconfgured CI/CD to use prow and aicoe-ci
* f972d45 :arrow_up: Automatic update of dependencies by Kebechet (#697)
* cb1a270 add justification based on metadata if possible
* 62e8138 :arrow_up: Automatic update of dependencies by Kebechet (#695)
* 30dc9b8 :arrow_up: Automatic update of dependencies by Kebechet (#694)
* 82a5b1c :arrow_up: Automatic update of dependencies by Kebechet (#692)
* 98e1be6 :arrow_up: Automatic update of dependencies by Kebechet (#691)
* f9e7f65 Release of version 1.2.4 (#690)
* b4383e2 :arrow_up: Automatic update of dependencies by kebechet. (#687)
* fdeca5d write outputs of pipenv lock -r to output file (#686)
* 134e8ef :arrow_up: Automatic update of dependencies by kebechet. (#685)
* b084816 :arrow_up: Automatic update of dependencies by kebechet. (#684)
* b40bbd4 :arrow_up: Automatic update of dependencies by kebechet. (#682)
* c0c4b41 Automatically close update merge request if no longer relevant (#661)
* 84eb9bd :arrow_up: Automatic update of dependencies by kebechet. (#677)
* a1349b5 :arrow_up: Automatic update of dependencies by kebechet. (#668)
* 6171631 Fixed log message (#673)
* 6ad8bda Delete branch if the pull request has been already closed
* 2bc7f1b removed bissenbay, thanks for your contributions!
* bcee979 :bug: fix some flake8 complains
* 6d4f9c6 :sparkles: add a little more linky footer to PRs
* 6e73e1c Thoth Labelmanager (#656)
* 1503c55 :arrow_up: Automatic update of dependencies by kebechet. (#666)
* fde6c29 Release of version 1.2.3 (#667)
* 234561a :arrow_up: Automatic update of dependencies by kebechet. (#660)
* 08a2bd9 :arrow_up: Automatic update of dependencies by kebechet. (#658)
* 404611c :arrow_up: Automatic update of dependencies by kebechet. (#655)
* efe2bd3 add a little more linky footer to PRs (#607)
* 2759bf7 :arrow_up: Automatic update of dependencies by kebechet. (#651)
* 6af3cbb fix the name of the imagestream to-be looked up (#650)
* 7638eaa Release of version 1.2.2 (#649)
* 5ff99b8 Relock to fix typing_extensions relock (#646)
* 95fa654 Update OWNERS
* f00ee55 Missing typing extensions (#645)
* 6285c35 Release of version 1.2.1 (#642)
* bb91e53 port to python38 (#621)
* b3d521b Release of version 1.2.0 (#638)
* 7142740 :arrow_up: Automatic update of dependencies by kebechet. (#636)
* 589096d statisfy the need of python38-devel libraries (#635)
* b90b12c newline adjustment for consistency of body for kinda issues (#631)
* f25f991 Fixed wrong function accessed (#633)
* 63e470c :arrow_up: Automatic update of dependencies by kebechet. (#630)
* b76ea6d Added warning if release tag is missing. (#628)
* 350f6d0 Slug wrongly set (#627)
* c232d45 Release of version 1.1.4 (#626)
* 0ab7e82 The release PR should close the issue (#606)
* 6bc8eda Release of version 1.1.3 (#624)
* b5c1b9e Req was using pipenv 2018 (#615)
* 940a8cd :arrow_up: Automatic update of dependencies by kebechet. (#613)
* 08f6217 Add Sai to project owners (#611)
* 3504427 Add AICOE Config (#600)
* 794addb Release of version 1.1.2 (#604)
* c828965 Updated to pipenv 2020 (#602)
* 90b47cf Release of version 1.1.1 (#599)
* 16f08c4 Update manager non-atomic updates (#597)
* 91adb2b Release of version 1.1.0 (#596)
* 78fb080 Added modifications to use gitpython (#594)
* 601092e :honeybee: upgrade pip for kebechet container image (#593)
* 5f86532 Release of version 1.0.10 (#592)
* 6dc98a7 Updated source-management and fixed version test (#590)
* 350720e Remove unnecessary quotes (#589)
* 0f5649f Enabled github app authentication (#587)
* 4103cac precommit happy
* 8375e81 Link formatted
* e538ed0 added a clickable link to readme
* 7661f51 :sparkles: :pencil: updated the readme, now we deploy via kustomize rather than ansible
* 09a2cde Precommit fixes
* 57c7319 Added reminder to add to thoth stroage
* 7590c61 Fix typo
* 4b54a15 Add manual request example
* 3070ad7 Release of version 1.0.9
* 45a98c8 Updated glyph
* 6c5fa10 updated github templates
* 068d108 Make pre-commit happy
* e6c0c59 Fixed version test
* 7c132b5 Release of version 1.0.8
* ec1ba02 Updated glyph to 0.13
* 26b8356 Release of version 1.0.7
* cbb0a9c Updated dependencies
* 1248793 fixed imports
* 35f7d70 Release of version 1.0.6
* 6b540c8 Update versions
* 89fc283 Release of version 1.0.5
* 9320519 Update .thoth.yaml
* 0fc9648 :pushpin: Automatic update of dependency gitpython from 3.1.7 to 3.1.8
* 1dbdd99 :pushpin: Automatic update of dependency thoth-glyph from 0.1.0 to 0.1.1
* 94b29b2 :pushpin: Automatic update of dependency sentry-sdk from 0.17.0 to 0.17.4
* a73e59c :pushpin: Automatic update of dependency thamos from 0.11.1 to 0.12.2
* 27caa45 :pushpin: Automatic update of dependency thoth-common from 0.16.1 to 0.18.2
* b60bf70 Fix formatting when wrong version identifier is found
* 889db03 Fix reStructuredText issues
* ce4d02e Release of version 1.0.4
* 2b1f43a Add GitHub's PR template
* 850cd0f Skip empty new lines in update manager
* 43b695d Update requirements.txt
* 091354e Revert "Updated to pipenv 2020.8.13 and locked"
* 4f1c40e Release of version 1.0.3
* b7acd8f Updated to pipenv 2020.8.13 and locked
* 51c04d3 Release of version 1.0.2
* 8e45ede Fix GitHub templates location
* 6d380f7 Fix formatting when smart changelogs are created
* 2f9af40 Enable smart logs by default
* 87b98f7 Add release templates to let Kebechet release itself
* 94e92cf Fixed added context to multiple version string error.
* f10e3fa :pushpin: Automatic update of dependency pytest-cov from 2.10.0 to 2.10.1 (#490)
* 31fc729 :pushpin: Automatic update of dependency thamos from 0.11.0 to 0.11.1 (#489)
* f9c3062 :pushpin: Automatic update of dependency thoth-common from 0.16.0 to 0.16.1 (#488)
* 3e849b2 Document CHANGELOG.md file generation and assignees (#487)
* d2f49bf Minor fix
* 88c9fc9 ThothGlyphException import added
* 370af46 return statement added in Glyph exception
* c504f38 Extra line removed
* 9c60e4d String concatenation fix
* 291bd45 Minor fix
* 8a96dfe Updated Version Manager's README to include Glyph's specifications
* b87e82f Pipfile updated, Glyph's exceptions handled
* fbe6429 Optionally generate intelligent release logs using Glyph
* 4c02a44 return statement added in Glyph exception
* 8a711e0 Extra line removed
* 8480639 :pushpin: Automatic update of dependency thamos from 0.10.6 to 0.11.0 (#486)
* 0a07f6f String concatenation fix
* ec8fc50 Minor fix
* 9b252e7 Updated Version Manager's README to include Glyph's specifications
* 0ee48bc Pipfile updated, Glyph's exceptions handled
* 8e4a78a Optionally generate intelligent release logs using Glyph
* 5038929 :pushpin: Automatic update of dependency pytest from 5.4.3 to 6.0.1 (#482)
* fdaa79d :pushpin: Automatic update of dependency pytest from 5.4.3 to 6.0.1 (#481)
* f45aae2 :pushpin: Automatic update of dependency thoth-common from 0.14.2 to 0.16.0 (#480)
* 8d9e2ac Formatted commit messages with backticks. (#477)
* 53f3736 :pushpin: Automatic update of dependency pytest-timeout from 1.4.1 to 1.4.2 (#476)
* 4bf8e95 :pushpin: Automatic update of dependency pytest-timeout from 1.4.1 to 1.4.2 (#475)
* 2e68bf8 :pushpin: Automatic update of dependency thoth-common from 0.14.1 to 0.14.2 (#474)
* da810f4 Relock fix  (#468)
* 50c7394 :pushpin: Automatic update of dependency gitpython from 3.1.3 to 3.1.7 (#471)
* a8b3111 :pushpin: Automatic update of dependency thamos from 0.10.5 to 0.10.6 (#472)
* 0f67b2b Precommit fixes (#470)
* 01476fb Cronjob cleanup-job can be archived
* 0806d68 :pushpin: Automatic update of dependency thoth-common from 0.13.13 to 0.14.1
* 2c09ce3 keep the application up-to-date with pre-commit
* e1e653d Remove thoth-station/package-analyzer
* 4ca0587 Update version manager documentation
* 1a6273e Add CodeQL security scanning (#425)
* c09d036 Remove build-analyzers
* 91396d2 Update OWNERS
* 93b6990 Remove graph-sync-scheduler
* 53c4df6 Update OWNERS
* 71b0c3d Remove result-api and workload-operator
* ccc73a7 :pushpin: Automatic update of dependency thoth-common from 0.13.12 to 0.13.13
* ab3ba6e :pushpin: Automatic update of dependency thoth-sourcemanagement from 0.2.9 to 0.3.0
* 899ef6f Limit version release log to 300
* 6816a09 keep wf for SLI
* 8941a23 Make config parsing more safe
* 8af17cb Piplock using 2018
* b6c31a4 Pin older version of Pipenv during the build
* 67d39de :pushpin: Automatic update of dependency requests from 2.23.0 to 2.24.0
* 52b01dc Added python 3.8
* 9fdf5bc New piplock
* 80421a5 :pushpin: Automatic update of dependency thoth-common from 0.13.11 to 0.13.12
* 2ebf415 Fix attribute error while parsing YAML
* c921f46 Fix if maintainers are not stated in OWNERS file
* 97a5fc3 Change logger to info to monitor on cluster
* 751d818 :pushpin: Automatic update of dependency pytest-timeout from 1.4.0 to 1.4.1
* 97001c5 :pushpin: Automatic update of dependency semver from 2.10.1 to 2.10.2
* e368adc :pushpin: Automatic update of dependency pytest-cov from 2.9.0 to 2.10.0
* 3d2bf1e :pushpin: Automatic update of dependency pytest-timeout from 1.3.4 to 1.4.0
* ea7e600 Remove old member
* 8ba9cff fresh piplock
* 41000f1 str cast moved to return
* b221e89 Typo fix
* 7074eb6 Coala errors
* 9f4132e Perform manual update of dependencies
* e14dcab Release of version 1.0.1
* 75f9473 Add repo for solver error classifier
* 9d1b8ad Correct template
* ed1a65f add pre-commit config
* c8639e3 added a 'tekton trigger tag_release pipeline issue'
* 6cd6256 Add thoth-station/datasets
* 6874675 Add version release for advise-reporter
* fdb23bf :pushpin: Automatic update of dependency pipenv from 2018.11.26 to 2020.5.28
* 5e94c8d Consider app.py and wsgi.py as a source for version
* 2354b37 :pushpin: Automatic update of dependency thoth-common from 0.13.6 to 0.13.7
* 23ae0b5 :pushpin: Automatic update of dependency thamos from 0.10.1 to 0.10.2
* 0150247 :pushpin: Automatic update of dependency pytest-cov from 2.8.1 to 2.9.0
* 8c9b6b8 :pushpin: Automatic update of dependency thoth-common from 0.13.5 to 0.13.6
* 84540a3 :pushpin: Automatic update of dependency thoth-common from 0.13.4 to 0.13.5
* 3a531d7 kebechet should be capitalized
* c8928ef :pushpin: Automatic update of dependency thoth-common from 0.13.3 to 0.13.4
* e50654f Added repo
* 899fa50 Added repo
* b318372 Revert "Fix if automatic relocking PR exists"
* c8889aa :pushpin: Automatic update of dependency thamos from 0.10.0 to 0.10.1
* bac167b :pushpin: Automatic update of dependency pyyaml from 3.13 to 5.3.1
* 97ab871 use source type enum
* 6bc928c remove metadata prefix
* b7b8249 Added update and version to slo
* bec4e66 :pushpin: Automatic update of dependency toml from 0.10.0 to 0.10.1
* 243cde5 :pushpin: Automatic update of dependency semver from 2.10.0 to 2.10.1
* ed958f3 use metadata option when calling thamos advise
* 78203fe Fixed coala errors
* 76410f4 Print version as info
* 36c174d Print version as info
* c8e5d91 Update README.rst
* 1ee5a0a Update README
* 7f6c08e :pushpin: Automatic update of dependency thoth-sourcemanagement from 0.2.7 to 0.2.9
* f60ddfe Fix test imports
* 7f06d1e :pushpin: Automatic update of dependency pytest from 5.4.1 to 5.4.2
* c3cf261 Added sesheta as mainatianer in version manager
* 399722e Added source management
* 1789c48 fixed coala
* ce93a75 coala fix
* c8658c6 Comments on pr if modified pr found.
* aa1f11c :pushpin: Automatic update of dependency semver from 2.9.1 to 2.10.0
* 9b00c4f Fix if automatic relocking pr exists
* 8bc5e26 :pushpin: Automatic update of dependency pylint from 2.5.1 to 2.5.2
* 17447a4 :pushpin: Automatic update of dependency pylint from 2.5.0 to 2.5.1
* fd84e66 :pushpin: Automatic update of dependency gitpython from 3.1.1 to 3.1.2
* f8bf59c :pushpin: Automatic dependency re-locking
* 25a1c7f Fixed coala errors
* 697829a Added instruction for manual trigger and closses issue
* d32039f Added instruction for manual trigger and closses issue"
* 74145f3 :pushpin: Automatic update of dependency thoth-common from 0.13.1 to 0.13.2
* 9b116ca :pushpin: Automatic update of dependency thamos from 0.9.4 to 0.10.0
* 1014c2f Changed image source to infra"
* 4eacb4e :pushpin: Automatic update of dependency thamos from 0.9.3 to 0.9.4
* 4ae9452 :pushpin: Automatic update of dependency thoth-common from 0.13.0 to 0.13.1
* 7695af7 :pushpin: Automatic update of dependency click from 7.1.1 to 7.1.2
* ed24769 Updated name to kebechet
* 75bc473 :pushpin: Automatic update of dependency pylint from 2.4.4 to 2.5.0
* 2aee963 :pushpin: Automatic update of dependency thoth-common from 0.12.10 to 0.13.0
* 4615758 Updated template and workflow to use openshift image
* 799950e Changed template name to kebechet-job
* 37ab272 Added argo workflow and oc template
* 382b352 :pushpin: Automatic update of dependency thoth-common from 0.12.9 to 0.12.10
* 61b4d69 Add SLO-reporter repo
* 04a9003 :pushpin: Automatic update of dependency thamos from 0.9.2 to 0.9.3
* a10efac Added cli endpoint envvar
* f796137 Add maintainer for thamos
* 67c8f58 Changed liveness probe to 45mins.
* 7da21d8 Coala fix
* 7436e15 Coala fix
* 8d30b49 Fix parameters
* 84be060 Fixed run-url cli error
* 9f7777e Fix job template
* 683577f :pushpin: Automatic update of dependency gitpython from 3.1.0 to 3.1.1
* 3205107 Delete thoth_demo.yaml
* d7346d5 Added s2i notebook repos
* 14ad72e :pushpin: Automatic update of dependency thoth-common from 0.12.8 to 0.12.9
* b82da91 :pushpin: Automatic update of dependency thoth-common from 0.12.7 to 0.12.8
* 1bb0cec :pushpin: Automatic update of dependency thoth-common from 0.12.6 to 0.12.7
* 6061c15 :pushpin: Automatic update of dependency thamos from 0.9.1 to 0.9.2
* 118cc04 :pushpin: Automatic update of dependency thoth-sourcemanagement from 0.2.6 to 0.2.7
* 2106de7 :pushpin: Automatic update of dependency thamos from 0.8.1 to 0.9.1
* 1f436a0 :pushpin: Automatic update of dependency thoth-common from 0.10.11 to 0.12.6
* 74e81b3 Removed fstrings
* 2649e08 Fixed coala errors
* 0a0f2b7 removed extra files
* 2d2ad83 Removed try catch
* be28b95 Fixed syntax
* eb81f33 Addressed comments
* eb5355e Added error handling in case version control is used
* b51112c Add support for advise-reporter
* e7d9d1f Support for thoth unresolved-package-handler
* 7dca108 add maintainer for thoth-station/messaging
* 450a3ad :pushpin: Automatic update of dependency pyyaml from 5.3 to 3.13
* cdcb560 :pushpin: Automatic update of dependency pytest from 5.4.0 to 5.4.1
* d1a780a :pushpin: Automatic update of dependency pytest from 5.3.5 to 5.4.0
* 084048a :pushpin: Automatic update of dependency thoth-common from 0.10.9 to 0.10.11
* 672a61b :pushpin: Automatic update of dependency click from 7.0 to 7.1.1
* 9b33348 :pushpin: Automatic update of dependency click from 7.0 to 7.1.1
* 90510da Delete thoth_demo.yaml
* 0015625 fixed coala
* ec6531b fixed coala
* cf16079 Check standard package in package.json
* 8d66b99 fixed commits
* fa2b8eb fixed messages
* b39c85d Revert "Fixed messages and create initial lock commits"
* ab04c4e Fixed messages and create initial lock commits
* 7f006cc Changed namespace to thoth
* 1d8f44a kebechet only uses thoth sourcemanagement
* 04a04f3 removed pin
* 52f074a Fixed dependencies
* d7bf3d0 Latest git python
* 46aef03 Fix cron job run
* ff01fb5 :pushpin: Automatic update of dependency thoth-common from 0.10.8 to 0.10.9
* aa3f858 New Maintainer
* 40b3162 fixed coala
* 65963b8 printin to log
* 32a9bc4 Closes release request if no change
* c5ec71e Adjust .thoth.yaml configuration file
* 4f745eb Handle \r\n
* ed6aa97 A big step towards general AI
* cdb7c2f Fixed lambda x
* 817c60a :pushpin: Automatic update of dependency thoth-common from 0.10.7 to 0.10.8
* 53c206f Fixed ogr migration errors
* 52f3e75 Fixed ogr migration errors
* cfde3cd Fixed ogr migration errors
* c7322d0 :pushpin: Automatic update of dependency requests from 2.22.0 to 2.23.0
* 466a69f Fixed gitlab payload
* 7a5a783 Supporting cron job run
* 8e142ca Added to requirement.txt
* c167c6c Gitlab works with usernames
* 2ff096c Added custom errors
* 7da8b5a Removed IGitt from depedencies
* 1b85778 coala fix
* c1f5630 Updated managers to use ogr methods
* 8d96a5a removed event variable
* 8e0e285 removed event variable
* e240e9a fixed list branches expecting json
* 4a0e47c Removed IGitt from manager base class
* 3cc728e added different id for gitlab
* f8630f5 Added logic for assigning to issue.
* 526e8d6 Added logic for assigning to issue.
* 0db0e9b Added alternate source management
* c97207f OGR Migration
* 0828a21 Now passing the whole payload to the managers.
* 66cea5b ogr changes
* 58f22b9 Adding ogr replacement
* 6665ee3 Fixed coala errors"
* a87b80c Added event conditions to managers
* 5f46e76 Saving parsed dict in parser
* 175a8a7 Added url parse and resolved comments"
* a485cad Update thoth.yaml
* e8fcb27 Update .thoth.yaml
* e4069c1 Added raising exceptions
* d0535fa Added suggested changes
* 2d20454 Add thoth-station/s2i repository
* fcca9ab Support for thoth package-update-job
* f274f00 Fixed coala errors
* 7234879 Added payload parsing
* 23b59a7 Webhook propagated to config.
* 8c678a9 Change cli to recieve payload as string
* 83e91ca Removed nested dictionary
* 56902e3 Fixed typos
* 66a8fd3 Added sub command
* 3d4f0ec Removed demo yaml file
* 21c69ef Added manager back to iter
* 613dc39 changed if condn
* e44b3d5 Fixed coala errors
* e2cd563 Reverted run method
* ce90d34 Fixed coala errors
* e5282d9 Use only slug
* 6154e79 temp close moved
* b71ae07 Run with managers from respective repos
* ca338d4 Introduce second instance of Kebechet
* b557ece :smiling_imp: added durandom_64fbc27e213f5a61c975ab29df94536b88f03270 to Kebechet
* 0db7883 Add new mantainer
* ec18f12 kebechet also support release of AICoE SrcOpsMetrics
* 556c8ce Support for AICoE SrcOpsMetrics
* ab22854 Add new maintainer
* 9b98667 Happy new year!
* 34a15fe Add thoth-station/s2i-thoth repo
* 827482d Fix number attribute error
* ed2156d support graph-backup-job with dependency updates.
* 363428b Add thoth-pybench to monitored repos
* 6fd9e5d Support for AICoE Fraud Detection
* cb0be2f Sort repositories based upon their dependencies
* a832c52 updated templates with annotations
* ca6d133 Use the generic webhook for build trigger
* df39357 github ref point to master
* 198ba2a Fix permission issues
* 7df77ea use /tmp for a .cache directory
* 9ba6901 Adjust Pipenv cache in the correct place
* c45920e Adjust cache location when run in the cluster due to perms
* 295288f :green_heart: added Thoth's Stub-API Repository
* e19f14c :sparkles: added an annotation to each object created, so that we know the version of the template that created the object
* aa8c7a8 Enable version manager for AICoE/prometheus-api-client-python
* 7671cbf Migrate to pytest
* 926d1d9 Add docstrings to satisfy coala linter.
* b03627b Make `v` optional in tag when matching version
* b9a8f9a Support for AICoE  ludus
* 73368de Development packages are not mandatory in Pipfile
* 370a543 added the AICoE repos
* 23219cc Add thoth-station/messaging to monitored repos
* 15bfd99 :lock: relocked
* a16d6d7 Update README.rst
* 85e5550 Fix wrong slug for the sesheta repo
* 4b5562f Do not monitor conu repo
* 596b0e6 Add package-analyzer to monitored repos
* 412ec93 Update templates and cli options
* 618ddfa Propagate deployment name for sentry environment
* c2172eb Add build-analyzers to monitored repos
* c063480 Use UBI8 as base image
* 454f18d Small changes to env names
* b46afd6 Remove osiris and osiris observer
* 6beeaa7 Fix list in YAML
* d1257e7 Update READMEs
* ab72f71 Update READMEs
* e6104f9 Coala formatting
* a53adf9 Combine configuration files
* 347bb13 Addressing comments
* 55f1567 Whoops
* 11fc06e Coala formatting
* e5853ea Review suggestions
* 054f166 Trigger Sesheta
* 9959945 Trigger Sesheta
* a694bcb Add "Finalize version" to accepted titles
* 0111609 Be consistent with issue title case
* 3bc190c Make maintainers case insensitive
* aaa7fe7 CronJobs are now in apiVersion v1beta1
* 74da6a6 Changed env variable names
* 2b7a225 Forgot to save app.sh
* 1fb5688 Adding subcommand should keep original functionality of cronjob
* af5b6f0 Changes based on suggestions
* 1af3c28 Update buildConfig-template.yaml
* e985052 Fixed coala formatting issues
* 472bc93 Fixed origin format
* cd0dd35 Add @harshad16 to maintainers of thoth-lab
* cb4dc6a Removed test values in job template
* 14098c8 Removed test values in job template
* c7f25c3 Forgot to clone repo before doing provenance check
* 9c788b1 Back to docker
* 993c59f cli
* 4a3f8c3 Wrong name for subcommand
* 605e7de app.sh executable
* da58468 Update Pipfile.lock
* 1a0c92c Remove result managers
* c19bf5a Recombined manager but has two distinct logical branches
* efd1287 Single missing quotation
* a85cf16 Merge run-url
* 126954d git tokens are now in secrets
* 057a904 Subcommands
* 68f025c Split thoth managers to remove waiting
* 2d84786 Forgot a line
* 5e1cba7 Changes based on review
* 5d24ec2 Update to work with s2i
* f4f31b6 Updated job template
* 00fced5 Made a services class
* 45d2018 Coala formatting
* 3a592b5 Forgot to save
* a59880e Implemented suggestions
* 59dc2b5 Configure starting deadline seconds to large number
* f177581 Changed to use environment variable
* 60874b7 Creation of kebechet job template
* c8a6e2d Missing period
* b7b01a3 Manual format
* edfbc59 Auto format
* dda8dfa GitLab url run
* 41d273d Manager runs for GitHub
* 86f647e First commit
* c76bcac Add invectio for management
* 7fb6b0a :sparkles: using the new trigger-build zuul job
* e504588 :sparkles: using the new trigger-build zuul job
* ab260e4 :sparkles: using the new trigger-build zuul job
* df3c0ef Add CermakM to list of thoth-lab maintainers
* 9249b4b Update based on suggestions
* 2c5a374 Updated based on suggestions
* be65e2f Added thamos to Pipfile for new managers
* 82b2182 Updated README
* 19a4b3d Logging info as well as auto retrying on Thamos failures
* 07ed2cc Auto format
* 0634256 Remove completed TODOs
* a90a195 Provenance manager (basic) complete
* bbacfda Labels were not being applied
* c6ae64b Automatically opens issues if thoth adviser returns error
* 6e48f58 Updated readme with thamos configuration example
* eefcd8f Removed _advise_wrap in anticpation of thamos.lib.advise_here()
* 9ddb889 Changed name to be more specific
* 889a984 Changed README and removed unnecessary code that was copied over
* cfd6a96 advise and write have been seperated so that if result is error an issue is opened
* 9780c71 Forgot to included init that makes manager accesible
* 574bf80 Basic thoth manager
* a92b0e3 Version manager searches for __about__.py as well
* 9d576a1 :lock: relocked
* b2159e6 Add Francesco to maintainers section of thoth-storages
* 8ddf0c5 Use emojis in commit messages not in pull-request titles
* 47f28d8 :sparkles: now using a bit of gitmoji
* 548c02b Add Thoth's configuration file
* e7a78bb Do not forget to install thoth-common
* 0f14a2c 🔥hotfixing the trailing space...
* 22a572c that part of the webhook url is not required
* d0cf374 Use safe_load() instead of load()
* 6fb5608 Use safe_load() instead of load()
* 81ab226 Kill Kebechet after 2 hours if it was not able compute results
* cd16ee9 Fix coala warning
* 1cf6dd8 Use Thoth's init_logging routine
* 2f59c08 Do not use update manager in graph-sync-scheduler
* 7b39d62 added graph-sync-scheduler to configuration file
* 41d1432 Add init-job to monitored repos
* 7f31658 It's already 2019
* 87a2d78 Add build-watcher to monitored repos
* 338f334 Add @CermakM to maintainers for osiris
* e08f12b Add osiris and osiris build-observer
* c275daa Add operators to monitored repos
* 55eb713 Add thoth-python to monitored repos
* 584bb6c Add long description for PyPI
* 09ff019 Remove markers from requirements file
* f5f76a0 Set env variables to suppress pipenv emojis
* a4fedc7 use thoth-* jobs in pipeline
* 59fd4be added metrics-exports
* 811f826 Monitor AICoE/prometheus-flatliner repository
* 0e63359 Monitor Thoth's management API
* cdca6f7 Lower log level when something goes wrong when running Pipenv
* e1e2b18 Correctly fix attribute error
* 37248a2 Fix attribute error
* e54b368 Propagate issue body to pull request on version updates
* 59dbc8c Add amun-client to monitored repos
* de1e803 Fix wrong manager name
* 3278077 Fix wrong value configuration
* 60ed9c2 Pipenv has been fixed upstream
* fc0b6e1 Fix version manager
* e61f07f Initial dependency lock
* 372e645 Do not forget to install sentry-sdk
* 7db04fa Let Kebechet do the locking
* eb7f062 Fixes to make Kebechet work in deployment
* f09dda7 Add Sentry support
* 0da43c4 Distinguish pip and Pipenv cache
* 671962d New Pipenv does not respect PIPENV_CACHE_DIR
* 7267cb5 A temporary fix to avoid recent Pipenv issues
* a7bfcec Add Amun API repository for monitoring
* 0d59708 Be case insensitive with issue titles triggering new versions
* 49ac058 Fix repo name
* d778de1 Monitor AICoE/log-anomaly-detector for updates
* 9f6e203 put some more labels in, adjusted successfulJobsHistoryLimit
* be53e2d hotfix
* 49899aa added thamos project
* 3d414b5 Fix computing of changelog
* 285d766 Log activities done during changelog computation
* e60465b Enable change log files on Thoth repos
* a394b90 Place related before reported changelog
* e96b9e8 Fix initial lock issues
* c6fa023 added requirements-dev.txt compatibility
* 3e9bedf Update .zuul.yaml
* 208fd37 Add CVE update job to monitored repos
* be9531c An array is expected
* 208ff25 Be consistent with git push
* 1a5156c Configure git on repo clone
* d4b8518 Fix commit
* cd09dfb Fix handling of versions when Pipfile is used
* f52c82b Fix key to packages in Pipfile
* bf827c1 Expand configuration to start using pipfile-requirements
* ce051f1 Fix f-string
* 0ea6ef8 using an obfuscated URL
* 1947206 now with a build trigger in the post pipeline
* 3fd81d2 now with a build trigger in the post pipeline
* 2d05cdf Do not cache images in build config
* 697a23b Version can be stated in version.py
* deaa142 Do calendar release with full year
* 4f858b1 Compute changelog on releases
* 2b08f1d Initial dependency lock
* 05017e9 Remove Pipfile.lock to get initial lock
* fe8c1f9 Print Kebechet version on startup
* 212cfb4 Fix user assignment to issue
* 7786b84 new templates
* d0dea82 added srcops-testing
* fe942c4 Introduce Pipfile requirements.txt manager
* 03f41c6 Assign users to the release issue
* 4885696 Use related instead of fixes
* badc589 Do not tag commits
* d3cc14d Fix tagging of commit
* 0943721 Fix version handling issues
* cd83d9a Another attempt to fix requests issue
* 9105f53 Make sure IGitt does not propagate verify arguments
* d25ff09 Try to fix IGitt requests handling
* e6c66bc Remove duplicit requests
* ed314c2 Make Kebechet compatible with recent IGitt release
* 1816d89 Use dev release of IGitt
* 2fa6868 Install IGitt from git repo correctly
* 0387982 Fix IGitt requirement
* ea7dbc8 Install IGitt from repository
* beb37f1 Do not forget to install semver
* c501b2c Use IGitt directly from git repository for now
* 518e70d Initial dependency lock
* da6c104 Let Kebechet relock dependencies with semver lib
* d17c992 Implement semver and calver for automated releases
* 34d4f78 Inspect also version.py for version information
* 2dcfd01 Minor fixes in README file
* c3becd8 State how version manager looks for version
* 4788cb4 Add user-cont/conu for managing updates
* 88137f5 Fix typo in docs
* e098236 Update README.rst
* 2aedbb1 Fix typo in docs
* 6f811e8 Remove unused import
* 2f7480e Adjusted based on review comments
* a48e90a Last documentation bits
* 9f66ee8 Document managers section
* 81902e8 Update documentation for version manager
* 2aaf282 Update documentation for update manager
* 719df7a Update documentation for info manager
* 3a5f5c1 Create a soft copy for YAML links
* dce4db1 Let only maintainers release new packages
* de85f50 Add version manager for Thoth repos
* e8e3cec Issue handling and minor fixes
* 05eafdb Fix missing packages
* 5ed32c0 Push also tags
* 4d388e8 Implement version change logic
* 4f68995 Introduce version manager for automatic version releases
* 92a62a9 Remove unused arguments
* 2de3f9d Move info messages into correct module
* ec1ccdc Introduce manager configuration entry
* 0e3da53 Initial dependency lock
* 52b9fff Provide README files for managers
* 26cf9d8 Place all managers into their own modules
* 0fd9bbd Pin down gitpython because of IGitt
* 0b3fe02 Ask Kebechet for initial lock
* 7155516 Fix a typo in attribute name
* d92c044 Add Sesheta to monitored repos
* 7f831ed Adjust template labels
* 4e2092c Use description instead of non-existing body attribute
* 9e11ebd Report end run for config entry
* b37958a Fix another subscription error
* 2f5db36 Fix typo
* 91512ff Fix key error exception
* 4350d58 Fix token expanding from env vars
* a7540f1 Install sources directly from GitHub repo
* 71054ad GitLab support fixes and extensions
* 1e669e4 Add GitLab support
* cf78255 Utilize repo cloning
* 022d7e4 Fix bound method call
* f7c2dd6 No need to print context in verbose mode
* bf02aea Hide token in logs
* 7d86865 Fix calling checkout
* 24d783b We have to explicitly install dependency version
* 7a554e2 Install Kebechet from git repo for now
* 03acad2 Initial dependency lock
* 3019e1f Delete Pipfile.lock for relocking dependencies
* 96b18ac Fix hash computation
* 0ce69e0 Run info manager on thoth-station repos
* a0258c8 Introduce managers abstraction
* 47f72c8 Checkout to master after changes
* 6a46157 Fix bound method call
* bc91542 Close initial lock issue when no longer relevant
* 463c5b5 Code refactoring
* 695baee Fix CI failures
* ecdafaf Close no management issue when it is no longer relevant
* 66db401 Report issue on initial lock failure
* dfcba2b Initial dependency locking
* 6838860 Update .zuul.yaml
* 9254a47 Open an issue if no dependency management is found
* f7aaa3b Automatic update of dependency pyyaml from 3.12 to 3.13
* 618ffb4 Report broken build environment
* a13f87c Automatic update of dependency pytest from 3.6.2 to 3.6.3
* 2b74ec0 Delete old branches from remote
* 849373c Automatic update of dependency pipenv from 2018.5.18 to 2018.7.1
* f016848 No need to install it anymore
* e68d5fc Notify about a rebase of pull requests
* 23ab120 Add support for silent bot
* f1b3845 Kebechet now reports issues on GitHub
* 700c6e2 Introduce a wrapper for running pipenv
* 9ef4b52 Improvements in logic
* 84b6d77 Remove pydocstyle from direct dependencies
* 02cda0e just minor wording tweaks
* 635478f renamed KEBECHET_CONFIGURATION to KEBECHET_CONFIGURATION_PATH all over the place
* 54ed1b9 Fix local setup
* ad0a38e some minor tweaks
* 9d220a6 Version 1.0.0
* dde26bf Do not allow pre-releases in updates
* 280853e Simplify code for with statement
* a39a887 Update .zuul.yaml
* eeda128 Install gcc-c++ for native builds
* 1d0e872 using only zuul for releaseing to pypi
* 12f7dbf Version 1.0.0-rc.5
* 0ceedfb Explicitly update dependencies to their latest version
* b2eaee3 Add a generic webhook for triggering builds
* 7d02538 Update __init__.py
* ee59a7a reparing 1.0.0-rc.4
* 36983ff Update .zuul.yaml
* 81d3c71 trigger
* 8433d51 fixing coala Errors
* 3b14e75 added all we need for coala
* ff67621 added the default coala configuration file
* 8b5e1a9 added upload to pypi
* ee16c88 added initial zuul config
* f9c5b55 added initial zuul config
* fdf30a9 Update old PRs on top of the current master
* 5c2d904 Monitor Jupyter Notebook for updates
* decca15 Fix syntax error in Ansible scripts
* 8d94933 Document Kebechet usage and design decisions
* ba26111 implemented Dockerfile, buildconfig, cronjobconfig, configmap templates.
* 948c4c2 updated username to reviewers in OWNERS
* 87574fb Add support for requirements.txt
* 27ea515 Version 1.0.0-rc.2
* 6efadf6 Explicitly name env variables to configure options
* 7f34d2b Add missing pyyaml dependency
* 81ca32f Provide a CLI to run kebechet
* 66146e5 Add missing gitpython dependency
* 61f06fb Add a not for future generations
* c092c81 Create OWNERS
* ef21f6c Remove approve label for auto approval
* 7f374d0 fixed the semver
* 68ab872 added VSCode directory
* 63707b7 Add OpenShift templates
* ebe741e Add configuration file for Thoth
* 4163dd7 Implementation improvements - a first working implementation
* 0e094da Update README.rst
* 72890c5 Initial project import

## Release 1.11.0 (2022-11-14T11:30:44)
* 8c49688 :arrow_up: Automatic update of dependencies by Kebechet for the rhel-8 environment
* 661b908 remove branch creation
* 1c69fea add signing to kebechet commits
* 16c8374 New feature update : Add 'allow' and 'disallow' setting to each manager
* e087552 Add 'env_allow_list' and 'env_disallow_list' setting to each manager
* 6e76af7 :arrow_up: Automatic update of dependencies by Kebechet for the rhel-8 environment
* cb7e541 add line to checkout default branch after pushing changes
* 3b8352c :arrow_up: Automatic update of dependencies by Kebechet for the rhel-8 environment
* a76af37 Create function which respects gh body limits
* 735fffb :arrow_up: Automatic update of dependencies by Kebechet for the rhel-8 environment
* 385bbd0 add check for no PRs opened
* 03bf872 :arrow_up: Automatic update of dependencies by Kebechet for the rhel-8 environment
* 3e697b5 :arrow_up: Automatic update of dependencies by Kebechet for the rhel-8 environment
* e9adaad :arrow_up: Automatic update of dependencies by Kebechet for the rhel-8 environment
* 7211c21 Remove checks for git and local path from pipfile
* bc612c8 :arrow_up: Automatic update of dependencies by Kebechet for the rhel-8 environment
* b81b18f Format package names in GitHub issues

## Release 1.10.5 (2022-09-13T15:27:51)
* eca1171 Type cast the type to pass typechecking (#1138)

## Release 1.10.4 (2022-09-13T12:27:51)
* e4f0671 :arrow_up: Automatic update of dependencies by Kebechet for the rhel-8 environment (#1134)
* a9c3bc5 :arrow_up: Automatic update of dependencies by Kebechet for the rhel-8 environment
* ea8dec8 check to make sure pr exists before attempting rebase on remote branch
* 40f30fe Use lock when updating the dependencies to avoid resource limitations
* 4e5fa9d :arrow_up: Automatic update of dependencies by Kebechet for the rhel-8 environment
* c3b0e8f :arrow_up: Automatic update of dependencies by Kebechet for the rhel-8 environment
* 6d6a243 :arrow_up: Automatic update of dependencies by Kebechet for the rhel-8 environment
* 30e76d2 - Add environment details in PR body with <details> tag (#1120)
* 8f5927d Mask git clone https token from logs (#1124)
* a42f419 Point the closing comment with Pull request link (#1119)
* 3d0eb13 Fix _construct_branch_name() method to avoid conflict while creating branches for different analysis ids
* 07e302b :arrow_up: Automatic update of dependencies by Kebechet for the rhel-8 environment

## Release 1.10.3 (2022-08-08T18:43:45)
* 03b509a :arrow_up: Automatic update of dependencies by Kebechet for the rhel-8 environment
* 20fab3b download owners file from repo
* ba8a06d remove hidden files during os walk
* 3661bd9 call sync when generating dependency graph
* fd5c20a Add configuration for support issue creation
* 0f907e2 :arrow_up: Automatic update of dependencies by Kebechet for the rhel-8 environment (#1105)
* 0c6ac2f Update Dockerfile with cmake dependency
* cdab57c add type annotations for urllib3.util.Url unpacking
* 924d3d0 :arrow_up: Automatic update of dependencies by Kebechet for the rhel-8 environment (#1103)

## Release 1.10.2 (2022-08-01T07:01:46)
* bf81dd2 Fix: Kebechet advise manager starting multiple advice requests Update run() method to prevent adding duplicate runtime_environments from .thoth.yaml
* bbdbd34 :arrow_up: Automatic update of dependencies by Kebechet for the rhel-8 environment
* b405c22 Fix for  referencing incorrect dict keys and Piplock file path
* 5c5238a :arrow_up: Automatic update of dependencies by Kebechet for the rhel-8 environment
* c88a1a0 fix: change the import method of managerbase in release_version
* be9ceae :arrow_up: Automatic update of dependencies by Kebechet for the rhel-8 environment
* b4ccdc0 Process direct dependencies to remove any extra deps
* 6781b02 :arrow_up: Automatic update of dependencies by Kebechet for the rhel-8 environment
* c13e8c6 bugfix: make labels for update manager default to empty list
* f3420d7 :arrow_up: Automatic update of dependencies by Kebechet for the rhel-8 environment
* c8e715d A more informative version manager message around wrong versions

## Release 1.10.1 (2022-07-11T20:27:17)
* 0bb79f6 Issue: Kebechet was picking approvers from it's own OWNERS file
* 521b82f :arrow_up: Automatic update of dependencies by Kebechet for the rhel-8 environment
* 656f71e Fix: Refer key 'parameters' directly
* 3e391b4 :arrow_up: Automatic update of dependencies by Kebechet for the rhel-8 environment
* 18e28dc Issue: https://github.com/thoth-station/kebechet/issues/1050
* db9596f :arrow_up: Automatic update of dependencies by Kebechet for the rhel-8 environment
* 137e855 fetch branch using git.fetch before trying to use it
* 5042936 add documentation for PR labels for version manager

## Release 1.10.0 (2022-06-21T18:05:10)
* 7e7d2c6 :arrow_up: Automatic update of dependencies by Kebechet for the rhel-8 environment
* 4e141c0 :arrow_up: Automatic update of dependencies by Kebechet for the rhel-8 environment (#1066)
* 3fdd416 Issue: Delete the branch if the pr is merged and tag is created
* f8905e7 :arrow_up: Automatic update of dependencies by Kebechet for the rhel-8 environment
* 493eabe :arrow_up: Automatic update of dependencies by Kebechet for the rhel-8 environment
* 65f2936 Address https://github.com/thoth-station/kebechet/pull/1058#pullrequestreview-1001902393
* a3edba2 Update run() method to check the merge PR ,to create TAG and publish
* 3bfa558 Add new util functions
* a6b0e8d :arrow_up: Automatic update of dependencies by Kebechet for the rhel-8 environment (#1057)
* eecb7db Fixing repo typing bug so tests can pass.

## Release 1.9.0 (2022-05-19T17:21:54)
* ba55d4b Add behave tests to Kebechet for 'integration' tests
* 29e8a08 :arrow_up: Automatic update of dependencies by Kebechet for the rhel-8 environment
* bc985bd fix: adjust pipenv cmd limit downward (leave space for dep graph)
* 2148a7f fix: open issue in the case of uninitialized overlay dir
* 18bdf88 fix: cleanup any unused changes to avoid merge conflicts
* 7c6d9de various bugfixes for keb-advise-manager
* d648580 :arrow_up: Automatic update of dependencies by Kebechet for the rhel-8 environment (#1040)
* b2fabb2 :arrow_up: Automatic update of dependencies by Kebechet for the rhel-8 environment
* 52e1438 :arrow_up: Automatic update of dependencies by Kebechet for the rhel-8 environment (#1034)
* 55665f6 env for format
* 057a13a clearer github comment for up to date dependencies
* bfaac03 add more info to no v found issue
* c060090 :arrow_up: Automatic update of dependencies by Kebechet for the rhel-8 environment
* 1a9f59d :arrow_up: Automatic update of dependencies by Kebechet for the rhel-8 environment
* 5afd12f fix mypy precommit errs
* fafbe4c add comment to update issue with PR id
* cef66cf place limit on chars from pipenv command. leave ~5000 for the rest of the issue

## Release 1.8.0 (2022-03-14T14:43:57)
* :arrow_up: Automatic update of dependencies by Kebechet for the rhel-8 environment
* close duplicate release issues when manager is run (#1000)
* :arrow_up: Automatic update of dependencies by Kebechet for the rhel-8 environment
* :arrow_up: Automatic update of dependencies by Kebechet for the rhel-8 environment
* Add links to manager docs in config initialization
* freshness check to avoid duplicating PR
* wrong location for keb metadata was used
* env_name->env
* :arrow_up: Automatic update of dependencies by Kebechet for the rhel-8 environment
* Update OWNERS
* handle case where no packages section exists in Pipfile
* :arrow_up: Automatic update of dependencies by Kebechet for the rhel-8 environment
* :arrow_up: Automatic update of dependencies by Kebechet for the rhel-8 environment
* open issue if no pipenv files are found
* :arrow_up: Automatic update of dependencies by Kebechet for the rhel-8 environment
* :arrow_up: Automatic update of dependencies by Kebechet for the rhel-8 environment
* Update the label to use on issue creation
* Update GitHub issue templates for bugs and features
* Update pre-commit plugins
* :arrow_up: Automatic update of dependencies by Kebechet for the rhel-8 environment
* Add commit hashes to the changelog entries
* handle case where no runtime_envs are defined
* use consistent name for 'has_prev_release'
* :arrow_up: Automatic update of dependencies by Kebechet for the rhel-8 environment
* :arrow_up: Automatic update of dependencies by Kebechet for the rhel-8 environment
* :medal_sports: set badges for easy access to content
* :arrow_up: Automatic update of dependencies by Kebechet for the rhel-8 environment
* :arrow_up: Automatic update of dependencies by Kebechet for the rhel-8 environment
* :arrow_up: Automatic update of dependencies by Kebechet for the rhel-8 environment (#984)

## Release 1.7.3 (2022-01-25T15:31:23)

- use previous tag for computing changelog

## Release 1.7.2 (2022-01-23T15:31:23)

- Add branch for if thoth configuration blocks advise submission
- check before trying to unshallow a repo
- :arrow_up: Automatic update of dependencies by Kebechet for the rhel-8 environment
- pop enabled config
- check before trying to unshallow a repo
- Enable TLS verification
- Unpin fasttext version from Pipfile
- Enable TLS verification in the sample default configuration

## Release 1.7.1 (2022-01-17T15:31:23)

- remove all references to get user
- :arrow_up: Automatic update of dependencies by Kebechet for the rhel-8 environment
- :arrow_up: Automatic update of dependencies by Kebechet for the rhel-8 environment

## Release 1.7.0 (2022-01-13T16:23:54)

- :arrow_up: Automatic update of dependencies by Kebechet for the rhel-8 environment
- use analysis-id 4 branch name to avoid collisions
- add documentation for advise issue
- :arrow_up: Automatic update of dependencies by Kebechet for the rhel-8 environment
- add link to manager doc above managers block in minimal yaml
- update version manager to act on PR merge with labels
- Suggest users to use Thamos CLI to create requirements file
- :arrow_up: Automatic update of dependencies by Kebechet for the rhel-8 environment
- check if update needs rebase

## Release 1.6.8 (2022-01-05T12:38:37)

- Fix the links to each manager's README
- :arrow_up: Automatic update of dependencies by Kebechet for the rhel-8 environment
- :arrow_up: Automatic update of dependencies by Kebechet for the rhel-8 environment
- create_pr for manager class with default value for forknamespace
- use env variable for kebechets name
- :arrow_up: Automatic update of dependencies by Kebechet for the rhel-8 environment
- :arrow_up: Automatic update of dependencies by Kebechet for the rhel-8 environment

## Release 1.6.7 (2021-11-26T18:41:48)

- Fix format string reference to environment name
- :arrow_up: Automatic update of dependencies by Kebechet for the rhel:8 environment
- :arrow_up: Automatic update of dependencies by Kebechet for the rhel:8 environment
- remove kebechet- prefix from version branch (used for image tag)

## Release 1.6.6 (2021-11-18T16:47:27)

- No computed changelog
- if no depth is passed fetch full history
- add kebechet- to all branch names

## Release 1.6.5 (2021-11-17T16:47:27)

- clean repo after using
- :arrow_up: Automatic update of dependencies by Kebechet for the rhel:8 environment

## Release 1.6.4 (2021-11-17T06:47:27)

- check if .git exists so that we don't catch all gitcommand exceptions (#909)
- if we have already cloned to dir, return repo from dir

## Release 1.6.3 (2021-11-16T06:47:27)

- :fire: patch the circuler import fix for keb version in utils
- reraise github server exception

## Release 1.6.2 (2021-11-15T06:47:27)

- Remove the maintainers section from .thoth.yaml
- :arrow_up: Automatic update of dependencies by Kebechet for the rhel:8 environment
- Track advise status using GitHub issue
- patch the fasttext version for build fix

## Release 1.6.1 (2021-11-09T06:47:27)

- add keb version to issue body
- :turtle: Support python 3.9 in kebechet dependency management
- use sphinx for Kebechet documentation

## Release 1.6.0 (2021-11-03T08:32:59)

- add triage/accepted labels to release issue template to prevent Prow from starting a traige
- :arrow_up: Automatic update of dependencies by Kebechet for the rhel:8 environment
- Add Goern, Harshad and Pep as approvers
- :bomb: use https based url in the pre-commit
- allow clone dir to be passed as environment variable
- use approvers section of OWNERS file as default maintainers
- do not report dependency manager exception on support (#878)
- add custom exception for known failure cases and open issues for failed manager
- change key value for getting results from advise endpoint
- set self.runtime_environment and use for all issue titles

## Release 1.5.5 (2021-10-14T18:00:50)

- add checks for num lines to avoid out-of-bounds exception
- patch read write method for changelog update
- checks for num lines to avoid out-of-bounds exception
- :turtle: patch read write method for changelog update
- Automatic update of dependencies by Kebechet for the rhel:8 environment
- :arrow_up: Automatic update of dependencies by Kebechet for the rhel:8 environment
- catch ssl errors as it is a networking issue

## Release 1.5.4 (2021-10-12T14:03:50)

- check if issue already exists
- create changelog file if it doesn't exist

## Release 1.5.3 (2021-10-11T20:43:58)

### Features

- :arrow_up: Automatic update of dependencies by Kebechet for the rhel:8 environment
- :arrow_up: Automatic update of dependencies by Kebechet for the rhel:8 environment
- add enabled flag to manager configuration
- don't require locked version for old deps
- :arrow_up: Automatic update of dependencies by Kebechet for the rhel:8 environment
- add checks for local installations and pkgs bundled by pipenv
- check for none indicating function failed
- create issue if no requirements found for runtime env
- log if issue creation is disabled

  ### Improvements

- make changelog not smart by default

- if PR already exists warn and continue

## Release 1.5.2 (2021-09-27T21:37:47)

### Features

- :arrow_up: Automatic update of dependencies by Kebechet for the rhel:8 environment (#837)
- add KPostOffice to approvers
- only create one issue per exc per line
- Fix markdown format for table rows
- get relative path of overlay currently being updated for link

  ### Improvements

- Minor format improvements in the README

## Release 1.5.1 (2021-09-23T19:16:52)

### Features

- :arrow_up: Automatic update of dependencies by Kebechet for the rhel:8 environment
- :arrow_up: Automatic update of dependencies by Kebechet for the rhel:8 environment
- :arrow_up: Automatic update of dependencies by Kebechet for the rhel:8 environment
- :arrow_up: Automatic update of dependencies by Kebechet for the rhel:8 environment
- add link to repository which caused exception
- :arrow_up: Automatic update of dependencies by Kebechet for the rhel:8 environment
- :arrow_up: Automatic update of dependencies by Kebechet for the rhel:8 environment

  ### Bug Fixes

- :bug: fix some typos

- do not raise issue for conn error

## Release 1.5.0 (2021-09-15T16:02:53)

### Features

- add unregistered manager which adds thoth-config
- convert README from RST to MD
- add return statement

  ### Bug Fixes

- instead of opening issues in user repo open in thoth-station/support

- if requirements.txt does not exist it must be created

  ### Improvements

- updated README files to reflect current state of Kebechet

- pull runtime_environment directly from advise results

- removed unused -dev dependencies

  ### Other

- Format traceback with Python backtick code

## Release 1.4.1 (2021-08-18T16:49:22)

### Features

- Empty commit for a new release

## [1.0.0-rc.4] - 2018-Jun-25 - goern

### Added

Starting with this release we have a Zuul-CI pipeline that:

- lints on Pull Requrest and gate/merge
- uploads to pypi (test) on tag

  ## Release 1.0.1 (2020-06-05T11:15:40)

- Add repo for solver error classifier

- Correct template

- add pre-commit config

- added a 'tekton trigger tag_release pipeline issue'

- Add thoth-station/datasets

- Add version release for advise-reporter

- :pushpin: Automatic update of dependency pipenv from 2018.11.26 to 2020.5.28

- Consider app.py and wsgi.py as a source for version

- :pushpin: Automatic update of dependency thoth-common from 0.13.6 to 0.13.7

- :pushpin: Automatic update of dependency thamos from 0.10.1 to 0.10.2

- :pushpin: Automatic update of dependency pytest-cov from 2.8.1 to 2.9.0

- :pushpin: Automatic update of dependency thoth-common from 0.13.5 to 0.13.6

- :pushpin: Automatic update of dependency thoth-common from 0.13.4 to 0.13.5

- kebechet should be capitalized

- :pushpin: Automatic update of dependency thoth-common from 0.13.3 to 0.13.4

- Added repo
- Added repo
- Revert "Fix if automatic relocking PR exists"
- :pushpin: Automatic update of dependency thamos from 0.10.0 to 0.10.1
- :pushpin: Automatic update of dependency pyyaml from 3.13 to 5.3.1
- use source type enum
- remove metadata prefix
- Added update and version to slo
- :pushpin: Automatic update of dependency toml from 0.10.0 to 0.10.1
- :pushpin: Automatic update of dependency semver from 2.10.0 to 2.10.1
- use metadata option when calling thamos advise
- Fixed coala errors
- Print version as info
- Print version as info
- Update README.rst
- Update README
- :pushpin: Automatic update of dependency thoth-sourcemanagement from 0.2.7 to 0.2.9
- Fix test imports
- :pushpin: Automatic update of dependency pytest from 5.4.1 to 5.4.2
- Added sesheta as mainatianer in version manager
- Added source management
- fixed coala
- coala fix
- Comments on pr if modified pr found.
- :pushpin: Automatic update of dependency semver from 2.9.1 to 2.10.0
- Fix if automatic relocking pr exists
- :pushpin: Automatic update of dependency pylint from 2.5.1 to 2.5.2
- :pushpin: Automatic update of dependency pylint from 2.5.0 to 2.5.1
- :pushpin: Automatic update of dependency gitpython from 3.1.1 to 3.1.2
- :pushpin: Automatic dependency re-locking
- Fixed coala errors
- Added instruction for manual trigger and closses issue
- Added instruction for manual trigger and closses issue"
- :pushpin: Automatic update of dependency thoth-common from 0.13.1 to 0.13.2
- :pushpin: Automatic update of dependency thamos from 0.9.4 to 0.10.0
- Changed image source to infra"
- :pushpin: Automatic update of dependency thamos from 0.9.3 to 0.9.4
- :pushpin: Automatic update of dependency thoth-common from 0.13.0 to 0.13.1
- :pushpin: Automatic update of dependency click from 7.1.1 to 7.1.2
- Updated name to kebechet
- :pushpin: Automatic update of dependency pylint from 2.4.4 to 2.5.0
- :pushpin: Automatic update of dependency thoth-common from 0.12.10 to 0.13.0
- Updated template and workflow to use openshift image
- Changed template name to kebechet-job
- Added argo workflow and oc template
- :pushpin: Automatic update of dependency thoth-common from 0.12.9 to 0.12.10
- Add SLO-reporter repo
- :pushpin: Automatic update of dependency thamos from 0.9.2 to 0.9.3
- Added cli endpoint envvar
- Add maintainer for thamos
- Changed liveness probe to 45mins.
- Coala fix
- Coala fix
- Fix parameters
- Fixed run-url cli error
- Fix job template
- :pushpin: Automatic update of dependency gitpython from 3.1.0 to 3.1.1
- Delete thoth_demo.yaml
- Added s2i notebook repos
- :pushpin: Automatic update of dependency thoth-common from 0.12.8 to 0.12.9
- :pushpin: Automatic update of dependency thoth-common from 0.12.7 to 0.12.8
- :pushpin: Automatic update of dependency thoth-common from 0.12.6 to 0.12.7
- :pushpin: Automatic update of dependency thamos from 0.9.1 to 0.9.2
- :pushpin: Automatic update of dependency thoth-sourcemanagement from 0.2.6 to 0.2.7
- :pushpin: Automatic update of dependency thamos from 0.8.1 to 0.9.1
- :pushpin: Automatic update of dependency thoth-common from 0.10.11 to 0.12.6
- Removed fstrings
- Fixed coala errors
- removed extra files
- Removed try catch
- Fixed syntax
- Addressed comments
- Added error handling in case version control is used
- Add support for advise-reporter
- Support for thoth unresolved-package-handler
- add maintainer for thoth-station/messaging
- :pushpin: Automatic update of dependency pyyaml from 5.3 to 3.13
- :pushpin: Automatic update of dependency pytest from 5.4.0 to 5.4.1
- :pushpin: Automatic update of dependency pytest from 5.3.5 to 5.4.0
- :pushpin: Automatic update of dependency thoth-common from 0.10.9 to 0.10.11
- :pushpin: Automatic update of dependency click from 7.0 to 7.1.1
- :pushpin: Automatic update of dependency click from 7.0 to 7.1.1
- Delete thoth_demo.yaml
- fixed coala
- fixed coala
- Check standard package in package.json
- fixed commits
- fixed messages
- Revert "Fixed messages and create initial lock commits"
- Fixed messages and create initial lock commits
- Changed namespace to thoth
- kebechet only uses thoth sourcemanagement
- removed pin
- Fixed dependencies
- Latest git python
- Fix cron job run
- :pushpin: Automatic update of dependency thoth-common from 0.10.8 to 0.10.9
- New Maintainer
- fixed coala
- printin to log
- Closes release request if no change
- Adjust .thoth.yaml configuration file
- Handle \r\n
- A big step towards general AI
- Fixed lambda x
- :pushpin: Automatic update of dependency thoth-common from 0.10.7 to 0.10.8
- Fixed ogr migration errors
- Fixed ogr migration errors
- Fixed ogr migration errors
- :pushpin: Automatic update of dependency requests from 2.22.0 to 2.23.0
- Fixed gitlab payload
- Supporting cron job run
- Added to requirement.txt
- Gitlab works with usernames
- Added custom errors
- Removed IGitt from depedencies
- coala fix
- Updated managers to use ogr methods
- removed event variable
- removed event variable
- fixed list branches expecting json
- Removed IGitt from manager base class
- added different id for gitlab
- Added logic for assigning to issue.
- Added logic for assigning to issue.
- Added alternate source management
- OGR Migration
- Now passing the whole payload to the managers.
- ogr changes
- Adding ogr replacement
- Fixed coala errors"
- Added event conditions to managers
- Saving parsed dict in parser
- Added url parse and resolved comments"
- Update thoth.yaml
- Update .thoth.yaml
- Added raising exceptions
- Added suggested changes
- Add thoth-station/s2i repository
- Support for thoth package-update-job
- Fixed coala errors
- Added payload parsing
- Webhook propagated to config.
- Change cli to recieve payload as string
- Removed nested dictionary
- Fixed typos
- Added sub command
- Removed demo yaml file
- Added manager back to iter
- changed if condn
- Fixed coala errors
- Reverted run method
- Fixed coala errors
- Use only slug
- temp close moved
- Run with managers from respective repos
- Introduce second instance of Kebechet
- :smiling_imp: added durandom_64fbc27e213f5a61c975ab29df94536b88f03270 to Kebechet
- Add new mantainer
- kebechet also support release of AICoE SrcOpsMetrics
- Support for AICoE SrcOpsMetrics
- Add new maintainer
- Happy new year!
- Add thoth-station/s2i-thoth repo
- Fix number attribute error
- support graph-backup-job with dependency updates.
- Add thoth-pybench to monitored repos
- Support for AICoE Fraud Detection
- Sort repositories based upon their dependencies
- updated templates with annotations
- Use the generic webhook for build trigger
- github ref point to master
- Fix permission issues
- use /tmp for a .cache directory
- Adjust Pipenv cache in the correct place
- Adjust cache location when run in the cluster due to perms
- :green_heart: added Thoth's Stub-API Repository
- :sparkles: added an annotation to each object created, so that we know the version of the template that created the object
- Enable version manager for AICoE/prometheus-api-client-python
- Migrate to pytest
- Add docstrings to satisfy coala linter.
- Make `v` optional in tag when matching version
- Support for AICoE ludus
- Development packages are not mandatory in Pipfile
- added the AICoE repos
- Add thoth-station/messaging to monitored repos
- :lock: relocked
- Update README.rst
- Fix wrong slug for the sesheta repo
- Do not monitor conu repo
- Add package-analyzer to monitored repos
- Update templates and cli options
- Propagate deployment name for sentry environment
- Add build-analyzers to monitored repos
- Use UBI8 as base image
- Small changes to env names
- Remove osiris and osiris observer
- Fix list in YAML
- Update READMEs
- Update READMEs
- Coala formatting
- Combine configuration files
- Addressing comments
- Whoops
- Coala formatting
- Review suggestions
- Trigger Sesheta
- Trigger Sesheta
- Add "Finalize version" to accepted titles
- Be consistent with issue title case
- Make maintainers case insensitive
- CronJobs are now in apiVersion v1beta1
- Changed env variable names
- Forgot to save app.sh
- Adding subcommand should keep original functionality of cronjob
- Changes based on suggestions
- Update buildConfig-template.yaml
- Fixed coala formatting issues
- Fixed origin format
- Add @harshad16 to maintainers of thoth-lab
- Removed test values in job template
- Removed test values in job template
- Forgot to clone repo before doing provenance check
- Back to docker
- cli
- Wrong name for subcommand
- app.sh executable
- Update Pipfile.lock
- Remove result managers
- Recombined manager but has two distinct logical branches
- Single missing quotation
- Merge run-url
- git tokens are now in secrets
- Subcommands
- Split thoth managers to remove waiting
- Forgot a line
- Changes based on review
- Update to work with s2i
- Updated job template
- Made a services class
- Coala formatting
- Forgot to save
- Implemented suggestions
- Configure starting deadline seconds to large number
- Changed to use environment variable
- Creation of kebechet job template
- Missing period
- Manual format
- Auto format
- GitLab url run
- Manager runs for GitHub
- First commit
- Add invectio for management
- :sparkles: using the new trigger-build zuul job
- :sparkles: using the new trigger-build zuul job
- :sparkles: using the new trigger-build zuul job
- Add CermakM to list of thoth-lab maintainers
- Update based on suggestions
- Updated based on suggestions
- Added thamos to Pipfile for new managers
- Updated README
- Logging info as well as auto retrying on Thamos failures
- Auto format
- Remove completed TODOs
- Provenance manager (basic) complete
- Labels were not being applied
- Automatically opens issues if thoth adviser returns error
- Updated readme with thamos configuration example
- Removed _advise_wrap in anticpation of thamos.lib.advise_here()
- Changed name to be more specific
- Changed README and removed unnecessary code that was copied over
- advise and write have been seperated so that if result is error an issue is opened
- Forgot to included init that makes manager accesible
- Basic thoth manager
- Version manager searches for **about**.py as well
- :lock: relocked
- Add Francesco to maintainers section of thoth-storages
- Use emojis in commit messages not in pull-request titles
- :sparkles: now using a bit of gitmoji
- Add Thoth's configuration file
- Do not forget to install thoth-common
- 🔥hotfixing the trailing space...
- that part of the webhook url is not required
- Use safe_load() instead of load()
- Use safe_load() instead of load()
- Kill Kebechet after 2 hours if it was not able compute results
- Fix coala warning
- Use Thoth's init_logging routine
- Do not use update manager in graph-sync-scheduler
- added graph-sync-scheduler to configuration file
- Add init-job to monitored repos
- It's already 2019
- Add build-watcher to monitored repos
- Add @CermakM to maintainers for osiris
- Add osiris and osiris build-observer
- Add operators to monitored repos
- Add thoth-python to monitored repos
- Add long description for PyPI
- Remove markers from requirements file
- Set env variables to suppress pipenv emojis
- use thoth-* jobs in pipeline
- added metrics-exports
- Monitor AICoE/prometheus-flatliner repository
- Monitor Thoth's management API
- Lower log level when something goes wrong when running Pipenv
- Correctly fix attribute error
- Fix attribute error
- Propagate issue body to pull request on version updates
- Add amun-client to monitored repos
- Fix wrong manager name
- Fix wrong value configuration
- Pipenv has been fixed upstream
- Fix version manager
- Initial dependency lock
- Do not forget to install sentry-sdk
- Let Kebechet do the locking
- Fixes to make Kebechet work in deployment
- Add Sentry support
- Distinguish pip and Pipenv cache
- New Pipenv does not respect PIPENV_CACHE_DIR
- A temporary fix to avoid recent Pipenv issues
- Add Amun API repository for monitoring
- Be case insensitive with issue titles triggering new versions
- Fix repo name
- Monitor AICoE/log-anomaly-detector for updates
- put some more labels in, adjusted successfulJobsHistoryLimit
- hotfix
- added thamos project
- Fix computing of changelog
- Log activities done during changelog computation
- Enable change log files on Thoth repos
- Place related before reported changelog
- Fix initial lock issues
- added requirements-dev.txt compatibility
- Update .zuul.yaml
- Add CVE update job to monitored repos
- An array is expected
- Be consistent with git push
- Configure git on repo clone
- Fix commit
- Fix handling of versions when Pipfile is used
- Fix key to packages in Pipfile
- Expand configuration to start using pipfile-requirements
- Fix f-string
- using an obfuscated URL
- now with a build trigger in the post pipeline
- now with a build trigger in the post pipeline
- Do not cache images in build config
- Version can be stated in version.py
- Do calendar release with full year
- Compute changelog on releases
- Initial dependency lock
- Remove Pipfile.lock to get initial lock
- Print Kebechet version on startup
- Fix user assignment to issue
- new templates
- added srcops-testing
- Introduce Pipfile requirements.txt manager
- Assign users to the release issue
- Use related instead of fixes
- Do not tag commits
- Fix tagging of commit
- Fix version handling issues
- Another attempt to fix requests issue
- Make sure IGitt does not propagate verify arguments
- Try to fix IGitt requests handling
- Remove duplicit requests
- Make Kebechet compatible with recent IGitt release
- Use dev release of IGitt
- Install IGitt from git repo correctly
- Fix IGitt requirement
- Install IGitt from repository
- Do not forget to install semver
- Use IGitt directly from git repository for now
- Initial dependency lock
- Let Kebechet relock dependencies with semver lib
- Implement semver and calver for automated releases
- Inspect also version.py for version information
- Minor fixes in README file
- State how version manager looks for version
- Add user-cont/conu for managing updates
- Fix typo in docs
- Update README.rst
- Fix typo in docs
- Remove unused import
- Adjusted based on review comments
- Last documentation bits
- Document managers section
- Update documentation for version manager
- Update documentation for update manager
- Update documentation for info manager
- Create a soft copy for YAML links
- Let only maintainers release new packages
- Add version manager for Thoth repos
- Issue handling and minor fixes
- Fix missing packages
- Push also tags
- Implement version change logic
- Introduce version manager for automatic version releases
- Remove unused arguments
- Move info messages into correct module
- Introduce manager configuration entry
- Initial dependency lock
- Provide README files for managers
- Place all managers into their own modules
- Pin down gitpython because of IGitt
- Ask Kebechet for initial lock
- Fix a typo in attribute name
- Add Sesheta to monitored repos
- Adjust template labels
- Use description instead of non-existing body attribute
- Report end run for config entry
- Fix another subscription error
- Fix typo
- Fix key error exception
- Fix token expanding from env vars
- Install sources directly from GitHub repo
- GitLab support fixes and extensions
- Add GitLab support
- Utilize repo cloning
- Fix bound method call
- No need to print context in verbose mode
- Hide token in logs
- Fix calling checkout
- We have to explicitly install dependency version
- Install Kebechet from git repo for now
- Initial dependency lock
- Delete Pipfile.lock for relocking dependencies
- Fix hash computation
- Run info manager on thoth-station repos
- Introduce managers abstraction
- Checkout to master after changes
- Fix bound method call
- Close initial lock issue when no longer relevant
- Code refactoring
- Fix CI failures
- Close no management issue when it is no longer relevant
- Report issue on initial lock failure
- Initial dependency locking
- Update .zuul.yaml
- Open an issue if no dependency management is found
- Automatic update of dependency pyyaml from 3.12 to 3.13
- Report broken build environment
- Automatic update of dependency pytest from 3.6.2 to 3.6.3
- Delete old branches from remote
- Automatic update of dependency pipenv from 2018.5.18 to 2018.7.1
- No need to install it anymore
- Notify about a rebase of pull requests
- Add support for silent bot
- Kebechet now reports issues on GitHub
- Introduce a wrapper for running pipenv
- Improvements in logic
- Remove pydocstyle from direct dependencies
- just minor wording tweaks
- renamed KEBECHET_CONFIGURATION to KEBECHET_CONFIGURATION_PATH all over the place
- Fix local setup
- some minor tweaks

## Release 1.0.2 (2020-08-27T06:36:58)

- Fix GitHub templates location
- Fix formatting when smart changelogs are created
- Enable smart logs by default
- Add release templates to let Kebechet release itself
- Fixed added context to multiple version string error.
- :pushpin: Automatic update of dependency pytest-cov from 2.10.0 to 2.10.1 (#490)
- :pushpin: Automatic update of dependency thamos from 0.11.0 to 0.11.1 (#489)
- :pushpin: Automatic update of dependency thoth-common from 0.16.0 to 0.16.1 (#488)
- Document CHANGELOG.md file generation and assignees (#487)
- Minor fix
- ThothGlyphException import added
- return statement added in Glyph exception
- Extra line removed
- String concatenation fix
- Minor fix
- Updated Version Manager's README to include Glyph's specifications
- Pipfile updated, Glyph's exceptions handled
- Optionally generate intelligent release logs using Glyph
- return statement added in Glyph exception
- Extra line removed
- :pushpin: Automatic update of dependency thamos from 0.10.6 to 0.11.0 (#486)
- String concatenation fix
- Minor fix
- Updated Version Manager's README to include Glyph's specifications
- Pipfile updated, Glyph's exceptions handled
- Optionally generate intelligent release logs using Glyph
- :pushpin: Automatic update of dependency pytest from 5.4.3 to 6.0.1 (#482)
- :pushpin: Automatic update of dependency pytest from 5.4.3 to 6.0.1 (#481)
- :pushpin: Automatic update of dependency thoth-common from 0.14.2 to 0.16.0 (#480)
- Formatted commit messages with backticks. (#477)
- :pushpin: Automatic update of dependency pytest-timeout from 1.4.1 to 1.4.2 (#476)
- :pushpin: Automatic update of dependency pytest-timeout from 1.4.1 to 1.4.2 (#475)
- :pushpin: Automatic update of dependency thoth-common from 0.14.1 to 0.14.2 (#474)
- Relock fix (#468)
- :pushpin: Automatic update of dependency gitpython from 3.1.3 to 3.1.7 (#471)
- :pushpin: Automatic update of dependency thamos from 0.10.5 to 0.10.6 (#472)
- Precommit fixes (#470)
- Cronjob cleanup-job can be archived
- :pushpin: Automatic update of dependency thoth-common from 0.13.13 to 0.14.1
- keep the application up-to-date with pre-commit
- Remove thoth-station/package-analyzer
- Update version manager documentation
- Add CodeQL security scanning (#425)
- Remove build-analyzers
- Update OWNERS
- Remove graph-sync-scheduler
- Update OWNERS
- Remove result-api and workload-operator
- :pushpin: Automatic update of dependency thoth-common from 0.13.12 to 0.13.13
- :pushpin: Automatic update of dependency thoth-sourcemanagement from 0.2.9 to 0.3.0
- Limit version release log to 300
- keep wf for SLI
- Make config parsing more safe
- Piplock using 2018
- Pin older version of Pipenv during the build
- :pushpin: Automatic update of dependency requests from 2.23.0 to 2.24.0
- Added python 3.8
- New piplock
- :pushpin: Automatic update of dependency thoth-common from 0.13.11 to 0.13.12
- Fix attribute error while parsing YAML
- Fix if maintainers are not stated in OWNERS file
- Change logger to info to monitor on cluster
- :pushpin: Automatic update of dependency pytest-timeout from 1.4.0 to 1.4.1
- :pushpin: Automatic update of dependency semver from 2.10.1 to 2.10.2
- :pushpin: Automatic update of dependency pytest-cov from 2.9.0 to 2.10.0
- :pushpin: Automatic update of dependency pytest-timeout from 1.3.4 to 1.4.0
- Remove old member
- fresh piplock
- str cast moved to return
- Typo fix
- Coala errors
- Perform manual update of dependencies
- Release of version 1.0.1
- Add repo for solver error classifier
- Correct template
- add pre-commit config
- added a 'tekton trigger tag_release pipeline issue'
- Add thoth-station/datasets
- Add version release for advise-reporter
- :pushpin: Automatic update of dependency pipenv from 2018.11.26 to 2020.5.28
- Consider app.py and wsgi.py as a source for version
- :pushpin: Automatic update of dependency thoth-common from 0.13.6 to 0.13.7
- :pushpin: Automatic update of dependency thamos from 0.10.1 to 0.10.2
- :pushpin: Automatic update of dependency pytest-cov from 2.8.1 to 2.9.0
- :pushpin: Automatic update of dependency thoth-common from 0.13.5 to 0.13.6
- :pushpin: Automatic update of dependency thoth-common from 0.13.4 to 0.13.5
- kebechet should be capitalized
- :pushpin: Automatic update of dependency thoth-common from 0.13.3 to 0.13.4
- Added repo
- Added repo
- Revert "Fix if automatic relocking PR exists"
- :pushpin: Automatic update of dependency thamos from 0.10.0 to 0.10.1
- :pushpin: Automatic update of dependency pyyaml from 3.13 to 5.3.1
- use source type enum
- remove metadata prefix
- Added update and version to slo
- :pushpin: Automatic update of dependency toml from 0.10.0 to 0.10.1
- :pushpin: Automatic update of dependency semver from 2.10.0 to 2.10.1
- use metadata option when calling thamos advise
- Fixed coala errors
- Print version as info
- Print version as info
- Update README.rst
- Update README
- :pushpin: Automatic update of dependency thoth-sourcemanagement from 0.2.7 to 0.2.9
- Fix test imports
- :pushpin: Automatic update of dependency pytest from 5.4.1 to 5.4.2
- Added sesheta as mainatianer in version manager
- Added source management
- fixed coala
- coala fix
- Comments on pr if modified pr found.
- :pushpin: Automatic update of dependency semver from 2.9.1 to 2.10.0
- Fix if automatic relocking pr exists
- :pushpin: Automatic update of dependency pylint from 2.5.1 to 2.5.2
- :pushpin: Automatic update of dependency pylint from 2.5.0 to 2.5.1
- :pushpin: Automatic update of dependency gitpython from 3.1.1 to 3.1.2
- :pushpin: Automatic dependency re-locking
- Fixed coala errors
- Added instruction for manual trigger and closses issue
- Added instruction for manual trigger and closses issue"
- :pushpin: Automatic update of dependency thoth-common from 0.13.1 to 0.13.2
- :pushpin: Automatic update of dependency thamos from 0.9.4 to 0.10.0
- Changed image source to infra"
- :pushpin: Automatic update of dependency thamos from 0.9.3 to 0.9.4
- :pushpin: Automatic update of dependency thoth-common from 0.13.0 to 0.13.1
- :pushpin: Automatic update of dependency click from 7.1.1 to 7.1.2
- Updated name to kebechet
- :pushpin: Automatic update of dependency pylint from 2.4.4 to 2.5.0
- :pushpin: Automatic update of dependency thoth-common from 0.12.10 to 0.13.0
- Updated template and workflow to use openshift image
- Changed template name to kebechet-job
- Added argo workflow and oc template
- :pushpin: Automatic update of dependency thoth-common from 0.12.9 to 0.12.10
- Add SLO-reporter repo
- :pushpin: Automatic update of dependency thamos from 0.9.2 to 0.9.3
- Added cli endpoint envvar
- Add maintainer for thamos
- Changed liveness probe to 45mins.
- Coala fix
- Coala fix
- Fix parameters
- Fixed run-url cli error
- Fix job template
- :pushpin: Automatic update of dependency gitpython from 3.1.0 to 3.1.1
- Delete thoth_demo.yaml
- Added s2i notebook repos
- :pushpin: Automatic update of dependency thoth-common from 0.12.8 to 0.12.9
- :pushpin: Automatic update of dependency thoth-common from 0.12.7 to 0.12.8
- :pushpin: Automatic update of dependency thoth-common from 0.12.6 to 0.12.7
- :pushpin: Automatic update of dependency thamos from 0.9.1 to 0.9.2
- :pushpin: Automatic update of dependency thoth-sourcemanagement from 0.2.6 to 0.2.7
- :pushpin: Automatic update of dependency thamos from 0.8.1 to 0.9.1
- :pushpin: Automatic update of dependency thoth-common from 0.10.11 to 0.12.6
- Removed fstrings
- Fixed coala errors
- removed extra files
- Removed try catch
- Fixed syntax
- Addressed comments
- Added error handling in case version control is used
- Add support for advise-reporter
- Support for thoth unresolved-package-handler
- add maintainer for thoth-station/messaging
- :pushpin: Automatic update of dependency pyyaml from 5.3 to 3.13
- :pushpin: Automatic update of dependency pytest from 5.4.0 to 5.4.1
- :pushpin: Automatic update of dependency pytest from 5.3.5 to 5.4.0
- :pushpin: Automatic update of dependency thoth-common from 0.10.9 to 0.10.11
- :pushpin: Automatic update of dependency click from 7.0 to 7.1.1
- :pushpin: Automatic update of dependency click from 7.0 to 7.1.1
- Delete thoth_demo.yaml
- fixed coala
- fixed coala
- Check standard package in package.json
- fixed commits
- fixed messages
- Revert "Fixed messages and create initial lock commits"
- Fixed messages and create initial lock commits
- Changed namespace to thoth
- kebechet only uses thoth sourcemanagement
- removed pin
- Fixed dependencies
- Latest git python
- Fix cron job run
- :pushpin: Automatic update of dependency thoth-common from 0.10.8 to 0.10.9
- New Maintainer
- fixed coala
- printin to log
- Closes release request if no change
- Adjust .thoth.yaml configuration file
- Handle \r\n
- A big step towards general AI
- Fixed lambda x
- :pushpin: Automatic update of dependency thoth-common from 0.10.7 to 0.10.8
- Fixed ogr migration errors
- Fixed ogr migration errors
- Fixed ogr migration errors
- :pushpin: Automatic update of dependency requests from 2.22.0 to 2.23.0
- Fixed gitlab payload
- Supporting cron job run
- Added to requirement.txt
- Gitlab works with usernames
- Added custom errors
- Removed IGitt from depedencies
- coala fix
- Updated managers to use ogr methods
- removed event variable
- removed event variable
- fixed list branches expecting json
- Removed IGitt from manager base class
- added different id for gitlab
- Added logic for assigning to issue.
- Added logic for assigning to issue.
- Added alternate source management
- OGR Migration
- Now passing the whole payload to the managers.
- ogr changes
- Adding ogr replacement
- Fixed coala errors"
- Added event conditions to managers
- Saving parsed dict in parser
- Added url parse and resolved comments"
- Update thoth.yaml
- Update .thoth.yaml
- Added raising exceptions
- Added suggested changes
- Add thoth-station/s2i repository
- Support for thoth package-update-job
- Fixed coala errors
- Added payload parsing
- Webhook propagated to config.
- Change cli to recieve payload as string
- Removed nested dictionary
- Fixed typos
- Added sub command
- Removed demo yaml file
- Added manager back to iter
- changed if condn
- Fixed coala errors
- Reverted run method
- Fixed coala errors
- Use only slug
- temp close moved
- Run with managers from respective repos
- Introduce second instance of Kebechet
- :smiling_imp: added durandom_64fbc27e213f5a61c975ab29df94536b88f03270 to Kebechet
- Add new mantainer
- kebechet also support release of AICoE SrcOpsMetrics
- Support for AICoE SrcOpsMetrics
- Add new maintainer
- Happy new year!
- Add thoth-station/s2i-thoth repo
- Fix number attribute error
- support graph-backup-job with dependency updates.
- Add thoth-pybench to monitored repos
- Support for AICoE Fraud Detection
- Sort repositories based upon their dependencies
- updated templates with annotations
- Use the generic webhook for build trigger
- github ref point to master
- Fix permission issues
- use /tmp for a .cache directory
- Adjust Pipenv cache in the correct place
- Adjust cache location when run in the cluster due to perms
- :green_heart: added Thoth's Stub-API Repository
- :sparkles: added an annotation to each object created, so that we know the version of the template that created the object
- Enable version manager for AICoE/prometheus-api-client-python
- Migrate to pytest
- Add docstrings to satisfy coala linter.
- Make `v` optional in tag when matching version
- Support for AICoE ludus
- Development packages are not mandatory in Pipfile
- added the AICoE repos
- Add thoth-station/messaging to monitored repos
- :lock: relocked
- Update README.rst
- Fix wrong slug for the sesheta repo
- Do not monitor conu repo
- Add package-analyzer to monitored repos
- Update templates and cli options
- Propagate deployment name for sentry environment
- Add build-analyzers to monitored repos
- Use UBI8 as base image
- Small changes to env names
- Remove osiris and osiris observer
- Fix list in YAML
- Update READMEs
- Update READMEs
- Coala formatting
- Combine configuration files
- Addressing comments
- Whoops
- Coala formatting
- Review suggestions
- Trigger Sesheta
- Trigger Sesheta
- Add "Finalize version" to accepted titles
- Be consistent with issue title case
- Make maintainers case insensitive
- CronJobs are now in apiVersion v1beta1
- Changed env variable names
- Forgot to save app.sh
- Adding subcommand should keep original functionality of cronjob
- Changes based on suggestions
- Update buildConfig-template.yaml
- Fixed coala formatting issues
- Fixed origin format
- Add @harshad16 to maintainers of thoth-lab
- Removed test values in job template
- Removed test values in job template
- Forgot to clone repo before doing provenance check
- Back to docker
- cli
- Wrong name for subcommand
- app.sh executable
- Update Pipfile.lock
- Remove result managers
- Recombined manager but has two distinct logical branches
- Single missing quotation
- Merge run-url
- git tokens are now in secrets
- Subcommands
- Split thoth managers to remove waiting
- Forgot a line
- Changes based on review
- Update to work with s2i
- Updated job template
- Made a services class
- Coala formatting
- Forgot to save
- Implemented suggestions
- Configure starting deadline seconds to large number
- Changed to use environment variable
- Creation of kebechet job template
- Missing period
- Manual format
- Auto format
- GitLab url run
- Manager runs for GitHub
- First commit
- Add invectio for management
- :sparkles: using the new trigger-build zuul job
- :sparkles: using the new trigger-build zuul job
- :sparkles: using the new trigger-build zuul job
- Add CermakM to list of thoth-lab maintainers
- Update based on suggestions
- Updated based on suggestions
- Added thamos to Pipfile for new managers
- Updated README
- Logging info as well as auto retrying on Thamos failures
- Auto format
- Remove completed TODOs
- Provenance manager (basic) complete
- Labels were not being applied
- Automatically opens issues if thoth adviser returns error
- Updated readme with thamos configuration example
- Removed _advise_wrap in anticpation of thamos.lib.advise_here()
- Changed name to be more specific
- Changed README and removed unnecessary code that was copied over
- advise and write have been seperated so that if result is error an issue is opened
- Forgot to included init that makes manager accesible
- Basic thoth manager
- Version manager searches for **about**.py as well
- :lock: relocked
- Add Francesco to maintainers section of thoth-storages
- Use emojis in commit messages not in pull-request titles
- :sparkles: now using a bit of gitmoji
- Add Thoth's configuration file
- Do not forget to install thoth-common
- 🔥hotfixing the trailing space...
- that part of the webhook url is not required
- Use safe_load() instead of load()
- Use safe_load() instead of load()
- Kill Kebechet after 2 hours if it was not able compute results
- Fix coala warning
- Use Thoth's init_logging routine
- Do not use update manager in graph-sync-scheduler
- added graph-sync-scheduler to configuration file
- Add init-job to monitored repos
- It's already 2019
- Add build-watcher to monitored repos
- Add @CermakM to maintainers for osiris
- Add osiris and osiris build-observer
- Add operators to monitored repos
- Add thoth-python to monitored repos
- Add long description for PyPI
- Remove markers from requirements file
- Set env variables to suppress pipenv emojis
- use thoth-* jobs in pipeline
- added metrics-exports
- Monitor AICoE/prometheus-flatliner repository
- Monitor Thoth's management API
- Lower log level when something goes wrong when running Pipenv
- Correctly fix attribute error
- Fix attribute error
- Propagate issue body to pull request on version updates
- Add amun-client to monitored repos
- Fix wrong manager name
- Fix wrong value configuration
- Pipenv has been fixed upstream
- Fix version manager
- Initial dependency lock
- Do not forget to install sentry-sdk
- Let Kebechet do the locking
- Fixes to make Kebechet work in deployment
- Add Sentry support
- Distinguish pip and Pipenv cache
- New Pipenv does not respect PIPENV_CACHE_DIR
- A temporary fix to avoid recent Pipenv issues
- Add Amun API repository for monitoring
- Be case insensitive with issue titles triggering new versions
- Fix repo name
- Monitor AICoE/log-anomaly-detector for updates
- put some more labels in, adjusted successfulJobsHistoryLimit
- hotfix
- added thamos project
- Fix computing of changelog
- Log activities done during changelog computation
- Enable change log files on Thoth repos
- Place related before reported changelog
- Fix initial lock issues
- added requirements-dev.txt compatibility
- Update .zuul.yaml
- Add CVE update job to monitored repos
- An array is expected
- Be consistent with git push
- Configure git on repo clone
- Fix commit
- Fix handling of versions when Pipfile is used
- Fix key to packages in Pipfile
- Expand configuration to start using pipfile-requirements
- Fix f-string
- using an obfuscated URL
- now with a build trigger in the post pipeline
- now with a build trigger in the post pipeline
- Do not cache images in build config
- Version can be stated in version.py
- Do calendar release with full year
- Compute changelog on releases
- Initial dependency lock
- Remove Pipfile.lock to get initial lock
- Print Kebechet version on startup
- Fix user assignment to issue
- new templates
- added srcops-testing
- Introduce Pipfile requirements.txt manager
- Assign users to the release issue
- Use related instead of fixes
- Do not tag commits
- Add user-cont/conu for managing updates

## Release 1.0.3 (2020-08-27T17:30:24)

### Features

- Release of version 1.0.2
- Fix GitHub templates location
- Fix formatting when smart changelogs are created
- Enable smart logs by default
- Add release templates to let Kebechet release itself
- Fixed added context to multiple version string error.
- ThothGlyphException import added
- return statement added in Glyph exception
- Updated Version Manager's README to include Glyph's specifications
- Pipfile updated, Glyph's exceptions handled
- Optionally generate intelligent release logs using Glyph
- return statement added in Glyph exception
- Updated Version Manager's README to include Glyph's specifications
- Pipfile updated, Glyph's exceptions handled
- Optionally generate intelligent release logs using Glyph
- Formatted commit messages with backticks. (#477)
- Cronjob cleanup-job can be archived
- keep the application up-to-date with pre-commit
- Remove thoth-station/package-analyzer
- Update version manager documentation
- Add CodeQL security scanning (#425)
- Remove build-analyzers
- Update OWNERS
- Remove graph-sync-scheduler
- Update OWNERS
- Limit version release log to 300
- keep wf for SLI
- Piplock using 2018
- Pin older version of Pipenv during the build
- Added python 3.8
- New piplock
- Change logger to info to monitor on cluster
- Remove old member
- fresh piplock
- str cast moved to return
- Coala errors
- Perform manual update of dependencies
- Release of version 1.0.1
- Add repo for solver error classifier
- Correct template
- add pre-commit config
- added a 'tekton trigger tag_release pipeline issue'
- Add thoth-station/datasets
- Add version release for advise-reporter
- Consider app.py and wsgi.py as a source for version
- kebechet should be capitalized
- Added repo
- Added repo
- Revert "Fix if automatic relocking PR exists"
- Added update and version to slo
- use metadata option when calling thamos advise
- Fixed coala errors
- Print version as info
- Print version as info
- Update README.rst
- Update README
- Added sesheta as mainatianer in version manager
- Added source management
- Comments on pr if modified pr found.
- Fix if automatic relocking pr exists
- :pushpin: Automatic dependency re-locking
- Fixed coala errors
- Changed image source to infra"
- Updated name to kebechet
- Changed template name to kebechet-job
- Added argo workflow and oc template
- Add SLO-reporter repo
- Added cli endpoint envvar
- Add maintainer for thamos
- Changed liveness probe to 45mins.
- Fix parameters
- Fixed run-url cli error
- Fix job template
- Delete thoth_demo.yaml
- Added s2i notebook repos
- Removed fstrings
- Fixed coala errors
- Removed try catch
- Fixed syntax
- Addressed comments
- Add support for advise-reporter
- Support for thoth unresolved-package-handler
- add maintainer for thoth-station/messaging
- Delete thoth_demo.yaml
- Revert "Fixed messages and create initial lock commits"
- Fixed messages and create initial lock commits
- Changed namespace to thoth
- Fixed dependencies
- Latest git python
- Fix cron job run
- New Maintainer
- printin to log
- Closes release request if no change
- Adjust .thoth.yaml configuration file
- Handle \r\n
- A big step towards general AI
- Fixed lambda x
- Fixed ogr migration errors
- Fixed ogr migration errors
- Fixed ogr migration errors
- Fixed gitlab payload
- Supporting cron job run
- Added to requirement.txt
- Gitlab works with usernames
- Added custom errors
- Removed IGitt from depedencies
- added different id for gitlab
- Added logic for assigning to issue.
- Added logic for assigning to issue.
- Added alternate source management
- OGR Migration
- Now passing the whole payload to the managers.
- ogr changes
- Adding ogr replacement
- Fixed coala errors"
- Added event conditions to managers
- Saving parsed dict in parser
- Update thoth.yaml
- Update .thoth.yaml
- Added raising exceptions
- Added suggested changes
- Add thoth-station/s2i repository
- Support for thoth package-update-job
- Fixed coala errors
- Added payload parsing
- Webhook propagated to config.
- Change cli to recieve payload as string
- Removed nested dictionary
- Added sub command
- Removed demo yaml file
- Added manager back to iter
- changed if condn
- Fixed coala errors
- Fixed coala errors
- Use only slug
- temp close moved
- Run with managers from respective repos
- Introduce second instance of Kebechet
- :smiling_imp: added durandom_64fbc27e213f5a61c975ab29df94536b88f03270 to Kebechet
- Add new mantainer
- kebechet also support release of AICoE SrcOpsMetrics
- Support for AICoE SrcOpsMetrics
- Add new maintainer
- Happy new year!
- Add thoth-station/s2i-thoth repo
- Fix number attribute error
- support graph-backup-job with dependency updates.
- Add thoth-pybench to monitored repos
- Support for AICoE Fraud Detection
- Sort repositories based upon their dependencies
- updated templates with annotations
- Use the generic webhook for build trigger
- github ref point to master
- Fix permission issues
- Adjust Pipenv cache in the correct place
- :green_heart: added Thoth's Stub-API Repository
- Enable version manager for AICoE/prometheus-api-client-python
- Migrate to pytest
- Add docstrings to satisfy coala linter.
- Make `v` optional in tag when matching version
- Support for AICoE ludus
- Development packages are not mandatory in Pipfile
- added the AICoE repos
- Add thoth-station/messaging to monitored repos
- :lock: relocked
- Update README.rst
- Do not monitor conu repo
- Add package-analyzer to monitored repos
- Update templates and cli options
- Propagate deployment name for sentry environment
- Add build-analyzers to monitored repos
- Use UBI8 as base image
- Small changes to env names
- Fix list in YAML
- Update READMEs
- Update READMEs
- Coala formatting
- Combine configuration files
- Addressing comments
- Whoops
- Coala formatting
- Review suggestions
- Trigger Sesheta
- Trigger Sesheta
- Add "Finalize version" to accepted titles
- Be consistent with issue title case
- Make maintainers case insensitive
- CronJobs are now in apiVersion v1beta1
- Forgot to save app.sh
- Adding subcommand should keep original functionality of cronjob
- Changes based on suggestions
- Update buildConfig-template.yaml
- Fixed coala formatting issues
- Fixed origin format
- Add @harshad16 to maintainers of thoth-lab
- Forgot to clone repo before doing provenance check
- Back to docker
- cli
- Wrong name for subcommand
- app.sh executable
- Update Pipfile.lock
- Remove result managers
- Recombined manager but has two distinct logical branches
- Single missing quotation
- Merge run-url
- git tokens are now in secrets
- Subcommands
- Split thoth managers to remove waiting
- Forgot a line
- Changes based on review
- Update to work with s2i
- Updated job template
- Made a services class
- Coala formatting
- Forgot to save
- Implemented suggestions
- Configure starting deadline seconds to large number
- Creation of kebechet job template
- Missing period
- Manual format
- Auto format
- GitLab url run
- Manager runs for GitHub
- First commit
- Add invectio for management
- :sparkles: using the new trigger-build zuul job
- :sparkles: using the new trigger-build zuul job
- :sparkles: using the new trigger-build zuul job
- Add CermakM to list of thoth-lab maintainers
- Update based on suggestions
- Updated based on suggestions
- Added thamos to Pipfile for new managers
- Updated README
- Logging info as well as auto retrying on Thamos failures
- Auto format
- Remove completed TODOs
- Provenance manager (basic) complete
- Labels were not being applied
- Updated readme with thamos configuration example
- Removed _advise_wrap in anticpation of thamos.lib.advise_here()
- Changed name to be more specific
- Forgot to included init that makes manager accesible
- Basic thoth manager
- Version manager searches for **about**.py as well
- :lock: relocked
- Add Francesco to maintainers section of thoth-storages
- Add Thoth's configuration file
- Do not forget to install thoth-common
- 🔥hotfixing the trailing space...
- that part of the webhook url is not required
- Use safe_load() instead of load()
- Use safe_load() instead of load()
- Fix coala warning
- Use Thoth's init_logging routine
- Do not use update manager in graph-sync-scheduler
- added graph-sync-scheduler to configuration file
- Add init-job to monitored repos
- It's already 2019
- Add build-watcher to monitored repos
- Add @CermakM to maintainers for osiris
- Add operators to monitored repos
- Add thoth-python to monitored repos
- Add long description for PyPI
- Remove markers from requirements file
- Set env variables to suppress pipenv emojis
- added metrics-exports
- Monitor AICoE/prometheus-flatliner repository
- Monitor Thoth's management API
- Fix attribute error
- Add amun-client to monitored repos
- Fix version manager
- Initial dependency lock
- Do not forget to install sentry-sdk
- Let Kebechet do the locking
- Fixes to make Kebechet work in deployment
- Add Sentry support
- Add Amun API repository for monitoring
- Be case insensitive with issue titles triggering new versions
- Fix repo name
- Monitor AICoE/log-anomaly-detector for updates
- hotfix
- added thamos project
- Fix computing of changelog
- Log activities done during changelog computation
- Enable change log files on Thoth repos
- Place related before reported changelog
- Fix initial lock issues
- added requirements-dev.txt compatibility
- Update .zuul.yaml
- Add CVE update job to monitored repos
- An array is expected
- Be consistent with git push
- Configure git on repo clone
- Fix commit
- Fix key to packages in Pipfile
- Expand configuration to start using pipfile-requirements
- Fix f-string
- using an obfuscated URL
- now with a build trigger in the post pipeline
- now with a build trigger in the post pipeline
- Do not cache images in build config
- Version can be stated in version.py
- Do calendar release with full year
- Compute changelog on releases
- Initial dependency lock
- Remove Pipfile.lock to get initial lock
- Print Kebechet version on startup
- Fix user assignment to issue
- new templates
- added srcops-testing
- Introduce Pipfile requirements.txt manager
- Assign users to the release issue
- Do not tag commits
- Fix tagging of commit
- Fix version handling issues
- Remove duplicit requests
- Make Kebechet compatible with recent IGitt release
- Use dev release of IGitt
- Install IGitt from git repo correctly
- Fix IGitt requirement
- Install IGitt from repository
- Do not forget to install semver
- Use IGitt directly from git repository for now
- Initial dependency lock
- Let Kebechet relock dependencies with semver lib
- Inspect also version.py for version information
- State how version manager looks for version
- Add user-cont/conu for managing updates
- Update README.rst
- Remove unused import
- Adjusted based on review comments
- Last documentation bits
- Document managers section
- Update documentation for version manager
- Update documentation for update manager
- Create a soft copy for YAML links
- Let only maintainers release new packages
- Add version manager for Thoth repos
- Fix missing packages
- Push also tags
- Implement version change logic
- Introduce version manager for automatic version releases
- Remove unused arguments
- Introduce manager configuration entry
- Initial dependency lock
- Provide README files for managers
- Place all managers into their own modules
- Pin down gitpython because of IGitt
- Ask Kebechet for initial lock
- Add Sesheta to monitored repos
- Adjust template labels
- Use description instead of non-existing body attribute
- Fix another subscription error
- Fix token expanding from env vars
- Install sources directly from GitHub repo
- GitLab support fixes and extensions
- Add GitLab support
- Utilize repo cloning
- Fix bound method call
- No need to print context in verbose mode
- Hide token in logs
- Fix calling checkout
- We have to explicitly install dependency version
- Install Kebechet from git repo for now
- Initial dependency lock
- Delete Pipfile.lock for relocking dependencies
- Fix hash computation
- Run info manager on thoth-station repos
- Introduce managers abstraction
- Fix bound method call
- Fix CI failures
- Initial dependency locking
- Update .zuul.yaml
- Open an issue if no dependency management is found
- Report broken build environment
- Delete old branches from remote
- Notify about a rebase of pull requests
- Add support for silent bot
- Kebechet now reports issues on GitHub
- Introduce a wrapper for running pipenv
- Improvements in logic
- Remove pydocstyle from direct dependencies
- renamed KEBECHET_CONFIGURATION to KEBECHET_CONFIGURATION_PATH all over the place
- Fix local setup
- Version 1.0.0
- Do not allow pre-releases in updates
- Update .zuul.yaml
- Install gcc-c++ for native builds
- using only zuul for releaseing to pypi
- Version 1.0.0-rc.5
- Explicitly update dependencies to their latest version
- Add a generic webhook for triggering builds
- Update **init**.py
- reparing 1.0.0-rc.4
- Update .zuul.yaml
- trigger
- added the default coala configuration file
- added upload to pypi
- added initial zuul config
- added initial zuul config
- Update old PRs on top of the current master
- Monitor Jupyter Notebook for updates
- implemented Dockerfile, buildconfig, cronjobconfig, configmap templates.
- updated username to reviewers in OWNERS
- Add support for requirements.txt
- Version 1.0.0-rc.2
- Explicitly name env variables to configure options
- Add missing pyyaml dependency
- Provide a CLI to run kebechet
- Add missing gitpython dependency
- Add a not for future generations
- Create OWNERS
- Remove approve label for auto approval
- added VSCode directory
- Add OpenShift templates
- Add configuration file for Thoth
- Update README.rst
- Initial project import

  ### Bug Fixes

- Minor fix

- String concatenation fix

- Minor fix

- String concatenation fix

- Minor fix

- Relock fix (#468)

- Precommit fixes (#470)

- Fix attribute error while parsing YAML

- Fix if maintainers are not stated in OWNERS file

- Typo fix

- fixed coala

- coala fix

- Coala fix

- Coala fix

- Added error handling in case version control is used

- fixed coala
- fixed coala
- fixed commits
- fixed messages
- fixed coala
- coala fix
- fixed list branches expecting json
- Adjust cache location when run in the cluster due to perms
- :sparkles: added an annotation to each object created, so that we know the version of the template that created the object
- Fix wrong slug for the sesheta repo
- Automatically opens issues if thoth adviser returns error
- advise and write have been seperated so that if result is error an issue is opened
- Use emojis in commit messages not in pull-request titles
- Kill Kebechet after 2 hours if it was not able compute results
- Lower log level when something goes wrong when running Pipenv
- Correctly fix attribute error
- Fix wrong manager name
- Fix wrong value configuration
- Pipenv has been fixed upstream
- New Pipenv does not respect PIPENV_CACHE_DIR
- A temporary fix to avoid recent Pipenv issues
- Fix handling of versions when Pipfile is used
- Use related instead of fixes
- Another attempt to fix requests issue
- Make sure IGitt does not propagate verify arguments
- Try to fix IGitt requests handling
- Minor fixes in README file
- Issue handling and minor fixes
- Fix key error exception
- Checkout to master after changes
- Close initial lock issue when no longer relevant
- Close no management issue when it is no longer relevant
- Report issue on initial lock failure
- fixing coala Errors
- Fix syntax error in Ansible scripts
- fixed the semver

  ### Improvements

- Updated to pipenv 2020.8.13 and locked

- Document CHANGELOG.md file generation and assignees (#487)

- Extra line removed

- Extra line removed

- Remove result-api and workload-operator

- Make config parsing more safe

- use source type enum

- Fix test imports

- Added instruction for manual trigger and closses issue

- Added instruction for manual trigger and closses issue"

- Updated template and workflow to use openshift image

- removed extra files

- Check standard package in package.json

- kebechet only uses thoth sourcemanagement

- removed pin

- Updated managers to use ogr methods
- removed event variable
- removed event variable
- Added url parse and resolved comments"
- Fixed typos
- Reverted run method
- use /tmp for a .cache directory
- Remove osiris and osiris observer
- Changed env variable names
- Removed test values in job template
- Removed test values in job template
- Changed to use environment variable
- :sparkles: now using a bit of gitmoji
- Add osiris and osiris build-observer
- use thoth-* jobs in pipeline
- Distinguish pip and Pipenv cache
- put some more labels in, adjusted successfulJobsHistoryLimit
- Implement semver and calver for automated releases
- Fix typo in docs
- Fix typo in docs
- Update documentation for info manager
- Move info messages into correct module
- Fix a typo in attribute name
- Report end run for config entry
- Fix typo
- Code refactoring
- No need to install it anymore
- just minor wording tweaks
- some minor tweaks
- added all we need for coala
- Document Kebechet usage and design decisions
- Implementation improvements - a first working implementation

  ### Non-functional

- Propagate issue body to pull request on version updates

  ### Other

- remove metadata prefix

- Removed IGitt from manager base class

- Changed README and removed unnecessary code that was copied over

- Simplify code for with statement

  ### Automatic Updates

- :pushpin: Automatic update of dependency pytest-cov from 2.10.0 to 2.10.1 (#490)

- :pushpin: Automatic update of dependency thamos from 0.11.0 to 0.11.1 (#489)

- :pushpin: Automatic update of dependency thoth-common from 0.16.0 to 0.16.1 (#488)

- :pushpin: Automatic update of dependency thamos from 0.10.6 to 0.11.0 (#486)

- :pushpin: Automatic update of dependency pytest from 5.4.3 to 6.0.1 (#482)

- :pushpin: Automatic update of dependency pytest from 5.4.3 to 6.0.1 (#481)

- :pushpin: Automatic update of dependency thoth-common from 0.14.2 to 0.16.0 (#480)

- :pushpin: Automatic update of dependency pytest-timeout from 1.4.1 to 1.4.2 (#476)

- :pushpin: Automatic update of dependency pytest-timeout from 1.4.1 to 1.4.2 (#475)

- :pushpin: Automatic update of dependency thoth-common from 0.14.1 to 0.14.2 (#474)

- :pushpin: Automatic update of dependency gitpython from 3.1.3 to 3.1.7 (#471)

- :pushpin: Automatic update of dependency thamos from 0.10.5 to 0.10.6 (#472)

- :pushpin: Automatic update of dependency thoth-common from 0.13.13 to 0.14.1

- :pushpin: Automatic update of dependency thoth-common from 0.13.12 to 0.13.13

- :pushpin: Automatic update of dependency thoth-sourcemanagement from 0.2.9 to 0.3.0

- :pushpin: Automatic update of dependency requests from 2.23.0 to 2.24.0
- :pushpin: Automatic update of dependency thoth-common from 0.13.11 to 0.13.12
- :pushpin: Automatic update of dependency pytest-timeout from 1.4.0 to 1.4.1
- :pushpin: Automatic update of dependency semver from 2.10.1 to 2.10.2
- :pushpin: Automatic update of dependency pytest-cov from 2.9.0 to 2.10.0
- :pushpin: Automatic update of dependency pytest-timeout from 1.3.4 to 1.4.0
- :pushpin: Automatic update of dependency pipenv from 2018.11.26 to 2020.5.28
- :pushpin: Automatic update of dependency thoth-common from 0.13.6 to 0.13.7
- :pushpin: Automatic update of dependency thamos from 0.10.1 to 0.10.2
- :pushpin: Automatic update of dependency pytest-cov from 2.8.1 to 2.9.0
- :pushpin: Automatic update of dependency thoth-common from 0.13.5 to 0.13.6
- :pushpin: Automatic update of dependency thoth-common from 0.13.4 to 0.13.5
- :pushpin: Automatic update of dependency thoth-common from 0.13.3 to 0.13.4
- :pushpin: Automatic update of dependency thamos from 0.10.0 to 0.10.1
- :pushpin: Automatic update of dependency pyyaml from 3.13 to 5.3.1
- :pushpin: Automatic update of dependency toml from 0.10.0 to 0.10.1
- :pushpin: Automatic update of dependency semver from 2.10.0 to 2.10.1
- :pushpin: Automatic update of dependency thoth-sourcemanagement from 0.2.7 to 0.2.9
- :pushpin: Automatic update of dependency pytest from 5.4.1 to 5.4.2
- :pushpin: Automatic update of dependency semver from 2.9.1 to 2.10.0
- :pushpin: Automatic update of dependency pylint from 2.5.1 to 2.5.2
- :pushpin: Automatic update of dependency pylint from 2.5.0 to 2.5.1
- :pushpin: Automatic update of dependency gitpython from 3.1.1 to 3.1.2
- :pushpin: Automatic update of dependency thoth-common from 0.13.1 to 0.13.2
- :pushpin: Automatic update of dependency thamos from 0.9.4 to 0.10.0
- :pushpin: Automatic update of dependency thamos from 0.9.3 to 0.9.4
- :pushpin: Automatic update of dependency thoth-common from 0.13.0 to 0.13.1
- :pushpin: Automatic update of dependency click from 7.1.1 to 7.1.2
- :pushpin: Automatic update of dependency pylint from 2.4.4 to 2.5.0
- :pushpin: Automatic update of dependency thoth-common from 0.12.10 to 0.13.0
- :pushpin: Automatic update of dependency thoth-common from 0.12.9 to 0.12.10
- :pushpin: Automatic update of dependency thamos from 0.9.2 to 0.9.3
- :pushpin: Automatic update of dependency gitpython from 3.1.0 to 3.1.1
- :pushpin: Automatic update of dependency thoth-common from 0.12.8 to 0.12.9
- :pushpin: Automatic update of dependency thoth-common from 0.12.7 to 0.12.8
- :pushpin: Automatic update of dependency thoth-common from 0.12.6 to 0.12.7
- :pushpin: Automatic update of dependency thamos from 0.9.1 to 0.9.2
- :pushpin: Automatic update of dependency thoth-sourcemanagement from 0.2.6 to 0.2.7
- :pushpin: Automatic update of dependency thamos from 0.8.1 to 0.9.1
- :pushpin: Automatic update of dependency thoth-common from 0.10.11 to 0.12.6
- :pushpin: Automatic update of dependency pyyaml from 5.3 to 3.13
- :pushpin: Automatic update of dependency pytest from 5.4.0 to 5.4.1
- :pushpin: Automatic update of dependency pytest from 5.3.5 to 5.4.0
- :pushpin: Automatic update of dependency thoth-common from 0.10.9 to 0.10.11
- :pushpin: Automatic update of dependency click from 7.0 to 7.1.1
- :pushpin: Automatic update of dependency click from 7.0 to 7.1.1
- :pushpin: Automatic update of dependency thoth-common from 0.10.8 to 0.10.9
- :pushpin: Automatic update of dependency thoth-common from 0.10.7 to 0.10.8
- :pushpin: Automatic update of dependency requests from 2.22.0 to 2.23.0
- Automatic update of dependency pyyaml from 3.12 to 3.13
- Automatic update of dependency pytest from 3.6.2 to 3.6.3
- Automatic update of dependency pipenv from 2018.5.18 to 2018.7.1

## Release 1.0.4 (2020-08-31T08:27:38)

### Features

- Add GitHub's PR template
- Skip empty new lines in update manager
- Update requirements.txt

  ### Improvements

- Revert "Updated to pipenv 2020.8.13 and locked"

## Release 1.0.5 (2020-09-11T17:33:31)

### Features

- Update .thoth.yaml
- Fix reStructuredText issues

  ### Bug Fixes

- Fix formatting when wrong version identifier is found

  ### Automatic Updates

- :pushpin: Automatic update of dependency gitpython from 3.1.7 to 3.1.8

- :pushpin: Automatic update of dependency thoth-glyph from 0.1.0 to 0.1.1

- :pushpin: Automatic update of dependency sentry-sdk from 0.17.0 to 0.17.4

- :pushpin: Automatic update of dependency thamos from 0.11.1 to 0.12.2

- :pushpin: Automatic update of dependency thoth-common from 0.16.1 to 0.18.2

## Release 1.0.6 (2020-09-18T10:59:54)

### Features

- Update versions

## Release 1.0.7 (2020-09-21T15:54:56)

### Features

- Updated dependencies

  ### Bug Fixes

- fixed imports

## Release 1.0.8 (2020-09-22T15:13:49)

### Features

- Updated glyph to 0.13

## Release 1.0.9 (2020-09-23T16:20:11)

### Features

- Updated glyph
- updated github templates
- Make pre-commit happy

  ### Improvements

- Fixed version test

## Release 1.0.10 (2020-11-12T19:06:36)

### Features

- Remove unnecessary quotes (#589)
- Enabled github app authentication (#587)
- precommit happy
- Link formatted
- added a clickable link to readme
- Added reminder to add to thoth stroage
- Add manual request example

  ### Bug Fixes

- Updated source-management and fixed version test (#590)

- Precommit fixes

  ### Improvements

- :sparkles: :pencil: updated the readme, now we deploy via kustomize rather than ansible

- Fix typo

## Release 1.1.0 (2020-11-18T18:13:51)

### Features

- :honeybee: upgrade pip for kebechet container image (#593)

  ### Improvements

- Added modifications to use gitpython (#594)

## Release 1.1.1 (2020-11-19T20:26:20)

### Features

- Update manager non-atomic updates (#597)

## Release 1.1.2 (2020-11-20T17:54:27)

### Features

- Updated to pipenv 2020 (#602)

## Release 1.1.3 (2020-11-24T18:20:49)

### Features

- Req was using pipenv 2018 (#615)
- :arrow_up: Automatic update of dependencies by kebechet. (#613)
- Add Sai to project owners (#611)

## Release 1.1.4 (2020-11-24T20:47:19)

### Bug Fixes

- The release PR should close the issue (#606)

## Release 1.2.0 (2020-12-03T20:32:37)

### Features

- statisfy the need of python38-devel libraries (#635)
- Fixed wrong function accessed (#633)
- :arrow_up: Automatic update of dependencies by kebechet. (#630)
- Added warning if release tag is missing. (#628)
- Slug wrongly set (#627)

  ### Improvements

- newline adjustment for consistency of body for kinda issues (#631)

## Release 1.2.1 (2020-12-03T21:47:41)

### Features

- port to python38 (#621)

## Release 1.2.2 (2020-12-04T14:28:28)

### Features

- Update OWNERS
- Missing typing extensions (#645)

  ### Bug Fixes

- Relock to fix typing_extensions relock (#646)

## Release 1.2.3 (2021-01-11T17:45:28)

### Features

- :arrow_up: Automatic update of dependencies by kebechet. (#660)
- :arrow_up: Automatic update of dependencies by kebechet. (#658)
- :arrow_up: Automatic update of dependencies by kebechet. (#655)
- add a little more linky footer to PRs (#607)
- :arrow_up: Automatic update of dependencies by kebechet. (#651)

  ### Bug Fixes

- fix the name of the imagestream to-be looked up (#650)

## Release 1.2.4 (2021-02-01T08:10:16)

### Features

- :arrow_up: Automatic update of dependencies by kebechet. (#687)
- write outputs of pipenv lock -r to output file (#686)
- :arrow_up: Automatic update of dependencies by kebechet. (#685)
- :arrow_up: Automatic update of dependencies by kebechet. (#684)
- :arrow_up: Automatic update of dependencies by kebechet. (#682)
- Automatically close update merge request if no longer relevant (#661)
- :arrow_up: Automatic update of dependencies by kebechet. (#677)
- :arrow_up: Automatic update of dependencies by kebechet. (#668)
- Fixed log message (#673)
- :sparkles: add a little more linky footer to PRs
- Thoth Labelmanager (#656)
- :arrow_up: Automatic update of dependencies by kebechet. (#666)

  ### Bug Fixes

- :bug: fix some flake8 complains

  ### Improvements

- removed bissenbay, thanks for your contributions!

## Release 1.3.0 (2021-06-02T21:26:33)

### Features

- :arrow_up: Automatic update of dependencies by Kebechet (#724)
- :hatched_chick: update the prow resource limits (#723)
- :arrow_up: Automatic update of dependencies by Kebechet
- :arrow_up: Automatic update of dependencies by Kebechet
- :arrow_up: Automatic update of dependencies by Kebechet (#716)
- :arrow_up: Automatic update of dependencies by Kebechet (#713)
- :arrow_up: Automatic update of dependencies by Kebechet
- :arrow_up: Automatic update of dependencies by Kebechet (#709)
- add kebechet metadata when sending request to thamos (#699)
- :arrow_up: Automatic update of dependencies by Kebechet (#708)
- :arrow_up: Automatic update of dependencies by Kebechet (#706)
- :arrow_up: Automatic update of dependencies by Kebechet (#703)
- :arrow_up: Automatic update of dependencies by Kebechet (#697)
- add justification based on metadata if possible
- :arrow_up: Automatic update of dependencies by Kebechet (#695)
- :arrow_up: Automatic update of dependencies by Kebechet (#694)
- :arrow_up: Automatic update of dependencies by Kebechet (#692)
- :arrow_up: Automatic update of dependencies by Kebechet (#691)

  ### Bug Fixes

- :zap: pre-commit fixes for the master branch

- :arrow_up: fix some formatting and update pre-commit plugins

  ### Improvements

- :sparkles: reconfgured CI/CD to use prow and aicoe-ci

  ### Other

- remove thoth-sourcemanagement from Kebechet (#725)

- remove todo

- Delete branch if the pull request has been already closed

## Release 1.3.1 (2021-06-09T11:13:43)

### Features

- Update OWNERS
- add ogr dep to Pipfile
- :arrow_up: Automatic update of dependencies by Kebechet
- :arrow_up: Automatic update of dependencies by Kebechet

## Release 1.3.2 (2021-06-14T06:18:31)

### Features

- use ogr to get app auth token
- pre-commit issue
- Update kebechet/managers/version/version.py
- Fixed prepending when Title exists
- Fixed README to remove legacy example configuration
- changed appending changelog to prepending changelog
- add docs for locally running Kebechet

  ### Bug Fixes

- Fixed small bug in which original changelog was removed

## Release 1.3.3 (2021-06-30T16:07:37)

### Features

- :arrow_up: Automatic update of dependencies by Kebechet
- :arrow_up: Automatic update of dependencies by Kebechet
- pass environment name to managers and add documentation for expected manager behaviour
- update from template project
- add priority/critical-urgent label to all bot related issue templates
- :arrow_up: Automatic update of dependencies by Kebechet
- :arrow_up: updated labels of issue templates

  ### Bug Fixes

- fix issue 746

- fixed bug with unrelated histories where khebhut doesn't create PR

  ### Improvements

- use upstream solution for adding assignees

- use thamos.lib.write_files

## Release 1.4.0 (2021-08-02T08:06:03)

### Features

- :arrow_up: Automatic update of dependencies by Kebechet (#768)
- add args to get access token
- make update manager work with overlays
- :arrow_up: Automatic update of dependencies by Kebechet
- :arrow_up: Automatic update of dependencies by Kebechet
- :sparkles: add some Kubernetes-inspired Labels to Issues opened by Kebechet

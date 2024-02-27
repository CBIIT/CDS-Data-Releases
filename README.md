# CDS-Data-Releases

This repository is designated for managing the release notes of the CDS Data. It contains branches corresponding to various environments such as DEV, QA, STAGE, PROD.

| Environment | Linked Branch |  |
|-------------|---------------|--|
| CDS-PROD    | prod          |🔒|
| CDS-STAGE   | stage         |🔒|
| CDS-QA      | qa            |🔒|
| CDS-DEV     | dev           |🔒|
| CDS-QA2     | qa2           |🔒|
| CDS-DEV2    | dev2          |🔒|

> ❗ **NOTE:** Branches are protected. Direct commits cannot be made to any of these branches.

## Steps to contribute to this repository:

1. Create a new and separate branch based on the "dev" branch, let's call it "xyz". (Ensure to pull the develop branch to keep it up to date before creating a new branch)
2. Make changes on the "xyz" branch; multiple commits are allowed. Commit those changes and push them to GitHub.
3. Create a Pull Request (PR) from "XYZ" to the "dev" branch.
4. Have the Pull Request (PR) reviewed by at least one reviewer to get it approved.
5. The reviewer needs to merge the PR into "dev" (which serves as the base branch for this PR).
6. The reviewer then needs to delete the "xyz" branch to maintain repository cleanliness.

> Here is the flow illustrating how release notes changes will progress from branch: <br />
"XYZ Branch" -PR-> "dev" -PR-> "qa" -PR-> "stage" -PR-> "prod"

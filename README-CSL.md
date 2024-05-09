Ensure master is up-to-date with upstream.

Merge in latest master (fixing conflicts in package name / version);

`git merge master`

`npm install`

Clean up the previous build:

`rm -rf dist`
`git clean -dfX src`

Then make a new build

`npm run build`

* Clone Repo
* cut your branch from main and do the changes in the branch
* Locally run the Repo by using command : redocly preview-docs docs/openapi.yaml
* Veify your changes are working fine locally.
* then update the index.html file using this command : sudo npx @redocly/cli build-docs docs/openapi.yaml -o index.html
* add all the file in your branch, commit, push your changes to your branch.
* then raise a PR against Main branch in github

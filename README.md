—INSTALL—

1. on github.com
  - under avatar in upper right, click "Your profile"
  - click "Edit Profile" button
  - click "Personal access tokens" (in Personal Settings bar on left)
  - add all scopes (?), click "Generate Token" button
  - on next screen, copy personal access token to clipboard

2. in gitnew.shrc file:
  - enter github id as "git_id"
  - enter personal access token (copied from above) as "git_token" variable

3. in .zshrc file
  - add line “source gitnew.shrc”


—USAGE—

usage: gitnew [reponame]

note: if no reponame is provided, current directory name is used

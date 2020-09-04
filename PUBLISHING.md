## Publishing

1. Install vsce `npm install -g vsce`
1. Create a publisher `vsce create-publisher galley-solutions` You will need to use a personal access token from 1password 'Azure Personal Access Token'.
1. In repo directory, `vsce package && vsce publish`

Reference: https://code.visualstudio.com/api/working-with-extensions/publishing-extension

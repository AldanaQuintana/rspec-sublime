Syntax highlighting and completions for rspec
=============================================

1. Install [ApplySyntax package][1] to get targeted syntax definitions and highlighting
2. Under Preferences > Package Settings > ApplySyntax > Settings - User add this rule (under "syntaxes") ```{
        "name": "User/RSpec",
        "rules": [
          {
            "file_name": ".*_spec\\.rb$"
          }
        ]
      }```
2. Go to your User Package folder (usually under  ~/.config/sublime-text-2/Packages/User)
3. Clone this repo

[1]: https://packagecontrol.io/packages/ApplySyntax

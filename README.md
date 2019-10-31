# Change Script Snippets on Markdown


## Enabling snippets tab-completion
In Visual Studio Code, snippets show in IntelliSense (⌃Space) mixed with other suggestions as well as in a dedicated snippet picker (Insert Snippet in the Command Palette). There is also support for tab-completion: Enable it with `"editor.tabCompletion": "on"`, type a snippet prefix, and press Tab to insert a snippet.

source: [Snippets in Visual Studio Code](https://code.visualstudio.com/docs/editor/userdefinedsnippets)

---

## Last update
Updated all variables to use the format `$1` or ```${1:`Label`}```
Snippet example:
```
"login": {
    "prefix": "login",
    "body": [
        "## Login customer's MDM console",
        "	Login to https://$1",
        "		Authenticate with Level 3 account",
        "		Check CI records for credentials",
        "	Organization Group: '${2:`Organization Group`}'",
        ""
    ],
    "description": "Login"
}
```

## Recommended plugins
Markdown Preview Enhanced

## Suggestions

| | URL |
|-|-|
| Visual Studio Code - Editor | [https://code.visualstudio.com/](https://code.visualstudio.com/) |
| Online snippet generator | [https://snippet-generator.app/](https://snippet-generator.app/) |
| Markdown Guide | [https://www.markdownguide.org/](https://www.markdownguide.org/) |

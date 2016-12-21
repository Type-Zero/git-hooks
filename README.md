# git-hooks
TypeZero Technologies Community Git-hooks

Based off of [git-hooks][1]

## Installation
  * Install [git-hooks][1] that supports the community extentions.
  * Make a file called `githooks.json` in the root of your project.
  * Add a hook:
```json
    {
      "pre-commit": {
          "github.com/Type-Zero/git-hooks": [
              "cfnvalidate",
              "swaggervalidate"
          ]
      }
    }
```

[1]:http://git-hooks.github.io/git-hooks/

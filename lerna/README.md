## Installing dependencies

With yarn workspaces you don't need to cd to each packages folder in order to install dependencies, all you gotta do is `$ yarn workspace @lerna-monorepo/<package> add npm-package-name`

If you want to install shared dependencies, `$ yarn add -W --dev typescript prettier eslint`.

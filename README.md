# basic-configs-react-ts-vite-vitest


#### Stack:

- editorconfig file
- Prettier
- ESLint
- React

- typescript-eslint/recommended - a set of rules for TypeScript code validation using ESLint.

- Vite - a tool for building web applications (instead of WebPack).

- Husky - a tool for creating git hooks that allow performing specific actions before or after executing git commands, such as commit, push, and others. It is used to prevent incorrect commits, such as commits without proper prefixes or direct commits to main branches.

- lint-staged - a tool used in conjunction with Husky to prevent code with errors from entering the repository. It allows running code validation commands only for changed files before creating a commit to speed up the process.

- Stylelint - a tool for checking CSS style syntax. It is used to detect and fix errors in writing styles and ensures consistent and clean code styles.

- Commitlint - a tool for checking the correctness of commits. It applies specific rules and templates to commit messages to ensure consistency and understanding of the meaning of each commit. link

- Git hook (pre-commit): - scripts that are automatically executed when certain git commands are run.
Pre-commit hook is a git hook that runs before creating a commit. In this context, it is used to prevent direct commits to main branches (main or develop) to ensure the proper development process through feature branches and pull requests.

- Vitest - a testing framework. Equivalent to Jest.

# P5.js Desktop template

Template repo for p5.js desktop development. Create p5.js art scripts without needing any html or css! Once your art is done, bundle it down with the build command to get your minified js file, then distribute it however you'd like!

## VSCode profile quickstart

If you want to dive right into developing, [here is a vscode profile to copy](https://vscode.dev/profile/github/4c21d073ea0a3ba27aaa1d00c05857af). It contains tools for p5 development such as spellcheck, a live canvas and shortcut for it, prettier, and more.

## Project setup

1. Run your preferred package manager's install script to add packages
2. Create a project folder in the src directory
3. Create a sketch.mjs file in that directory
4. Add any p5 global methods to the global space
   - Example: window.setup = setup
5. Start coding!

## Type checking (Optional)

If you would like type checking in your code, update your jsconfig.json file to look like this:
```json
{
  "compilerOptions": {
    "checkJs": true,
    "allowJs": true,
    "types": ["@types/p5/global.d.ts", "./types/window.d.ts"]
  },
  "include": ["./src/*/*.js", "./src/*/sketch.mjs"]
}
```

# React Form UI Snippets

Snippets for common React form UIs and utilities:
- **Components**: Button, Input, CheckBox, Form (basic), Form with routing
- **Logic**: validateField, onChange handler, validateForm (linked placeholder), form handler (linked placeholder)

## Usage
1. Install from VSIX or Marketplace (after publishing).
2. In React/JS/TS files, type one of the prefixes and press `Tab`:
   - `buttoncomponent`
   - `inputcomponent`
   - `checkboxcomponent`
   - `formcomponent`
   - `formcomponentv2`
   - `validatefield`
   - `onchangehandler`
   - `validateform`
   - `formhandler`

## Developing
- Make changes in `snippets/react-components.code-snippets`.
- Test locally by running VS Code -> `F5` to launch an Extension Development Host.

## Packaging & Publishing
1. Install VSCE: `npm i -g @vscode/vsce`
2. Create a publisher (once): `vsce create-publisher <your-publisher-id>`
3. Bump version in `package.json` (semver).
4. Package: `vsce package` (produces `.vsix`).
5. Publish: `vsce publish` (requires a Personal Access Token from Azure DevOps).

### Notes
- The `validateform` snippet uses a *linked placeholder* for the form state variable: change `loginData` once to update all occurrences.
- The `formhandler` snippet uses a *linked placeholder* for the handler name.

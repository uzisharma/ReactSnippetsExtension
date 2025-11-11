
# React Form UI Snippets

This extension provides a collection of useful React, CSS/SCSS, and utility snippets for building form UIs and pages.

## Included Snippet Files

- **react-components.code-snippets**: React form components and helpers (Button, Input, CheckBox, Form, validateField, onChange, validateForm, form handler)
- **complete-react-page.code-snippets**: Boilerplate for a complete React page
- **react-base.code-snippets**: Base React component structure
- **js-dummy-data.code-snippets**: Dummy data for JS/React development
- **css-snippets.code-snippets**: CSS/SCSS styles for forms, containers, buttons, inputs, and page layouts


## Usage
1. Install from VSIX or Marketplace (after publishing).
2. In supported files, type one of the following prefixes and press `Tab`:

### 1. react-components.code-snippets (React/JS/TS)
   - `buttoncomponent`
   - `inputcomponent`
   - `checkboxcomponent`
   - `formcomponent`
   - `formcomponentv2`
   - `validatefield`
   - `onchangehandler`
   - `validateform`
   - `formhandler`

### 2. complete-react-page.code-snippets (React/JS/TS)
   - `signuppage`
   - `loginpage`
   - `dashboardpage`

### 3. react-base.code-snippets (React/JS/TS)
   - `rfc (react functional component)`
   - `_st (UseState component)`
   - `_stfilename (UseState component with filename)`

### 4. js-dummy-data.code-snippets (React/JS/TS)
   - `inputfields (dummy data for input fields)`

### 5. css-snippets.code-snippets (CSS/SCSS)
   - `globalreset`
   - `pagecenter`
   - `containerbox`
   - `rememberme`
   - `formcontainer`
   - `formheader`
   - `inputcontainer`
   - `btncontainer`
   - `checkboxcontainer`
   - `footercontainer`
   - `authstyles`

## Developing
- Make changes in the relevant file in the `snippets/` folder.
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

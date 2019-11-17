# ATOM IDE CONFIGURATIONS
#### The list of packages and configurations for the Atom IDE

- Colors configurations: `pigments`
- Icons: `file-icon`
- Auto Completing: `emmet`
- Code Preview: `minimap`
- Git Blame: `git-blame`
- Emmet JSX: `emmet-jsx-props`
- Typescript: `atom-typescript`
- Auto indent: `auto-indent`
- Auto Saving: `autosave-onchange`
- Multi Cursor: `multi-cursor-plug`
- SVG Preview: `svg-preview`
- Parenthesis: `rainbow-delimiters`
- Other packages for supporting other languages


#### Atom IDE keymap configurations
```cson
'atom-text-editor':
  'cmd-d': 'editor:duplicate-lines'

'atom-text-editor[data-grammar~="jsx"]:not([mini])':
  'tab': 'emmet:expand-abbreviation-with-tab'

'atom-text-editor[data-grammar~="tsx"]:not([mini])':
  'tab': 'emmet:expand-abbreviation-with-tab'
```

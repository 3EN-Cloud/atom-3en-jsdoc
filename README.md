# Atom 3EN JSDoc package

Atom package for quick jsdoc comment generation.

## Install

```bash
apm install atom-3en-jsdoc
```

## Usage

Control-Shift-d or Control-Shift-j to add comment templates.

To add comments for any piece of code, position the cursor anywhere on the line preceding the line you wish to comment on.
```javascript
/**
 * @function functionComment
 * @description description
 *  
 * @param  {type} argA description
 * @param  {type} argB description
 * @param  {type} argC description
 * @return {type}      description
 */
function functionComment (argA, argB, argC) {
    return 'jsdoc';
}
```

```javascript
/**
 * This is an empty comment
 */
var a = 'A';
```

## Autocontinue

Comments now are automatically continued if the user hits enter (new line event) while inside of a block (/**..etc.).

### Contribute
I'll be adding features periodically, however bug fixes, feature requests, and pull requests are all welcome.

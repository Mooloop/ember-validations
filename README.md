ember-validations
=================

Additional custom validators for [dockyard/ember-validations](https://github.com/dockyard/ember-validations).

## How To Use ##

Just include the validators from /validators into your project after you include Ember Validations.

## Usage ##

### Email ###
Validates an email address.

#### Options ####
  * `allowBlank` - If `true` skips validation if value is empty

```javascript
// Examples
email: { allowBlank: true }
```
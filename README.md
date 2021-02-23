# ☁ CDNF.io YAML Editor

This is an open-source, YAML configuration editor & verification tool.

[The editor is availble on the official website.](https://pantheontech.github.io/cdnf-editor/)

### Important!

The JSON Schema specification [recommends to use](https://json-schema.org/understanding-json-schema/structuring.html?highlight=ref) the _definitions_ key, where all definitions should be located. Then, you should use a _relative path_ to point to the definitions. 

Our implementation [of the JSON schema requires](https://json-schema.org/understanding-json-schema/structuring.html?highlight=ref#using-id-with-ref) a _definitions_ object, if the _ref ID_ links to a definition and does not use a relative path. 

* __Supported__: JSON Schema draft-04 [(and included features, such as valid formats, etc.)](https://json-schema.org/understanding-json-schema/reference/string.html#format)
* __Not supported__: Loading definitions from external URIs 

## Features

* YAML & JSON Schema Validation
* Generating YAML Examples
* Importing & Export of Configurations

## YAML Configuration Validation
Import, or copy & paste a YAML configuration via the three-dot menu in the __Configuration__ tab.

Errors will then be highlighted, against the imported JSON schema. 

## JSON Schema → YAML Example

1. Visit the [CDNF.io YAML Editor website](https://pantheontech.github.io/cdnf-editor/)
2. Import/paste a valid _draft-04_ JSON Schema, or [use the existing example](/examples/schema.json), via the folder icon, in the __JSON Schema__ tab, on the right.
3. Have a look at the generated _Example YAML code_ in the __YAML Example__ tab.

## Examples
We have prepared two examples of YAML files for you to copy & paste into our CDNF.io YAML Editor.

### Invalid YAML File
* Import, or copy & paste [this invalid YAML example](/examples/invalid-yaml.yaml) into the __Configuration__ window

### Valid YAML File
* Import, or copy & paste [this valid YAML example](/examples/valid-yaml.yaml) into the __Configuration__ window

## Feedback
[Leave us your feedback here](https://cdnf.io/contact/) or creaate an __Issue__ in this repository.

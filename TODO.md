- Add {{ .Example }} block 
- add Options for block
- Option: Exclude examples #https://github.com/terraform-docs/terraform-docs/issues/617
- Option: L10/L50 notation #https://github.com/terraform-docs/terraform-docs/issues/605
- Update all the docs
- Add tests

Config Options: 
- Example Folder
  Sets a different folder to be the one holding examples (default is ./examples)
- Include Examples
  Give a list of examples to show
- Exclude Examples
  Give a list of examples to hide
- Limit Examples
  Only take the first X examples. 0 is unlimited. 
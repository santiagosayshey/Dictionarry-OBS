```JSON
{
  "name": "Special Edition",
  "includeCustomFormatWhenRenaming": true,
  "specifications": [
    {
      "name": "Special Edition",
      "implementation": "ReleaseTitleSpecification",
      "negate": false,
      "required": true,
      "fields": {
        "value": "(?<!^)\\b(extended|uncut|director|special|unrated|uncensored|directors)(\\b|\\d)"
      }
    },
    {
      "name": "Not Theatrical ",
      "implementation": "ReleaseTitleSpecification",
      "negate": true,
      "required": true,
      "fields": {
        "value": "Theatrical"
      }
    }
  ]
}
```
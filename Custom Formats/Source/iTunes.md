```JSON
{
  "name": "iTunes",
  "includeCustomFormatWhenRenaming": true,
  "specifications": [
    {
      "name": "iTunes",
      "implementation": "ReleaseTitleSpecification",
      "negate": false,
      "required": false,
      "fields": {
        "value": "\\b(it|itunes)\\b(?=[ ._-]web[ ._-]?(dl|rip)\\b)"
      }
    },
    {
      "name": "iTunes",
      "implementation": "ReleaseTitleSpecification",
      "negate": false,
      "required": true,
      "fields": {
        "value": "\\b(it|itunes)\\b(?=[ ._-]web[ ._-]?(dl|rip)\\b)"
      }
    }
  ]
}
```


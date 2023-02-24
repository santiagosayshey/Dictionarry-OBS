```JSON
{
  "name": "Movies Anywhere",
  "includeCustomFormatWhenRenaming": true,
  "specifications": [
    {
      "name": "Movies Anywhere",
      "implementation": "ReleaseTitleSpecification",
      "negate": false,
      "required": true,
      "fields": {
        "value": "(?<!dts[ .-]?hd[ .-]?)ma\\b(?=.*\\bweb[ ._-]?(dl|rip)\\b)"
      }
    }
  ]
}
```

A collection of custom formats, profile guides and private tracker resources. Heavily inspired by the TRaSH guides.
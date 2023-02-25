## Regular 
```JSON
{
  "name": "HDR10",
  "includeCustomFormatWhenRenaming": true,
  "specifications": [
    {
      "name": "HDR",
      "implementation": "ReleaseTitleSpecification",
      "negate": false,
      "required": true,
      "fields": {
        "value": "\\b(HDR|HDR10|HDR10+|HDR10Plus)\\b"
      }
    },
    {
      "name": "DV",
      "implementation": "ReleaseTitleSpecification",
      "negate": true,
      "required": true,
      "fields": {
        "value": "\\b(DoVi|DV)\\b"
      }
    },
    {
      "name": "FraMeSToR",
      "implementation": "ReleaseGroupSpecification",
      "negate": true,
      "required": true,
      "fields": {
        "value": "\\b(FraMeSToR)\\b"
      }
    },
    {
      "name": "HDR10+",
      "implementation": "ReleaseTitleSpecification",
      "negate": true,
      "required": true,
      "fields": {
        "value": "\\bHDR10Plus|HDR10(\\b\\+)"
      }
    }
  ]
}
```

## FraMeSToR releases

```JSON
{
  "name": "HDR10 ",
  "includeCustomFormatWhenRenaming": true,
  "specifications": [
    {
      "name": "FraMeSToR",
      "implementation": "ReleaseGroupSpecification",
      "negate": false,
      "required": true,
      "fields": {
        "value": "\\b(FraMeSToR)\\b"
      }
    },
    {
      "name": "SDR",
      "implementation": "ReleaseTitleSpecification",
      "negate": true,
      "required": true,
      "fields": {
        "value": "SDR"
      }
    },
    {
      "name": "4K",
      "implementation": "ResolutionSpecification",
      "negate": false,
      "required": true,
      "fields": {
        "value": 2160
      }
    },
    {
      "name": "BLURAY",
      "implementation": "SourceSpecification",
      "negate": false,
      "required": true,
      "fields": {
        "value": 9
      }
    },
    {
      "name": "REMUX",
      "implementation": "ReleaseTitleSpecification",
      "negate": false,
      "required": true,
      "fields": {
        "value": "REMUX"
      }
    },
    {
      "name": "DV",
      "implementation": "ReleaseTitleSpecification",
      "negate": true,
      "required": true,
      "fields": {
        "value": "\\b(DV|DoVi)\\b"
      }
    },
    {
      "name": "HDR10+",
      "implementation": "ReleaseTitleSpecification",
      "negate": true,
      "required": true,
      "fields": {
        "value": "\\bHDR10Plus|HDR10(\\b\\+)"
      }
    }
  ]
}
```
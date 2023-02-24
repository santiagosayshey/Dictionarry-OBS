### WEB Atmos
```JSON
{
  "name": "ATMOS",
  "includeCustomFormatWhenRenaming": true,
  "specifications": [
    {
      "name": "ATMOS",
      "implementation": "ReleaseTitleSpecification",
      "negate": false,
      "required": false,
      "fields": {
        "value": "\\bATMOS(\\b|\\d)"
      }
    },
    {
      "name": "W4NK3R / CtrlHD",
      "implementation": "ReleaseGroupSpecification",
      "negate": true,
      "required": false,
      "fields": {
        "value": "W4NK3R|CtrlHD"
      }
    }
  ]
}
```

## UHD Atmos
```JSON
{
  "name": "ATMOS ",
  "includeCustomFormatWhenRenaming": true,
  "specifications": [
    {
      "name": "W4NK3R / CtrlHD",
      "implementation": "ReleaseTitleSpecification",
      "negate": false,
      "required": true,
      "fields": {
        "value": "W4NK3R|CtrlHD"
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
      "name": "UHD BLURAY",
      "implementation": "SourceSpecification",
      "negate": false,
      "required": true,
      "fields": {
        "value": 9
      }
    },
    {
      "name": "TrueHD",
      "implementation": "ReleaseTitleSpecification",
      "negate": false,
      "required": true,
      "fields": {
        "value": "\\b(TrueHD)\\b"
      }
    }
  ]
}
```
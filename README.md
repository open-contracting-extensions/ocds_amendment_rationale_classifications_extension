# Amendment rationale classifications

Adds a field to the `Amendment` object to classify the rationale for the amendment.

## Legal context

In the European Union, this extension's fields correspond to [eForms BT-140 (Change Reason Code) and BT-200 (Modification Reason Code)](https://docs.ted.europa.eu/eforms/latest/reference/business-terms/). For correspondences to eForms fields, see [OCDS for eForms](https://standard.open-contracting.org/profiles/eforms/latest).

## Example

```json
{
  "tender": {
    "id": "1",
    "amendments": [
      {
        "rationaleClassifications": [
          {
            "id": "update-add",
            "description": "Information updated",
            "scheme": "change-corrig-justification"
          }
        ]
      }
    ]
  }
}
```

## Issues

Report issues for this extension in the [ocds-extensions repository](https://github.com/open-contracting/ocds-extensions/issues), putting the extension's name in the issue's title.

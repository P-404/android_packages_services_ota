# Documentation
### An example of the `deviceName.json` is given below :

```JSON
{
  "response": [
    {
      "datetime": 202102250030,
      "filename": "project-404-4.2-20210225-105403-RIPPA-cas.zip",
      "id": "fed323770dceba2c189f1a84f098111a",
      "romtype": "RIPPA",
      "size": 314572800,
      "url": "https://example.com",
      "version": "4.3",
      "links": {
        "xda": "",
        "supportGroup": "https://telegram.me/project_404",
        "deviceGroup": "https://telegram.me/abcd"
      },
      "changelog": [
        "first change goes here",
        "another change goes here",
        "and another one here"
      ]
    }
  ]
}
```
## Stuff to be noted
- `deviceName` should be in lowercase when creating the json file.
- Changelog list can be extended by adding more lines **(don't add comma after the last string in changelog)**.
- If you don't have any changes just leave changelog empty.
- For `datetime` and `id`, use the _timestamp_ and _MD5 Hash_ that is generated after a successful build.

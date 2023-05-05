# Unity Package Template

Follows Unity Documentation on how to create packages [here](https://docs.unity3d.com/Manual/CustomPackages.html).

Meta files are ignored by this repo. They are added to local .git/info/exclude.

Docs git exclude on [github](https://docs.github.com/en/get-started/getting-started-with-git/ignoring-files) and [git doc](https://git-scm.com/docs/gitignore).

## Usage

Remember to:

1- Add/Change proper .asmdef file to folders in a need basis.
```json
{
    "name": "namespace",
    "references": [ ],
    "includePlatforms": [],
    "excludePlatforms": []
}
```

2 - Update changelog with proper version. Docs link in the file.

3 - Update license.md with needed license. [choose a license](https://choosealicense.com/licenses/mit/).

4 - Update package.json accordingly.
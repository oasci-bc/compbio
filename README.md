# Computational Biology Breadcrumbs

TODO:

## Deploying

We use [bump-my-version](https://github.com/callowayproject/bump-my-version) to release a new version.
This will create a git tag that is used by [poetry-dynamic-version](https://github.com/mtkennerly/poetry-dynamic-versioning) to generate version strings.

However, we are using [Calendar Versioning](https://calver.org/) which means we need to manually specify new versions.
For example, to bump the version to November 8, 2024, you would run the following command after activating the relevant conda environment.

```bash
bump-my-version bump --new-version 2024.11.8
```

After releasing a new version, you need to push and include all tags.

```bash
git push --follow-tags
```

## License

Code contained in this project is released under the [MIT License](https://spdx.org/licenses/MIT.html) as specified in [`LICENSE_CODE`](https://github.com/oasci-bc/compbio/blob/main/LICENSE_CODE.md).
This license grants you the freedom to use, modify, and distribute it as long as you include the original copyright notice contained in [`LICENSE_CODE`](https://github.com/oasci-bc/compbio/blob/main/LICENSE_CODE.md) and the following notice.

> Portions of this code were incorporated and adapted with permission from [Computational Biology Breadcrumbs](https://gitlab.com/oasci/compbio) by OASCI licensed under the [MIT license](https://github.com/oasci-bc/compbio/blob/main/LICENSE_CODE.md).

All other data, information, documentation, and associated content provided within this project are released under the [Creative Commons Attribution-ShareAlike 4.0 International License (CC BY-SA 4.0)](https://creativecommons.org/licenses/by-sa/4.0/) as specified in [`LICENSE_INFO`](https://github.com/oasci-bc/compbio/blob/main/LICENSE_INFO.md).
This means you are free to share and adapt the non-code elements, but you must give appropriate credit to the original source and indicate if changes were made.

> Some content was incorporated and adapted with permission [Computational Biology Breadcrumbs](https://gitlab.com/oasci/compbio) by OASCI licensed under the [CC BY-SA 4.0 license](https://github.com/oasci-bc/compbio/blob/main/LICENSE_INFO.md)

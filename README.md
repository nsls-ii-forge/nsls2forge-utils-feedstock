About nsls2forge-utils
======================

Home: https://github.com/nsls-ii-forge/nsls2forge-utils

Package license: BSD-3-Clause

Feedstock license: BSD-3-Clause

Summary: nsls2forge utilities for packaging



Current build status
====================


<table><tr><td>All platforms:</td>
    <td>
      <a href="https://dev.azure.com/nsls2forge/nsls2forge/_build/latest?definitionId=209&branchName=master">
        <img src="https://dev.azure.com/nsls2forge/nsls2forge/_apis/build/status/nsls2forge-utils-feedstock?branchName=master">
      </a>
    </td>
  </tr>
</table>

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-nsls2forge--utils-green.svg)](https://anaconda.org/nsls2forge/nsls2forge-utils) | [![Conda Downloads](https://img.shields.io/conda/dn/nsls2forge/nsls2forge-utils.svg)](https://anaconda.org/nsls2forge/nsls2forge-utils) | [![Conda Version](https://img.shields.io/conda/vn/nsls2forge/nsls2forge-utils.svg)](https://anaconda.org/nsls2forge/nsls2forge-utils) | [![Conda Platforms](https://img.shields.io/conda/pn/nsls2forge/nsls2forge-utils.svg)](https://anaconda.org/nsls2forge/nsls2forge-utils) |

Installing nsls2forge-utils
===========================

Installing `nsls2forge-utils` from the `nsls2forge` channel can be achieved by adding `nsls2forge` to your channels with:

```
conda config --add channels nsls2forge
```

Once the `nsls2forge` channel has been enabled, `nsls2forge-utils` can be installed with:

```
conda install nsls2forge-utils
```

It is possible to list all of the versions of `nsls2forge-utils` available on your platform with:

```
conda search nsls2forge-utils --channel nsls2forge
```




Updating nsls2forge-utils-feedstock
===================================

If you would like to improve the nsls2forge-utils recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`nsls2forge` channel, whereupon the built conda packages will be available for
everybody to install and use from the `nsls2forge` channel.
Note that all branches in the nsls-ii-forge/nsls2forge-utils-feedstock are
immediately built and any created packages are uploaded, so PRs should be based
on branches in forks and branches in the main repository should only be used to
build distinct package versions.

In order to produce a uniquely identifiable distribution:
 * If the version of a package **is not** being increased, please add or increase
   the [``build/number``](https://conda.io/docs/user-guide/tasks/build-packages/define-metadata.html#build-number-and-string).
 * If the version of a package **is** being increased, please remember to return
   the [``build/number``](https://conda.io/docs/user-guide/tasks/build-packages/define-metadata.html#build-number-and-string)
   back to 0.

Feedstock Maintainers
=====================



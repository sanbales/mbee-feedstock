About mbee
==========

Home: http://www.openmbee.org

Package license: MIT

Feedstock license: BSD 3-Clause

Summary: Model-Based Engineering Environment

The Model-Based Engineering Environment (MBEE) is a modeling collaboration software
that integrates system models with multidisciplinary engineering data and tools.
This enables system models to be a single-source of truth. MBEE allows for model
data to be more accessible across disciplines and skill sets via web-based UI.
The UI enables users to interact with system model data without needing to be a
systems modeler.


Current build status
====================


<table><tr>
    <td>Appveyor</td>
    <td>
      <a href="https://ci.appveyor.com/project/conda-forge/mbee-feedstock/branch/master">
        <img alt="windows" src="https://img.shields.io/appveyor/ci/conda-forge/mbee-feedstock/master.svg?label=Windows">
      </a>
    </td>
  </tr>
    
  <tr>
    <td>Azure</td>
    <td>
      <details>
        <summary>
          <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=&branchName=master">
            <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/mbee-feedstock?branchName=master">
          </a>
        </summary>
        <table>
          <thead><tr><th>Variant</th><th>Status</th></tr></thead>
          <tbody><tr>
              <td>linux</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=&branchName=master">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/mbee-feedstock?branchName=master&jobName=linux&configuration=linux_" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=&branchName=master">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/mbee-feedstock?branchName=master&jobName=osx&configuration=osx_" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>win</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=&branchName=master">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/mbee-feedstock?branchName=master&jobName=win&configuration=win_" alt="variant">
                </a>
              </td>
            </tr>
          </tbody>
        </table>
      </details>
    </td>
  </tr>
![ppc64le disabled](https://img.shields.io/badge/ppc64le-disabled-lightgrey.svg)
</table>

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-mbee-green.svg)](https://anaconda.org/sanbales/mbee) | [![Conda Downloads](https://img.shields.io/conda/dn/sanbales/mbee.svg)](https://anaconda.org/sanbales/mbee) | [![Conda Version](https://img.shields.io/conda/vn/sanbales/mbee.svg)](https://anaconda.org/sanbales/mbee) | [![Conda Platforms](https://img.shields.io/conda/pn/sanbales/mbee.svg)](https://anaconda.org/sanbales/mbee) |

Installing mbee
===============

Installing `mbee` from the `sanbales` channel can be achieved by adding `sanbales` to your channels with:

```
conda config --add channels sanbales
```

Once the `sanbales` channel has been enabled, `mbee` can be installed with:

```
conda install mbee
```

It is possible to list all of the versions of `mbee` available on your platform with:

```
conda search mbee --channel sanbales
```




Updating mbee-feedstock
=======================

If you would like to improve the mbee recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`sanbales` channel, whereupon the built conda packages will be available for
everybody to install and use from the `sanbales` channel.
Note that all branches in the conda-forge/mbee-feedstock are
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

* [@sanbales](https://github.com/sanbales/)


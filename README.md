About tensorflow-metal
======================

Home: https://pypi.org/project/tensorflow-metal/

Package license: MIT

Feedstock license: [BSD-3-Clause](https://github.com/ngam/tensorflow-metal-feedstock/blob/master/LICENSE.txt)

Summary: TensorFlow acceleration for Mac GPUs.

Current build status
====================


<table>
    
  <tr>
    <td>Azure</td>
    <td>
      <details>
        <summary>
          <a href="https://dev.azure.com/ngam/feedstock-builds/_build/latest?definitionId=&branchName=master">
            <img src="https://dev.azure.com/ngam/feedstock-builds/_apis/build/status/tensorflow-metal-feedstock?branchName=master">
          </a>
        </summary>
        <table>
          <thead><tr><th>Variant</th><th>Status</th></tr></thead>
          <tbody><tr>
              <td>osx_64_python3.10.____cpython</td>
              <td>
                <a href="https://dev.azure.com/ngam/feedstock-builds/_build/latest?definitionId=&branchName=master">
                  <img src="https://dev.azure.com/ngam/feedstock-builds/_apis/build/status/tensorflow-metal-feedstock?branchName=master&jobName=osx&configuration=osx_64_python3.10.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_64_python3.8.____cpython</td>
              <td>
                <a href="https://dev.azure.com/ngam/feedstock-builds/_build/latest?definitionId=&branchName=master">
                  <img src="https://dev.azure.com/ngam/feedstock-builds/_apis/build/status/tensorflow-metal-feedstock?branchName=master&jobName=osx&configuration=osx_64_python3.8.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_64_python3.9.____cpython</td>
              <td>
                <a href="https://dev.azure.com/ngam/feedstock-builds/_build/latest?definitionId=&branchName=master">
                  <img src="https://dev.azure.com/ngam/feedstock-builds/_apis/build/status/tensorflow-metal-feedstock?branchName=master&jobName=osx&configuration=osx_64_python3.9.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_arm64_python3.10.____cpython</td>
              <td>
                <a href="https://dev.azure.com/ngam/feedstock-builds/_build/latest?definitionId=&branchName=master">
                  <img src="https://dev.azure.com/ngam/feedstock-builds/_apis/build/status/tensorflow-metal-feedstock?branchName=master&jobName=osx&configuration=osx_arm64_python3.10.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_arm64_python3.8.____cpython</td>
              <td>
                <a href="https://dev.azure.com/ngam/feedstock-builds/_build/latest?definitionId=&branchName=master">
                  <img src="https://dev.azure.com/ngam/feedstock-builds/_apis/build/status/tensorflow-metal-feedstock?branchName=master&jobName=osx&configuration=osx_arm64_python3.8.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_arm64_python3.9.____cpython</td>
              <td>
                <a href="https://dev.azure.com/ngam/feedstock-builds/_build/latest?definitionId=&branchName=master">
                  <img src="https://dev.azure.com/ngam/feedstock-builds/_apis/build/status/tensorflow-metal-feedstock?branchName=master&jobName=osx&configuration=osx_arm64_python3.9.____cpython" alt="variant">
                </a>
              </td>
            </tr>
          </tbody>
        </table>
      </details>
    </td>
  </tr>
</table>

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-tensorflow--metal-green.svg)](https://anaconda.org/ngam/tensorflow-metal) | [![Conda Downloads](https://img.shields.io/conda/dn/ngam/tensorflow-metal.svg)](https://anaconda.org/ngam/tensorflow-metal) | [![Conda Version](https://img.shields.io/conda/vn/ngam/tensorflow-metal.svg)](https://anaconda.org/ngam/tensorflow-metal) | [![Conda Platforms](https://img.shields.io/conda/pn/ngam/tensorflow-metal.svg)](https://anaconda.org/ngam/tensorflow-metal) |

Installing tensorflow-metal
===========================

Installing `tensorflow-metal` from the `ngam` channel can be achieved by adding `ngam` to your channels with:

```
conda config --add channels ngam
conda config --set channel_priority strict
```

Once the `ngam` channel has been enabled, `tensorflow-metal` can be installed with `conda`:

```
conda install tensorflow-metal
```

or with `mamba`:

```
mamba install tensorflow-metal
```

It is possible to list all of the versions of `tensorflow-metal` available on your platform with `conda`:

```
conda search tensorflow-metal --channel ngam
```

or with `mamba`:

```
mamba search tensorflow-metal --channel ngam
```

Alternatively, `mamba repoquery` may provide more information:

```
# Search all versions available on your platform:
mamba repoquery search tensorflow-metal --channel ngam

# List packages depending on `tensorflow-metal`:
mamba repoquery whoneeds tensorflow-metal --channel ngam

# List dependencies of `tensorflow-metal`:
mamba repoquery depends tensorflow-metal --channel ngam
```




Updating tensorflow-metal-feedstock
===================================

If you would like to improve the tensorflow-metal recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`ngam` channel, whereupon the built conda packages will be available for
everybody to install and use from the `ngam` channel.
Note that all branches in the ngam/tensorflow-metal-feedstock are
immediately built and any created packages are uploaded, so PRs should be based
on branches in forks and branches in the main repository should only be used to
build distinct package versions.

In order to produce a uniquely identifiable distribution:
 * If the version of a package **is not** being increased, please add or increase
   the [``build/number``](https://docs.conda.io/projects/conda-build/en/latest/resources/define-metadata.html#build-number-and-string).
 * If the version of a package **is** being increased, please remember to return
   the [``build/number``](https://docs.conda.io/projects/conda-build/en/latest/resources/define-metadata.html#build-number-and-string)
   back to 0.

Feedstock Maintainers
=====================

* [@ngam](https://github.com/ngam/)


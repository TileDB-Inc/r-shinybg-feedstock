About r-shinybg-feedstock
=========================

Feedstock license: [BSD-3-Clause](https://github.com/conda-forge/r-shinybg-feedstock/blob/main/LICENSE.txt)


About r-shinybg
---------------

Home: https://github.com/TileDB-Inc/shinybg

Package license: MIT

Summary: Render Shiny apps inside a Jupyter notebook

About r-shinybg
---------------

Home: https://github.com/TileDB-Inc/shinybg

Package license: MIT

Summary: Render Shiny apps inside a Jupyter notebook

Current build status
====================


<table>
    
  <tr>
    <td>Azure</td>
    <td>
      <details>
        <summary>
          <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=None&branchName=main">
            <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/r-shinybg-feedstock?branchName=main">
          </a>
        </summary>
        <table>
          <thead><tr><th>Variant</th><th>Status</th></tr></thead>
          <tbody><tr>
              <td>linux_64_r_base4.2</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=None&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/r-shinybg-feedstock?branchName=main&jobName=linux&configuration=linux%20linux_64_r_base4.2" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_64_r_base4.3</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=None&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/r-shinybg-feedstock?branchName=main&jobName=linux&configuration=linux%20linux_64_r_base4.3" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_64_r_base4.2</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=None&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/r-shinybg-feedstock?branchName=main&jobName=osx&configuration=osx%20osx_64_r_base4.2" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_64_r_base4.3</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=None&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/r-shinybg-feedstock?branchName=main&jobName=osx&configuration=osx%20osx_64_r_base4.3" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>win_64</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=None&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/r-shinybg-feedstock?branchName=main&jobName=win&configuration=win%20win_64_" alt="variant">
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
| [![Conda Recipe](https://img.shields.io/badge/recipe-r--shinybg-green.svg)](https://anaconda.org/tiledb/r-shinybg) | [![Conda Downloads](https://img.shields.io/conda/dn/tiledb/r-shinybg.svg)](https://anaconda.org/tiledb/r-shinybg) | [![Conda Version](https://img.shields.io/conda/vn/tiledb/r-shinybg.svg)](https://anaconda.org/tiledb/r-shinybg) | [![Conda Platforms](https://img.shields.io/conda/pn/tiledb/r-shinybg.svg)](https://anaconda.org/tiledb/r-shinybg) |

Installing r-shinybg
====================

Installing `r-shinybg` from the `tiledb` channel can be achieved by adding `tiledb` to your channels with:

```
conda config --add channels tiledb
conda config --set channel_priority strict
```

Once the `tiledb` channel has been enabled, `r-shinybg` can be installed with `conda`:

```
conda install r-shinybg
```

or with `mamba`:

```
mamba install r-shinybg
```

It is possible to list all of the versions of `r-shinybg` available on your platform with `conda`:

```
conda search r-shinybg --channel tiledb
```

or with `mamba`:

```
mamba search r-shinybg --channel tiledb
```

Alternatively, `mamba repoquery` may provide more information:

```
# Search all versions available on your platform:
mamba repoquery search r-shinybg --channel tiledb

# List packages depending on `r-shinybg`:
mamba repoquery whoneeds r-shinybg --channel tiledb

# List dependencies of `r-shinybg`:
mamba repoquery depends r-shinybg --channel tiledb
```




Updating r-shinybg-feedstock
============================

If you would like to improve the r-shinybg recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`tiledb` channel, whereupon the built conda packages will be available for
everybody to install and use from the `tiledb` channel.
Note that all branches in the conda-forge/r-shinybg-feedstock are
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

* [@SarantopoulosKon](https://github.com/SarantopoulosKon/)
* [@Shelnutt2](https://github.com/Shelnutt2/)
* [@aaronwolen](https://github.com/aaronwolen/)
* [@ihnorton](https://github.com/ihnorton/)


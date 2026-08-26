About dinrail-feedstock
=======================

Feedstock license: [BSD-3-Clause](https://github.com/conda-forge/dinrail-feedstock/blob/main/LICENSE.txt)


About dinrail
-------------

Home: https://github.com/gbionics/dinrail

Package license: BSD-3-Clause

Summary: Metapackage for the complete core dinrail stack

Development: https://github.com/gbionics/dinrail

`dinrail` is a convenience metapackage that depends on `libdinrail`,
`dinrail-devices`, and `dinrail-tools`.

About dinrail-devices
---------------------

Home: https://github.com/gbionics/dinrail

Package license: BSD-3-Clause

Summary: Built-in device plugins for dinrail

Development: https://github.com/gbionics/dinrail

`dinrail-devices` ships the built-in runtime-loaded device plugins for
dinrail, including the fake control-board device used for development
and testing.

About dinrail-tools
-------------------

Home: https://github.com/gbionics/dinrail

Package license: BSD-3-Clause

Summary: Command-line tools for dinrail

Development: https://github.com/gbionics/dinrail

`dinrail-tools` ships the `dinrail` command-line application for working
with the core dinrail framework and its device abstractions.

About dinrail-yarp
------------------

Home: https://github.com/gbionics/dinrail

Package license: BSD-3-Clause

Summary: Metapackage for the complete dinrail YARP integration

Development: https://github.com/gbionics/dinrail

`dinrail-yarp` is a convenience metapackage that depends on
`libdinrail-yarp`, `dinrail-yarp-devices`, and `dinrail-yarp-tools`.

About dinrail-yarp-devices
--------------------------

Home: https://github.com/gbionics/dinrail

Package license: BSD-3-Clause

Summary: YARP device plugins for dinrail

Development: https://github.com/gbionics/dinrail

`dinrail-yarp-devices` ships the runtime-loaded YARP device plugins that
connect dinrail control-board abstractions with YARP networks and devices.

About dinrail-yarp-tools
------------------------

Home: https://github.com/gbionics/dinrail

Package license: BSD-3-Clause

Summary: YARP-based executable tools for dinrail

Development: https://github.com/gbionics/dinrail

`dinrail-yarp-tools` ships the YARP-based `dinrail-runner` executables for
launching and operating dinrail devices in a YARP environment.

About libdinrail
----------------

Home: https://github.com/gbionics/dinrail

Package license: BSD-3-Clause

Summary: Core C++ shared library and headers for dinrail

Development: https://github.com/gbionics/dinrail

`libdinrail` ships the core C++ shared library, public headers, and CMake
package files for dinrail. This output is intended for native consumers
that implement, load, or use dinrail device abstractions.

About libdinrail-yarp
---------------------

Home: https://github.com/gbionics/dinrail

Package license: BSD-3-Clause

Summary: C++ conversion library for dinrail and YARP interoperability

Development: https://github.com/gbionics/dinrail

`libdinrail-yarp` ships the C++ conversion library, public headers, and
CMake package files used to exchange properties between dinrail and YARP.

Current build status
====================


<table><tr>
    <td>GitHub Actions</td>
    <td>
      <a href="https://github.com/conda-forge/dinrail-feedstock/actions/workflows/conda-build.yml">
        <img src="https://github.com/conda-forge/dinrail-feedstock/actions/workflows/conda-build.yml/badge.svg?event=push&branch=main">
      </a>
    </td>
  </tr>
    
  <tr>
    <td>Azure</td>
    <td>
      <details>
        <summary>
          <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=29266&branchName=main">
            <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/dinrail-feedstock?branchName=main">
          </a>
        </summary>
        <table>
          <thead><tr><th>Variant</th><th>Status</th></tr></thead>
          <tbody><tr>
              <td>osx_64</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=29266&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/dinrail-feedstock?branchName=main&jobName=osx&configuration=osx%20osx_64_" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_arm64</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=29266&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/dinrail-feedstock?branchName=main&jobName=osx&configuration=osx%20osx_arm64_" alt="variant">
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
| [![Conda Recipe](https://img.shields.io/badge/recipe-dinrail-green.svg)](https://anaconda.org/conda-forge/dinrail) | [![Conda Downloads](https://img.shields.io/conda/dn/conda-forge/dinrail.svg)](https://anaconda.org/conda-forge/dinrail) | [![Conda Version](https://img.shields.io/conda/vn/conda-forge/dinrail.svg)](https://anaconda.org/conda-forge/dinrail) | [![Conda Platforms](https://img.shields.io/conda/pn/conda-forge/dinrail.svg)](https://anaconda.org/conda-forge/dinrail) |
| [![Conda Recipe](https://img.shields.io/badge/recipe-dinrail--devices-green.svg)](https://anaconda.org/conda-forge/dinrail-devices) | [![Conda Downloads](https://img.shields.io/conda/dn/conda-forge/dinrail-devices.svg)](https://anaconda.org/conda-forge/dinrail-devices) | [![Conda Version](https://img.shields.io/conda/vn/conda-forge/dinrail-devices.svg)](https://anaconda.org/conda-forge/dinrail-devices) | [![Conda Platforms](https://img.shields.io/conda/pn/conda-forge/dinrail-devices.svg)](https://anaconda.org/conda-forge/dinrail-devices) |
| [![Conda Recipe](https://img.shields.io/badge/recipe-dinrail--tools-green.svg)](https://anaconda.org/conda-forge/dinrail-tools) | [![Conda Downloads](https://img.shields.io/conda/dn/conda-forge/dinrail-tools.svg)](https://anaconda.org/conda-forge/dinrail-tools) | [![Conda Version](https://img.shields.io/conda/vn/conda-forge/dinrail-tools.svg)](https://anaconda.org/conda-forge/dinrail-tools) | [![Conda Platforms](https://img.shields.io/conda/pn/conda-forge/dinrail-tools.svg)](https://anaconda.org/conda-forge/dinrail-tools) |
| [![Conda Recipe](https://img.shields.io/badge/recipe-dinrail--yarp-green.svg)](https://anaconda.org/conda-forge/dinrail-yarp) | [![Conda Downloads](https://img.shields.io/conda/dn/conda-forge/dinrail-yarp.svg)](https://anaconda.org/conda-forge/dinrail-yarp) | [![Conda Version](https://img.shields.io/conda/vn/conda-forge/dinrail-yarp.svg)](https://anaconda.org/conda-forge/dinrail-yarp) | [![Conda Platforms](https://img.shields.io/conda/pn/conda-forge/dinrail-yarp.svg)](https://anaconda.org/conda-forge/dinrail-yarp) |
| [![Conda Recipe](https://img.shields.io/badge/recipe-dinrail--yarp--devices-green.svg)](https://anaconda.org/conda-forge/dinrail-yarp-devices) | [![Conda Downloads](https://img.shields.io/conda/dn/conda-forge/dinrail-yarp-devices.svg)](https://anaconda.org/conda-forge/dinrail-yarp-devices) | [![Conda Version](https://img.shields.io/conda/vn/conda-forge/dinrail-yarp-devices.svg)](https://anaconda.org/conda-forge/dinrail-yarp-devices) | [![Conda Platforms](https://img.shields.io/conda/pn/conda-forge/dinrail-yarp-devices.svg)](https://anaconda.org/conda-forge/dinrail-yarp-devices) |
| [![Conda Recipe](https://img.shields.io/badge/recipe-dinrail--yarp--tools-green.svg)](https://anaconda.org/conda-forge/dinrail-yarp-tools) | [![Conda Downloads](https://img.shields.io/conda/dn/conda-forge/dinrail-yarp-tools.svg)](https://anaconda.org/conda-forge/dinrail-yarp-tools) | [![Conda Version](https://img.shields.io/conda/vn/conda-forge/dinrail-yarp-tools.svg)](https://anaconda.org/conda-forge/dinrail-yarp-tools) | [![Conda Platforms](https://img.shields.io/conda/pn/conda-forge/dinrail-yarp-tools.svg)](https://anaconda.org/conda-forge/dinrail-yarp-tools) |
| [![Conda Recipe](https://img.shields.io/badge/recipe-libdinrail-green.svg)](https://anaconda.org/conda-forge/libdinrail) | [![Conda Downloads](https://img.shields.io/conda/dn/conda-forge/libdinrail.svg)](https://anaconda.org/conda-forge/libdinrail) | [![Conda Version](https://img.shields.io/conda/vn/conda-forge/libdinrail.svg)](https://anaconda.org/conda-forge/libdinrail) | [![Conda Platforms](https://img.shields.io/conda/pn/conda-forge/libdinrail.svg)](https://anaconda.org/conda-forge/libdinrail) |
| [![Conda Recipe](https://img.shields.io/badge/recipe-libdinrail--yarp-green.svg)](https://anaconda.org/conda-forge/libdinrail-yarp) | [![Conda Downloads](https://img.shields.io/conda/dn/conda-forge/libdinrail-yarp.svg)](https://anaconda.org/conda-forge/libdinrail-yarp) | [![Conda Version](https://img.shields.io/conda/vn/conda-forge/libdinrail-yarp.svg)](https://anaconda.org/conda-forge/libdinrail-yarp) | [![Conda Platforms](https://img.shields.io/conda/pn/conda-forge/libdinrail-yarp.svg)](https://anaconda.org/conda-forge/libdinrail-yarp) |

Installing dinrail
==================

Installing `dinrail` from the `conda-forge` channel can be achieved by adding `conda-forge` to your channels with:

```
conda config --add channels conda-forge
conda config --set channel_priority strict
```

How to use
----------

<details>
<summary>With conda</summary>

```
conda install dinrail dinrail-devices dinrail-tools dinrail-yarp dinrail-yarp-devices dinrail-yarp-tools libdinrail libdinrail-yarp
```

</details>

<details>
<summary>With mamba</summary>

```
mamba install dinrail dinrail-devices dinrail-tools dinrail-yarp dinrail-yarp-devices dinrail-yarp-tools libdinrail libdinrail-yarp
```

</details>

<details>
<summary>With pixi</summary>

```
# for adding to your local project
pixi add dinrail dinrail-devices dinrail-tools dinrail-yarp dinrail-yarp-devices dinrail-yarp-tools libdinrail libdinrail-yarp
# for installing globally
pixi global install dinrail dinrail-devices dinrail-tools dinrail-yarp dinrail-yarp-devices dinrail-yarp-tools libdinrail libdinrail-yarp
```

</details>

Search package versions
-----------------------

It is possible to list all of the versions of `dinrail` available on your platform:

<details>
<summary>With conda</summary>

```
conda search dinrail --channel conda-forge
```

</details>

<details>
<summary>With mamba</summary>

```
mamba search dinrail --channel conda-forge
```

</details>

<details>
<summary>With pixi</summary>

```
pixi search dinrail --channel conda-forge
```

</details>

<details>
<summary>With mamba repoquery, which may provide more information</summary>

```
# Search all versions available on your platform:
mamba repoquery search dinrail --channel conda-forge

# List packages depending on `dinrail`:
mamba repoquery whoneeds dinrail --channel conda-forge

# List dependencies of `dinrail`:
mamba repoquery depends dinrail --channel conda-forge
```

</details>


About conda-forge
=================

[![Powered by
NumFOCUS](https://img.shields.io/badge/powered%20by-NumFOCUS-orange.svg?style=flat&colorA=E1523D&colorB=007D8A)](https://numfocus.org)

conda-forge is a community-led conda channel of installable packages.
In order to provide high-quality builds, the process has been automated into the
conda-forge GitHub organization. The conda-forge organization contains one repository
for each of the installable packages. Such a repository is known as a *feedstock*.

A feedstock is made up of a conda recipe (the instructions on what and how to build
the package) and the necessary configurations for automatic building using freely
available continuous integration services. Thanks to the awesome service provided by
[Azure](https://azure.microsoft.com/en-us/services/devops/), [GitHub](https://github.com/),
[CircleCI](https://circleci.com/), [AppVeyor](https://www.appveyor.com/),
[Drone](https://cloud.drone.io/welcome), and [TravisCI](https://travis-ci.com/)
it is possible to build and upload installable packages to the
[conda-forge](https://anaconda.org/conda-forge) [anaconda.org](https://anaconda.org/)
channel for Linux, Windows and OSX respectively.

To manage the continuous integration and simplify feedstock maintenance,
[conda-smithy](https://github.com/conda-forge/conda-smithy) has been developed.
Using the ``conda-forge.yml`` within this repository, it is possible to re-render all of
this feedstock's supporting files (e.g. the CI configuration files) with ``conda smithy rerender``.

For more information, please check the [conda-forge documentation](https://conda-forge.org/docs/).

Terminology
===========

**feedstock** - the conda recipe (raw material), supporting scripts and CI configuration.

**conda-smithy** - the tool which helps orchestrate the feedstock.
                   Its primary use is in the construction of the CI ``.yml`` files
                   and simplify the management of *many* feedstocks.

**conda-forge** - the place where the feedstock and smithy live and work to
                  produce the finished article (built conda distributions)


Updating dinrail-feedstock
==========================

If you would like to improve the dinrail recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`conda-forge` channel, whereupon the built conda packages will be available for
everybody to install and use from the `conda-forge` channel.
Note that all branches in the conda-forge/dinrail-feedstock are
immediately built and any created packages are uploaded, so PRs should be based
on branches in forks, and branches in the main repository should only be used to
build distinct package versions.

In order to produce a uniquely identifiable distribution:
 * If the version of a package **is not** being increased, please add or increase
   the [``build/number``](https://docs.conda.io/projects/conda-build/en/latest/resources/define-metadata.html#build-number-and-string).
 * If the version of a package **is** being increased, please remember to return
   the [``build/number``](https://docs.conda.io/projects/conda-build/en/latest/resources/define-metadata.html#build-number-and-string)
   back to 0.

Feedstock Maintainers
=====================

* [@traversaro](https://github.com/traversaro/)


<!-- dummy commit to enable rerendering -->


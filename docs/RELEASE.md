# motorMicronix Releases

## __R1-2 (2026-01-22)__
R1-2 is a release based on the master branch.

### Changes since R1-1

#### New features
* Pull request [#8](https://github.com/epics-motor/motorMicronix/pull/8): [Reinier van Mourik](https://github.com/TAU-Reinier) added version parsing for MMC-110
* Pull request [#10](https://github.com/epics-motor/motorMicronix/pull/10): [Henrik Loos](https://github.com/HenrikLoos) added handling of MMC-ETHERNET module

#### Modifications to existing features
* None

#### Bug fixes
* Pull request [#7](https://github.com/epics-motor/motorMicronix/pull/7): [Reinier van Mourik](https://github.com/TAU-Reinier) corrected the resolution calculation for MMC-1xx series
* Pull request [#9](https://github.com/epics-motor/motorMicronix/pull/9): Use ENC as the resolution when an axis is in closed-loop mode

#### Continuous integration
* Upgraded ci-scripts (v3.4.1)

## __R1-1 (2023-04-12)__
R1-1 is a release based on the master branch.

### Changes since R1-0-1

#### New features
* None

#### Modifications to existing features
* Commit [b106160](https://github.com/epics-motor/motorMicronix/commit/b1061603c03e8fd8df4914d5427127bf1add5e1e): Handle the MMC-103 version string

#### Bug fixes
* None

#### Continuous integration
* Added ci-scripts (v3.0.1)
* Configured to use Github Actions for CI

## __R1-0-1 (2020-05-11)__
R1-0-1 is a release based on the master branch.  

### Changes since R1-0

#### New features
* None

#### Modifications to existing features
* None

#### Bug fixes
* Commit [1afcc7e](https://github.com/epics-motor/motorMicronix/commit/1afcc7e36aed0bb87044eff988d343b736a36d6c): Include ``$(MOTOR)/modules/RELEASE.$(EPICS_HOST_ARCH).local`` instead of ``$(MOTOR)/configure/RELEASE``

## __R1-0 (2019-04-18)__
R1-0 is a release based on the master branch.  

### Changes since motor-6-11

motorMicronix is now a standalone module, as well as a submodule of [motor](https://github.com/epics-modules/motor)

#### New features
* motorMicronix can be built outside of the motor directory
* motorMicronix has a dedicated example IOC that can be built outside of motorMicronix

#### Modifications to existing features
* None

#### Bug fixes
* None

# motorMicronix Releases

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

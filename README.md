# poc-vcv-rack-validator

This repository is a Proof of Concept for VCV Rack plug-in validation on CI,
here on GitHub Actions.

This system will check that a plug-in can properly load by installing Rack,
and requesting it to take screenshots of the library.

If the output screenshot files are present, then it is most probably safe to
assume that the plug-in did properly load.

This doesn't do any pixel compare.

This Proof of Concept is made for [Eurorack-blocks](https://github.com/ohmtech-rdi/eurorack-blocks )
as we want an automated way to check for build regressions for the simulator.

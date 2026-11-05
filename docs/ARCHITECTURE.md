# Hexadecimal Day Clock

Provider-specific clock semantics remain local. The C ABI and reusable arithmetic are consumed through Common 1.19.81 at a99ef676b0e43c7e645c81756e3fd38be0a54406, linked from its authoritative submodule rather than copied. Offline native install includes the pinned sources; original accuracy tests remain mandatory.

## Implementation language

The clock provider and its arithmetic remain ISO C11: they require no C++ runtime, exception machinery or dynamic resource ownership. C exports preserve the exact Common temporal ABI. Builds link against the pinned Common gitlink (a99ef676b0e43c7e645c81756e3fd38be0a54406) and must pass the native output, accuracy, package and upgrade checks before publication.

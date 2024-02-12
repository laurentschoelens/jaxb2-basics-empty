# jaxb2-basics-empty

This project aims to fix [jaxb-tools issue #465](https://github.com/highsource/jaxb-tools/issues/465)
by providing an empty jar with `org.jvnet.jaxb2_commons:jaxb2-basics-runtime` coordinates.

The new `jaxb2-basics-runtime` (with `org.jvnet.jaxb` groupId) will then depend on this specific version range `[3,9999]`
so it will be taken by transitivity by maven or gradle rather than the old-non-empty one with 0.x or 1.x version.

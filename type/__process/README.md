This type does runtime-only starting and stopping of processes.
It is certainly debatable if this should be part of configuration management in
the form of a distinct type.

Most (if not all) use-cases of this type could be implemented more easily using
a gencode-remote script or using the `__check_messages` type.

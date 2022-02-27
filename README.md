Bug Demo
--------

Though we have code that loads the `bs58check` library, Vite silently excludes
some of its dependencies at bundle time, and we're left to run into the issue
at runtime.
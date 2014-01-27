MyAndroidDevIVYRepo
---

Just a simple publish to local ivy repo for android app dev using gradle.
Just simple done in ant.

# Implementation Notes

Implemented in Apache ANT using the IVY set of ant tasks using the setting
of the publisher resolver to local to load the ivy repo into the local cache as than
we can point gradle to that sub directory.

# Best Pratices

Same layout as the repo using maven conventions. Items not found in Maven are
store under my own namespace to avoid conflicts when they become found in maven.

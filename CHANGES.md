# Proposed Changes to GRaF

## Bug Fixes
- Fixed an issue in the `cov.SE` function where the class check for "dist" was causing errors with newer R versions that support multiple class inheritance. 
  Changed `class(sumdiffs) == "dist"` to `inherits(sumdiffs, "dist")`.

## Improvements
- Updated the package to be compatible with newer R versions that support multiple class inheritance.


# Changelog

All notable changes to `AntiScanScanClub` will be documented in this file.

## Version 2.0.1

### Added
-   getPublicFiles() method for get all files in public path recursively
-   getAllRoutes() method for get uri of all registered routes
-   whitelistPublicFiles() method for whitelisting all public files recursively
-   whitelistAllRoutes() method for whitelisting uri of all registered routes

## Version 2.0.0

### Added
-   whitelistFile() method, for whitelisting files/path from filterFile()
-   restoreFilterFiles() method to restoring filter_files.txt to default

## Version 1.0.3

### Fixed
-   Fix filterInput() bug failed to handle array input fields (reported by [@mirfansulaiman](https://github.com/mirfansulaiman))

## Version 1.0.2-dev1

### Fixed

-   Fix filterFile() bug cause matching through strpos isn't efficient

## Version 1.0.2

### Added

-   filterFile() method, to prevent client if they're try to access credentials and/ important files/path.

## Version 1.0.1

### Fixed

-   filterInput() method

## Version 1.0

### Added

-   Everything

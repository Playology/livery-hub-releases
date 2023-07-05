# Livery Hub
Livery Hub is web site and a desktop application working together to allow sim racers to share and sync custom liveries on an event by event basis.

# Release History


## v1.4.2 - 2023-07-05

### Fixed
- Issue with spaces at start of livery folder name


## v1.4.1 - 2023-07-04

### Fixed
- Minor irritation introduced in last update



## v1.4.0 - 2023-07-04

### Added
- Ability to delete livery from cloud (does not affect local liveries)

### Fixed
- Speculative attempt to fix intermittent error where SSL decription fails by retrying three times before failing.



## v1.3.0 - 2023-07-03

### Added
- Paging to Livery Gallery.

### Changed
- Hide link button on livery gallery tile when no url specified.

### Fixed
- Issue introduced in v1.2.2 where upload livery was looking for files with double .json extension.


## v1.2.3 - 2023-07-02

### Changed
- Increased logging during sync of liveries
- Prevented single failure of livery download and install from stopping process
- Notify user if not all liveries could be synced.


## v1.2.2 - 2023-06-30

### Added
- Car model name to My Liveries table

### Changed
- Log custom car file path as loaded
- Improved error reporting on error loading custom car file
- Continue loading custom cars after error

## v1.2.1 - 2023-06-24


### Added
- Refresh button to My Liveries

### Changed
- Ability to link multiple liveries to community

## v1.2.0 - 2023-06-24

### Added
- Link livery to a community
- Sync liveries linked to a community
- Livery gallery with ability to install individual liveries

### Changed
- Change Activate to Start on upcoming event button
- Hid actual urls on navigation links



## v1.1.3 - 2023-06-23

### Fixed
- Issue were desktop was not taking local date into consideration when finding upcoming events.


## v1.1.2 - 2023-06-23

### Fixed
- Issue where download of liveries failed if user has not uploaded a livery


## v1.1.1 - 2023-06-03

### Changed
- Restricted upcoming events to next two weeks


## v1.1.0 - 2023-06-03

### Added
- Ability to remove linked livery from event

### Changed
- Disable assign button in assign livery dialog when no livery selected


## v1.0.1 - 2023-06-02

### Changed
- Layout of dashboard items

### Fixed
- Ordering of upcoming events


## v1.0.0 - 2023-06-01

### Changed
- Centered token capture dialog

### Fixed
- Error on load when no custom cars or liveries have been created


## v1.0.0-beta.5 - 2023-05-13

### Changed
- About now shows semantic version rather than assembly version


## v1.0.0-beta.4 - 2023-05-13

### Added
- Cloud icon to rows in My Liveries to indicate whether the livery has been uploaded to My Livery Cloud

### Changed
- Livery upload now recognises whether the livery has already been uploaded and overwrites with any changes
- Deleting a local livery automatically removes all references to it from the cloud
- Structure of package so that it could potentially be downloaded and installed manually

## v1.0.0-beta.3 - 2023-05-12

### Fixed
- Error from converters when re-loading upcoming events

## v1.0.0-beta.2 - 2023-05-12

### Fixed
- Reduced height of Log Viewer to better fit on screen

## v1.0.0-beta.1 - 2023-05-12

### Added
- Download and install linked liveries on activation of an event
- Cleanup linked liveries when activated event is stopped

## v1.0.0-alpha.7 - 2023-05-11

### Added
- Assign livery to upcoming event
- Display assigned livery name on upcoming event tile

## v1.0.0-alpha.6 - 2023-05-10

### Added
- Upload of livery from My Liveries
- Display of uploaded liveries in Livery Cloud

## v1.0.0-alpha.5 - 2023-05-09

### Added
- Display of upcoming events for user

## v1.0.0-alpha.4 - 2023-05-09

### Added
- Display of user communities on dashboard

## v1.0.0-alpha.3 - 2023-05-06

### Added
- Initial livery manager implementation

## v1.0.0-alpha.2 - 2023-05-05

### Added
- Button to copy token from clipboard

### Changed
- Maximise window on startup

## v1.0.0-alpha.1 - 2023-05-05

Initial alpha release


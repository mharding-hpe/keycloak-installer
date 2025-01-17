# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [3.7.0]
### Changed
- Updated base chart to version 16.1.0.
- Updated keycloak image to 16.1.1.
- Changed logic for getting the client secret for each client from keycloak.
- Addressed all issues related to upgrading base chart as well as keycloak image.

## [3.0.0]
### Removed
- keycloak_setup: Now removes the `gatekeeper` Client and associated Secret.

## [1.0.0]
### Added
- keycloak_setup: Now creates an `oauth2-proxy` Client and associated Secret
  with the client secret for use by OAuth2-Proxy.
- keycloak_setup: Now creates an `system-nexus-client` Client and associated
  Secret with the client secret for use by the Nexus-Keycloak plugin.

## [0.12.6]
- keycloak_setup: Initial release for CSM 1.0

## [0.10.1]
- keycloak_setup: Added `wlm-client` in shasta realm

## [0.10.0]
- keycloak_setup: Added `system-pxe-client` in shasta realm (CC only flow, `system-pxe` role)

## [0.9.2]
- keycloak_setup: Added `system-compute-client` in shasta realm (CC only flow, `system-compute` role)

## [0.1.0]
### Added
- Initial release

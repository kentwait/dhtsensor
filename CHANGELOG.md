# Changelog
All notable changes to this project will be documented in this file.

This project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [0.2.1] - 2019-01-27
### Added
- Changelog that documents notable changes to the project, especially the API.

## [0.2.0] - 2019-01-27
### Changed
- Removed the need to pass an instance of the pigpio.pi class when creating a new sensor object. Now, everytime a new instance of Sensor is created, each instance creates a pigpio.pi class for itself.

## 0.1.0 - 2019-01-27
### Added
- Reading class which encapsulates temperature and humidity data.
- Sensor class to represent a DHT11 or DHT22 sensor connected to a given GPIO pin. 
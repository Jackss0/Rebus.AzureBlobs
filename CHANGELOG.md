# Changelog

## 0.1.0
* Initial version

## 0.2.0
* Update microsoft.azure.storage.blob dependency to 11 - thanks [oseku]

## 0.3.0
* Update to Rebus 6
* Implement data bus attachment storage management API

## 0.4.0
* Add options for skipping container creation and updating last read time when using blobs as data bus storage
* Additional configuration overload that makes it possible to pass a fully qualified container URI (incl. SAS token) when configuring data bus storage

## 0.5.0
* Update to Rebus 6 stable
* Hopefully fix race condition when updating last read time of data bus attachments

[oseku]: https://github.com/oseku
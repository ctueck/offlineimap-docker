offlineimap-docker
==================

Simple Docker container and Docker Compose config to run [OfflineIMAP](https://www.offlineimap.org/)

The main use case for creating this was to back up emails from an IMAP account into a Docker volume. You'll need to:

- create an `offlineimap.conf` file to mount into the container, see minimalist `offlineimap-sample.conf` or the [full sample from the OfflineIMAP repository](https://github.com/OfflineIMAP/offlineimap/blob/master/offlineimap.conf);
- create a file to store your IMAP password/credentials under `passwords/`;
- run the container, e.g. from a cron job.


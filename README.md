# CQC Data Repository

Raw JSON data files and tarballs for the CQC API package.

## Structure

- initial_bulk/ - Initial full download of all location/provider data
- incremental/ - Daily incremental updates
- cqc_initial_bulk_YYYY-MM-DD.tar.gz - Compressed initial bulk data
- cqc_incremental_YYYY-MM-DD.tar.gz - Compressed incremental updates

## Usage

This repo is automatically updated by GitHub Actions workflows in the main cqcpack package repository.

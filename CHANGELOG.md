# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/).

## [1.0.0] - 2026-07-10

### Added
- Initial release of the Fintech Fraud Analytics Data Warehouse project.
- Designed a production-inspired 7-table relational schema:
  - transactions
  - customers
  - merchants
  - devices
  - locations
  - chargebacks
  - fraud_alerts

### Database & SQL Features
- Added complete SQL script for database creation and analytics.
- Implemented advanced SQL techniques:
  - Window Functions (ROW_NUMBER, DENSE_RANK, LAG, SUM OVER)
  - Common Table Expressions (CTEs)
  - Aggregation queries
  - CASE-based risk classification
  - Date-based financial analysis

### Analytics Capabilities
- Added cumulative chargeback loss tracking.
- Added customer spending spike detection.
- Added high-value transaction identification.
- Added merchant fraud risk tier classification.
- Added suspicious transaction monitoring logic.

### Dataset
- Added simulated fintech transaction datasets.
- Included 50,000+ transaction records for analytics testing.

### Documentation
- Added project README with:
  - Business objectives
  - Database schema overview
  - SQL skills demonstrated
  - Execution instructions

## [Future Releases]

### Planned Enhancements
- Add Power BI/Tableau dashboard integration.
- Add Python-based fraud prediction model.
- Add automated ETL pipeline.
- Add real-time fraud monitoring simulation.
- Improve anomaly detection algorithms.

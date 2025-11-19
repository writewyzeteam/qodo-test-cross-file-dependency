# E-Commerce Application

This application includes shared utility functions for formatting prices, dates, and validating data.

## Architecture

- `src/utils/formatters.js` - Shared formatting utilities used across the application
- `src/components/` - UI components that depend on formatters
- `src/services/` - Business logic services that use formatters
- `tests/` - Test suite for utilities

## Dependencies

The formatPrice function is used in:
- ProductCard component
- CheckoutSummary component
- InvoiceGenerator service
- ReportGenerator service

Any changes to formatters.js should be tested across all dependent modules.

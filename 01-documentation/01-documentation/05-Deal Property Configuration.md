# Deal Property Configuration

## Overview

Custom deal properties were implemented to tailor HubSpot CRM to Gochelicious's catering operations.

## Configured Properties

| Property | Field Type | Purpose |
|-----------|------------|---------|
| Event Date | Date Picker | Stores the scheduled event date. |
| Event Type | Dropdown | Identifies the type of catering engagement. |
| Number of Guests | Number | Supports menu planning and logistics. |
| Venue Location | Single-line text | Records the event venue. |
| Budget Range | Dropdown | Helps qualify opportunities and recommend service packages. |
| Dietary Requirements | Multi-line text | Captures client dietary preferences and restrictions. |
| Service Package | Dropdown | Identifies the selected catering package. |

## Business Benefits

- Standardized booking information
- Improved operational planning
- Better reporting and filtering
- Consistent data capture
- Enhanced customer experience

## Lessons Learned

A CRM implementation should store business-specific information on the object that owns the data. Since catering bookings are represented by Deals, event-related information was implemented as Deal properties rather than Contact properties.

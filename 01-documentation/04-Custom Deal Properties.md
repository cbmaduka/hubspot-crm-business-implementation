# Custom Deal Properties

## Purpose

Custom deal properties were created to capture business-specific information required by Gochelicious Premium Catering.

## Property

### Event Date

**Object:** Deal

**Field Type:** Date Picker

**Description:**

Stores the scheduled date of the client's catering event.

## Business Value

Capturing the event date enables the business to:

- Schedule catering operations
- Allocate staff and equipment
- Prevent booking conflicts
- Improve operational planning
- Support event reporting

## Lessons Learned

Business-specific properties should be attached to the object that owns the data. Since an event belongs to a booking rather than a person, the Event Date property was created as a Deal property instead of a Contact property.

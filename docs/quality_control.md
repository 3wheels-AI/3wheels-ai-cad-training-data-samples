# CAD Data Quality Control

## QC Pipeline

```text
Source Data
   ↓
Format Validation
   ↓
Metadata Validation
   ↓
Duplicate Detection
   ↓
Annotation Validation
   ↓
Human Review
   ↓
Final Quality Check
   ↓
Release
```

## Validation Areas

### File Validation
- File opens successfully
- Expected extension matches content
- No corrupted files

### Metadata Validation
- Unique sample ID
- Required fields present
- Valid category and domain
- Consistent units

### Annotation Validation
- Correct labels
- No unsupported assumptions
- Dimensions and symbols verified
- Ambiguous samples flagged

## Quality Status

Recommended values:

- `pending`
- `in_review`
- `verified`
- `rejected`

# Dataset Ingestion Notes: [Dataset name]

**Status:** Planned  
**Date:** [YYYY-MM-DD]

## 1. Dataset provenance
- Original source:
- Download page:
- Dataset name/version:
- License / terms:
- Scenario described by source:

## 2. File details
- Filename:
- Format:
- Approximate size:
- Compression:
- Expected event structure:

## 3. Splunk configuration
- Splunk version:
- Index:
- Sourcetype:
- Source:
- Host:
- Time range:
- Timezone:
- Parsing settings changed:

## 4. Ingestion steps
[Document the actual steps taken.]

## 5. Validation searches
```spl
index=soc_lab
| head 20
```

```spl
index=soc_lab
| stats count by sourcetype, source, host
```

## 6. Validation results
- Events searchable?:
- Timestamp parsed correctly?:
- Fields extracted correctly?:
- Unexpected parsing issues?:

## 7. Evidence
[Link sanitized screenshots from `08-evidence/`.]

## 8. Limitations
[Document missing fields, synthetic data, incomplete telemetry or other limitations.]

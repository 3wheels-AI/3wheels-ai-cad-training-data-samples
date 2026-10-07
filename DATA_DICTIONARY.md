# CAD Dataset — Data Dictionary

| Field | Type | Description |
|---|---|---|
| sample_id | string | Unique identifier for the sample |
| data_type | string | 2D or 3D |
| category | string | CAD category |
| domain | string | Engineering domain |
| file_format | string | Original CAD/data format |
| object_type | string | Component or object category |
| units | string | Measurement unit |
| annotation_status | string | Annotation completion status |
| annotation_type | string | Type of annotation |
| quality_status | string | Quality-control status |
| source_type | string | Source category |
| version | string | Dataset/sample version |
| file_path | string | Path of the CAD file relative to the repository root |
| preview_path | string | Path of the PNG preview image |

## Example

```json
{
  "sample_id": "CAD_3D_003",
  "data_type": "3D",
  "category": "automotive",
  "domain": "automotive",
  "file_format": "STEP",
  "object_type": "brake_disc",
  "units": "mm",
  "annotation_status": "annotated",
  "annotation_type": "geometry",
  "quality_status": "verified",
  "version": "1.0",
  "file_path": "samples/3d/CAD_3D_003_brake_disc.step",
  "preview_path": "samples/3d/CAD_3D_003_brake_disc.png"
}
```

# Module titiler.utils

TiTiler utility functions.

None

## Functions

    
### bbox_to_feature

```python3
def bbox_to_feature(
    bbox: Tuple[float, float, float, float],
    properties: Union[Dict, NoneType] = None
) -> geojson_pydantic.features.Feature
```

    
Create a GeoJSON feature polygon from a bounding box.

    
### get_hash

```python3
def get_hash(
    **kwargs: Any
) -> str
```

    
Create hash from a dict.

## Classes

### Timer

```python3
class Timer(
    /,
    *args,
    **kwargs
)
```

#### Instance variables

```python3
from_start
```

Return time elapsed from start.
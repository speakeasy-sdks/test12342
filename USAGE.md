<!-- Start SDK Example Usage [usage] -->
```python
import test
from test.models import shared

s = test.Test()

req = shared.Pet(
    id=596804,
    name='<value>',
)

res = s.pets.create_pets(req)

if res is not None:
    # handle response
    pass

```
<!-- End SDK Example Usage [usage] -->
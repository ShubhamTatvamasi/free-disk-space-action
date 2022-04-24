# free-disk-space

This will remove **android**, **dotnet** and **haskell** sdk and will give us extra **18GB**.

```yaml
name: Free Disk Space
on: push

jobs:
  free-disk-space:
    runs-on: ubuntu-latest
    steps:

    - name: Free Disk Space
      uses: ShubhamTatvamasi/free-disk-space-action@master
```

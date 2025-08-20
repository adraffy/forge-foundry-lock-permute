# `foundry.lock` random permute on `forge i`

Repeated `forge i` randomly permutes `foundry.lock`.

### A, B, C
```
{
  "lib/forge-std": {
    "tag": {
      "name": "v1.10.0",
      "rev": "8bbcf6e3f8f62f419e5429a0bd89331c85c37824"
    }
  },
  "lib/ens-contracts": {
    "tag": {
      "name": "v1.5.2",
      "rev": "5d51c1c5d79a679fe41a516c60dabd9c0232cc67"
    }
  },
  "lib/openzeppelin-contracts": {
    "tag": {
      "name": "v5.4.0",
      "rev": "c64a1edb67b6e3f4a15cca8909c9482ad33a02b0"
    }
  }
}
```

### C, B, A

```json
{
  "lib/openzeppelin-contracts": {
    "tag": {
      "name": "v5.4.0",
      "rev": "c64a1edb67b6e3f4a15cca8909c9482ad33a02b0"
    }
  },
  "lib/ens-contracts": {
    "tag": {
      "name": "v1.5.2",
      "rev": "5d51c1c5d79a679fe41a516c60dabd9c0232cc67"
    }
  },
  "lib/forge-std": {
    "tag": {
      "name": "v1.10.0",
      "rev": "8bbcf6e3f8f62f419e5429a0bd89331c85c37824"
    }
  }
}
```
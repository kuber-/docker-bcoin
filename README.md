Adapted from https://github.com/bcoin-org/bcoin-docker

# Setup

1. Needs environment variables
```    
environment:
    BCOIN_CONFIG: /data/bcoin.conf
    BCOIN_VERSION: v1.0.0-beta.15
```

2. Needs data and conf
```
    volumes:
      - ./data/bcoin/data:/data
      - ./data/bcoin/bcoin.conf:/data/bcoin.conf
```
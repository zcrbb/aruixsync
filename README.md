# aruixsync

config file specific:

```json
{
//   listen on host and port 
  "server": {
    "host": "127.0.0.1",
    "port": 20001
  },
//   file to persist sync information
  "db_file": "db.json",
//   scan file interval (s)
  "sync_interval": 2,
//   recv buffer size (B) 
  "buffer_size": 1024,
//   compress level 0-9, higher is smaller
  "compress_level": 6,
//   is encryption?
  "encryption": false,
//   the peers' ip
  "ips": [],
//   file block size to divide file (B), default is 1M 
  "file_block_size": 1048576, 
//   the share directory
  "sync_dir": "./share"
}

```


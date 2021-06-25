# fileselastalert
```
├── logstash_stdout.conf
└── pipeline
    └── logstash.conf
```


PUT logstash-snort3a/_mapping
{
  "properties": {
    "location": {
      "type": "geo_point"
    }
  }
}

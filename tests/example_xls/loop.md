| survey |
| | type | name | label:english | 
| | select all that apply from toilet_type or specify other | available_toilet_types | What type of toilets are on the premises? |
| | begin loop over toilet_type | loop_toilet_types |
| | integer | number | How many %(label)s are on the premises? |
| | end loop |
| choices |
| | list name | name | label:english |
| | toilet_type | pit_latrine_with_slab | Pit latrine with slab |
| | toilet_type | open_pit_latrine | Pit latrine without slab/open pit |
| | toilet_type | bucket_system | Bucket system |

<img src="https://github.com/data-science-student-society/datathon2019/blob/master/images/traffic_col.png" alt="drawing" width="350"/>

## Traffic Collisions
These datasets contain vehicle crashes and traffic levels happened in San Diego. Data includes collisions metadata and traffic counts metadata.

## Basic Statistics

| Field            | Total number  |
| ---------------- |:-------------:|
| Collisions       | 22,709    |
| Traffic counts   | 11,660     |

## Metadata
- Collisions
```
report_id, date_time,
police_beat, street_no,
street_dir, street_name,
street_type, injured, killed, etc.
```
- Traffic counts
```
id, street_name, limits, all_count, northbound_count, southbound_count,
eastbound_count, westbound_count, total_count, file_no, count_date
```

### Example Collision
``` 
{ 
    'report_id': 170166
    'date_time': 2017/1/1 00:01
    'police_beat': 124
    'street_no': 8300
    'street_name': CAM DEL ORO
    'violation_section': MISC-HAZ
    'violation_type': VC
    'charge_desc': MISCELLANEOUS HAZARDOUS VIOLATIONS OF THE VEHICLE CODE
    'injured': 0
    'killed': 0
    'hit_run_lvl': MISDEMEANOR
}
```

### Example Traffic Counts
```
{ 
    'id': 01AV018207
    'street_name': 01 AV
    'limits': A ST - ASH ST
    'northbound_count': 18010
    'total_count': 18010
    'file_no': 0182-07
    'count_date': 2007/3/13 00:00
}
```

## Possible Tasks:
- Participants will have the option to explore both datasets individually or try to combine the two
sources to build a bigger picture of the effects of traffic on car crashes.

## Download links
- [Traffic Collisions](http://seshat.datasd.org/pd/pd_collisions_datasd.csv)
- [Traffic Collisions Dictionary](http://seshat.datasd.org/pd/pd_collisions_dictionary_datasd.csv)
- [Traffic Counts](http://seshat.datasd.org/traffic_counts/traffic_counts_datasd.csv)
- [Traffic Counts Dictionary](http://seshat.datasd.org/traffic_counts/traffic_counts_dictionary_datasd.csv)

## Citation
Please cite the following if you use the data:

https://data.sandiego.gov/datasets/traffic-volumes/

*Data SD*

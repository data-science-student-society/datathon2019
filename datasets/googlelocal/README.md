<img src="https://github.com/data-science-student-society/datathon2019/blob/master/images/googlelocal.png" alt="drawing" width="350"/>

## Google Local Reviews
These datasets contain reviews about businesses from Google Local (Google Maps). Data includes geographic information for each business as well as reviews.

## Basic Statistics

| Field         | Total number  |
| ------------- |:-------------:|
| Reviews       | 11,453,845    |
| Users         | 4,567,431     |
| Businesses    | 3,116,785     |

## Metadata
- reviews and ratings
- GPS coordinates and address
- User information (places lived, jobs)
- timestamps
- business category, opening hours, etc.

### Example Review
``` 
{ 
    'rating': 3.0,
    'reviewerName': u'an lam', 
    'reviewText': u'Ch\u1ea5t l\u01b0\u1ee3ng t\u1ea1m \u1ed5n', 
    'categories': [u'Gi\u1ea3i Tr\xed - Caf\xe9'], 
    'gPlusPlaceId': u'108103314380004200232', 
    'unixReviewTime': 1372686659, 
    'reviewTime': u'Jul 1, 2013', 
    'gPlusUserId': u'100000010817154263736' 
}
```

### Example Business
```
{ 
  'name': u'Diamond Valley Lake Marina', 
  'price': None, 
  'address': [u'2615 Angler Ave', u'Hemet, CA 92545'], 
  'hours': [[u'Monday', [[u'6:30 am--4:15 pm']]], [u'Tuesday', [[u'6:30 am--4:15 pm']]], 
    [u'Wednesday', [[u'6:30 am--4:15 pm']], 1], [u'Thursday', [[u'6:30 am--4:15 pm']]], 
    [u'Friday', [[u'6:30 am--4:15 pm']]], [u'Saturday', [[u'6:30 am--4:15 pm']]], 
    [u'Sunday', [[u'6:30 am--4:15 pm']]]], 
  'phone': u'(951) 926-7201', 
  'closed': False, 
  'gPlusPlaceId': '104699454385822125632', 
  'gps': [33.703804, -117.003209] 
}
```

## Download links
- Places Data (276mb)
- User Data (178mb)
- Review Data (1.4gb)

## Citation
Please cite the following if you use the data:

*Translation-based factorization machines for sequential recommendation*  
Rajiv Pasricha, Julian McAuley  
RecSys, 2018  

*Translation-based recommendation*  
Ruining He, Wang-Cheng Kang, Julian McAuley  
RecSys, 2017

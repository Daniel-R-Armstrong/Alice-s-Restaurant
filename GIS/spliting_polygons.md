
https://snorfalorpagus.net/blog/2016/03/13/splitting-large-polygons-for-faster-intersections/

Method	|Time taken |	Num. features	|Num. vertices	|Subsequent queries
---|---|---|---|---
None	|--|	2,129,751	|63,472,852 |	> 2.5 hours *
Fishnet	|668 mins	|2,419,661 (+13.6%)|	65,214,478 (+2.7%)|	106 seconds
Katana	|42 mins	|2,213,649 (+3.9%)|	63,960,886 (+0.8%)|	106 seconds


alternative using postgis
http://blog.cleverelephant.ca/2018/06/polygon-splitting.html

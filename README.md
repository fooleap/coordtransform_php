# coordtransform_php

提供了百度坐标（BD09） 、国测局坐标（火星坐标，GCJ02）和地球坐标（WGS84）之间的转换

根据 https://github.com/wandergis/coordtransform 写的 PHP 版本。

## 介绍 

请参考 https://github.com/wandergis/coordtransform

## 用法

```php
<?php
$coordtransform = new CoordTransform();
$coordtransform->bd09togcj02(116.68209, 23.35374);
$coordtransform->gcj02tobd09(116.68209, 23.35374);
$coordtransform->wgs84togcj02(116.68209, 23.35374);
$coordtransform->gcj02towgs84(116.68209, 23.35374);
$coordtransform->wgs84tobd09(116.68209, 23.35374);
$coordtransform->bd09towgs84(116.68209, 23.35374);
```

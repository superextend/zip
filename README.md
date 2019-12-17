# 压缩

zip压缩
## 安装
~~~
composer require 842426182/zip
~~~
use zip\Zip;

$logopath = ''; //要压缩的文件目录
$filepath = '';//要存放的目录
$zips = new Zip();  
$result = $zips->makezip($logopath,$filepath);


# 使用案例代码（DemoCode）

// 1. 引入autoload.php

require './vendor/autoload.php';


$data = [
  'name' => 'zs',
 'age' => 18
];

// 调用 Json的encode静态方法   序列化数据
$jsondata = \phptestsoft8\Json::encode($data);

print_r($jsondata);

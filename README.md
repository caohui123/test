# test
test composer go

composer文件代码：
```apple js
{
  "minimum-stability": "dev",
  "require": {},
  "require-dev":{
    "caohui/test":"dev-master"
  }
}

```

调用方法：
```apple js
$test = new \Lib\Test\test();
echo $test->go();
```

## Rice 数学运算
```Rice
import rice.console;
func main() {
	num i = 1/4 + 4^2;
	console.print(i);
}
```
打印输出：

```
6
```


## Rice 判断
```rice
import rice.console;
func main() {
    num x = 6;
	if(x > 5) {
		print("Well done!");
	}else{
		print("Maybe some errors!");
	}
}
```
打印输出：
```
Well done!
```


## rice 字符串
```rice
import rice.console;
func main() {
	string version = "0.0.1";
	string title = "Text Game";
	string text = "Good";
	print(text);
	print("你好，好耶，稍等");
	print("稍等...");
}
```
打印输出：

```
Good
你好，好耶，稍等
稍等...
```

## Rice 模块系统
```rice
import rice.console;
export func add (int a,int b):int{
	return a + b;
}
```

```rice
import rice.console;
import module;
func main(){
     console.print(module.add(1,2));
}
```

输出:
```
3
```


## Rice 关键字

关键字|说明|支持
-|-|-
import|导入|√
0 |  | 
static|静态|√
0 |  | 
num|自动数的别称（int 整型/float 浮点型/double 双精度浮点型） |√
string|字符串|√
func|函数|√
bool|逻辑|√
true|真(1)|√
false|假(0)|√
null|空|√
return|返回|√
0 |  | 
if|如果|√
elif|如果否则|√
else|否则|√
0 |  | 
for|循环/计数循环|√
while|循环/计数循环|√
break|循环结束|√
0 |  | 


## Rice 版本 0.0.1 关键字

关键字|说明|支持
-|-|-
of|取模块内容|？×
export|导出|？×

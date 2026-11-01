 <div align="center">
	<h1>
	<a href="https://github.com/tbox-studio/tbox-language">
	<img src="https://github.com/uxnt/rtne/blob/main/rtne.svg" height="256" >
	</a>
	</h1>
	<h4>rtne 编程语言</h4>
  <div>
  </div>
	
	
[简体中文](tbox-grammatical-norm-lang/tbox-grammatical-norm-zh-cn.md) • [English](tbox-grammatical-norm-lang/tbox-grammatical-norm-en-us.md)
	
</div>

rtne 是一门开源的编程语言，于 2021 年 8 月 10 日正式启动，由 Uxnt 团队主导开发，并借助 AI 辅助持续改进。

- 2024年3月1日：Tbox 重写为 Rice。
- 2026年11月1日：NaxeLamp 更名为 rtne。

# rtne 0.0.1

## rtne Hello

[Hello.rtne](hello.md)

```Neon
// Screw 100
// BitTea 100
// kone 100
// Cava 100
// CppScript 100
// Neon
// NaxeLamp
// rtne
// Otne > NeonLang 1.0 > NaxeLamp > Rice / Haxe / 2021-8-10

import rtne.io
func main() {
	print("rtne Hello");
}

```
打印输出：

```
rtne Hello
```

## Rice 编译器生成exe文件

```bat
rice hello.ri -o hello.exe
```

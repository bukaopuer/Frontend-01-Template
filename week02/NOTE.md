# 第二周总结

## 编程语言通识

- 形式语言
  - 形式语言一般有两个方面: [语法](https://baike.baidu.com/item/语法/2447258)和[语义](https://baike.baidu.com/item/语义/9716033)。专门研究语言的语法的数学和计算机科学分支叫做**形式语言理论**，它只研究语言的语法而不致力于它的语义。在形式语言理论中，**形式语言**是一个[字母表](https://baike.baidu.com/item/字母表/1314769)上的某些有限长[字符串](https://baike.baidu.com/item/字符串/1017763)的[集合](https://baike.baidu.com/item/集合/73081)。一个形式语言可以包含无限多个字符串
- 有强类型和弱类型语言、有动态和静态语言。

## 词法和类型

- atom
  - whiteSpace（空格有很多种类，无空格代码的实现原理就是用不同的空格种类完成）
  - LineTerminator 换行符 \n
  - Comment 注释(老师说也有特殊的用处以后讲解)
  - Token 一切有效东西的最小单元（无法翻译的内容）
  - Punctuator: 符号 
  - Keywords：关键字 除了特殊的get
  - Literal: 直接量
    - Number
      - 存储 Uint8Array、Float64Array
      - 各种进制的写法
        - 二进制 0b
        - 八进制 0o
        - 十六进制 0x
    - String
      - Character
      - Code Point
      - Encoding
        - unicode 编码 - utf
        - gbk
        - big5
      - Grammar
    - Boolean
      - `true`
      - `false`
    - Null
    - Undefind
- emojy(好玩好用)
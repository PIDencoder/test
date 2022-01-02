借此平台学习和分享一下自己的日常技术博客，欢迎技术交流313211395@qq.com
# MARKDOWN入门使用


## 加入图片
![图片](https://images.unsplash.com/photo-1593421816976-c66bf53c99e7?ixid=MXwxMjA3fDB8MHxzZWFyY2h8MXx8JUU1JUI3JUE1JUU1JThFJTgyfGVufDB8fDB8&ixlib=rb-1.2.1&auto=format&fit=crop&w=500&q=60 "这是一个美女")

LSP你好

![图片2](https://images.unsplash.com/photo-1593422012561-4d80036b8bb6?ixid=MXwxMjA3fDB8MHxzZWFyY2h8Mnx8JUU1JUI3JUE1JUU1JThFJTgyfGVufDB8fDB8&ixlib=rb-1.2.1&auto=format&fit=crop&w=500&q=60 "nihaoya")









## 花样文字


*中华人民共和国万岁*
**中华人民共和国万岁**
***中华人民共和国万岁***
## 超链接
<http://www.mi.com>
[B站](www.bilibili.com "点击进入B站")
[百度][wangzhi1]

[wangzhi1]: http://www.baidu.com "垃圾百度广告多"
## 脚注
待解释[^er]




[^er]:1234456


## 代码块
    helloworld
`#include<iostream>`

```C
uint8_t GPIO_ReadInputDataBit(GPIO_TypeDef* GPIOx, uint16_t GPIO_Pin)
{
  uint8_t bitstatus = 0x00;
  
  /* Check the parameters */
  assert_param(IS_GPIO_ALL_PERIPH(GPIOx));
  assert_param(IS_GET_GPIO_PIN(GPIO_Pin)); 
  
  if ((GPIOx->IDR & GPIO_Pin) != (uint32_t)Bit_RESET)
  {
    bitstatus = (uint8_t)Bit_SET;
  }
  else
  {
    bitstatus = (uint8_t)Bit_RESET;
  }
  return bitstatus;
}

   hellloword
```
## 奇奇怪怪
诶诶奥飞回我了
说说看感觉
---
***
___
~~我不想考试~~
>1
>>2
>>>3
>>>>4
>>>>>5

## 表格
|name|xuehao|chenngji|
|:-------:|:------:|:------:|
|baishaihua|19040500115|100|
|dongyujie|19040500105|99|
|niuhuijie|19040500099|98|
|wensiqi|19040600025|97|
|tongruiqian|19040235323|0|
|yangyilin|19023203522|00|























# 变更内容

1. 修改日期字符串转换函数**`dateToDayDateString`**

   将格式转化逻辑由

   ```plaintext
   "Sun, 10 Jan 2021 22:22:22 GMT" -> "2021.01.10”
   改为
   "Sun, 10 Jan 2021 22:22:22 GMT" -> "2021-01-10 22-22-22”
   ```

   添加对小时、分钟和秒的处理，并调整返回的字符串格式
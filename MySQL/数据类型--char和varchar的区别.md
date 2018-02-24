# char和varchar的区别

## char 

1. 固定长度
2. 最大255字节
3. 系统总是分配最大的存储空间，即使长度不够都会为其分配规定的存储空间，


## varchar

1. 长度可变
2. 最大长度65535字节
3. 系统会根据实际需要空间进行存储

## 比较

效率上 char > varchar > text, 如果是Innodb引擎，推荐使用varchar代替char


date: 2018-03-24-星期六

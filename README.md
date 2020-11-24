# C-
## c语言的指针
`*a`;带有`*`将指向一个变量  

`&`; 返回变量的地址  

`sizeof()`;返回变量的大小


## c语言的枚举
`enum　枚举名　{枚举元素1,枚举元素2,……};`  
> 注意：第一个枚举成员的默认值为整型的 0，后续枚举成员的值在前一个成员上加 1。我们在这个实例中把第一个枚举成员的值定义为 1，第二个就为 2，以此类推。
> 没有指定值的枚举元素，其值为前一元素加 1。也就说 spring 的值为 0，summer 的值为 3，autumn 的值为 4，winter 的值为 5  
### 枚举变量的声明
1. 先定义枚举类型，再定义枚举变量
> 
```
enum DAY
{
      MON=1, TUE, WED, THU, FRI, SAT, SUN
};
enum DAY day;
```
2. 定义枚举类型的同时定义枚举变量
> 
```
enum DAY
{
      MON=1, TUE, WED, THU, FRI, SAT, SUN
} day;
```
3. 省略枚举名称，直接定义枚举变量
> 
```
enum
{
      MON=1, TUE, WED, THU, FRI, SAT, SUN
} day;
```

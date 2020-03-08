# python基础命令
#-- coding: utf-8 --         //加在第一行可以输出汉字
Print          //输出与php中的echo一致
Message   //变量可以用
'\n'  添加空行
小数
括号外面%可以给括号里面的赋值按照%（1，2，3，4）为里面的第几个赋值当然也可以计算
例如
my_name = 'Zed A. Shaw'
my_age = 35 # not a lie
 my_height = 74 # inches
 my_weight = 180 # lbs
 my_eyes = 'Blue'
my_teeth = 'White'
 my_hair = 'Brown' 
print "If I add %d, %d, and %d I get %d." % ( my_age, my_height, my_weight, my_age + my_height + my_weight) 
输出
If I add 35, 74, and 180 I get 289 

title() 首字母大写
upper（）全字母大写
lower（）全字母小写
str = "www.runoob.com"
print(str.upper())          # 把所有字符中的小写字母转换成大写字母
print(str.lower())          # 把所有字符中的大写字母转换成小写字母
print(str.capitalize())     # 把第一个字母转化为大写字母，其余小写
print(str.title())          # 把每个单词的第一个字母转化为大写，其余小写 

字符串全元素大写
user_1=['gsf','lk','lgf','txd','hw'
#首先利用 isinstance(gsf,str)判断gsf的值是不是str格式（字母）是就输出一个gsf.upper()的值然后循环后面的for循环挨个输出user_1的值，不是就直接输出一个gsf保存到变量的中
user_3= [gsf.upper() if isinstance(gsf,str) else gsf for gsf in user_1]
\t 制表符
\n换行符号
.append("xxx") 在末尾添加新变量值xxx
.Insert(数字'xxx')在数字号位置加入xxx变量值 
Del xxx[数字]删除xxx变量中数字号位置的变量值 
 //注数字是指你要删除的变量值在变量中的几号位置
 ////"."号前接你所要改变的变量 
新变量 = 变量.pop(数字) 删除变量中数字号位置的变量
print（新变量）打印删除变量的值
.remove('变量值') 删除指定变量值，   


（Fruits）变量.sort()    按照变量里变量值首字母顺序排序
（Fruits）变量.sort(reverse=True)    按照变量里变量值首字母顺序排序  
//注排列的顺序是永久的Fruits是一个变量下同
print(sorted(cars))   输出临时排序  cars变量值＋
print(sorted(cars，reverse=True）） 反向
//排列是单次的

（Fruits）变量.reverse（）反转排列顺序排列
Len(变量)  输出有多少个元素

For  xxx in xxx：  Python从列表xxx中取出一个名字，并将其存储在变量xxx中。最后，我们让Python打印前面存储到变量xxx中的名字 
for语句末尾的冒号告诉Python，下一行是循环的第一行 
for xxxx in range(1,10):   //打印1-9的数字
range()让你能轻松地生成一系列的数字（）里你要的数字范围例如1，10即输出1-9
range（1，10，2）即隔1个单位输出一个数字
kong.append(pfang)    将新计算得到的平方值附加到列表kong末尾 
b=(max(a))  输出最大
print(b)
print(min(a))  输出最小
print(sum(a))  输出和

list(range(1,21))   输出1-21的所有值
e.append(d)  把d变量的值赋给e
gf_5=[gf_6 for gf_6 in range(1,30)]   //列表法直接生成   
print（变量值[0:3]）   //输出0-3的变量值
gsf_2 = gsf_3[:]  复制变量
my_foods.append('cannoli')   在列表my_foods里添加值'cannoli

4.5元组
dimensions[0] = 250 元组的值不可修改

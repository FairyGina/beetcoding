비트코딩

1번
print(2020)
print(4+3)
print("Hello")
print('Hello')
print("3"+"A")

2번
1. 숫자와 문자(or 문자열)는 더할 수 없다.
2. 문자열은 ""사이에 넣어야 출력이 된다.

3번
print(1);
print(2,end='')
print(3,end='')
print(4)
print(5,end='finish')
print(6)
print('''This is My Story for you''')

4번
print(1234567890)

5번
print("제 이름은 홍길동입니다.")

6번
print("14590") -> 14590
print(abc) -> 오류: abc 변수로 여기는 듯. abc 그대로 출력할 시 "" 필요
print(13-2) -> 11
print(12+4/2+1) -> 15.0   */연산은 자동으로 실수 영역으로 계산됨
print("A"+"B"+"C") -> ABC
print("A"-"B") -> 오류: 문자는 뺄 수 없음. 
print("A"+"B") -> AB
print(52-"33") -> 오류: 숫자에서 문자열은 뺄 수 없음.

7번
print('''그대는
나에게 왔다가
떠나가네...''')

8번
print('''238c7
238c7''')

9번
a
b cD
EF

10번
A=1
B=2
C=A+B
print(A)
print(B)
print(C)

11번
A=5
B=A
A=1
print(A); print(B)
print(A,B)

12번
A,B=1.3,2
C=A+B
A=A-0.3
D=1

print(A,B,C)
print(A+B)
print(C+1)
print(D+2.0)

13번
x,y=2,1
z=x+y
print(z)

14번
a,b=2,3
print(a+b)

15번
117.6

16번
x,y,z=1,2,3
print(z*z+x)
print((z*z+x)*(z*z+x))
print((z*z+x)*(z*z+x)*(z*z+x))

17번
a,b=2.5,4
c=4*a+b
print(c)

18번
1.0
3.0
-0.5
4.0
0.0
2.0

19번
10000
6000
46000
10000.0
-18000.0

20번
30
30
30  *변수값 동시 저장 후 대입 연산자일시 맨 오른쪽 값이 저장된다.

21번
x,y,z=1,2,1.5

print(x) -> 1
print(x+y) ->3
print(x+y+z) ->4.5
print(2x) -> error
print(2*x) ->2
print(2.0*x) -> 2.0
print(x-1.0) -> 0.0
print(x-1) -> 0
print(z-0.5) -> 1.0
print(xz) -> error
print(x*z) -> 1.5

22번
name='kevin'
work='IT company'
num1=5.3
num2=4.7517
print("I'm", name, "and work in", work)
print("I'm {} and work in {}".format(name,work))
print("This is{:8.2},{:8.2}".format(num1,num2))

23번
country='Korea'
population='50M'
print("{} has about {} people".format(country,population))

24번
num1=1.23456789
num2=0.22222222
num3=1.87654321
num4=0.21314151

print("First:{:.2}".format(num1))
print("Second:{:10.4}".format(num2))
print("Third:{}".format(num3))
print("Fourth:{:10.4}".format(num4))   *정수 부분 0일시 포함x(0.xx..)

25번
add=12+21
sub=41-22
mul=2*8
div=3/2
div_int=3//2
exp=10**3
mod=34%5

print(add)
print(sub)
print(mul)
print(div)
print(div_int)
print(exp)
print(mod)

26번
a,b,c=1,2,3
a+=1
b+=a
print(a,b)
a-=1
c/=b
print(a,b,c)

27번
x,y,z=14,3,5

print(x%y)
print(x//z)
print(x/z+y)
print(y**z+y)
print(x%z*y)
print(z-x**1*y)
print(z-x*y**2)
print(z**2//z)
print(x%z**2+y)

28번
x,y,z=3,7,21

print(x*y**2)
print((x*y)**2)
print(z%(x+y))

29번
a,b,c,d=2,7,3,17

print(a+b) -> 9
print(b%c) -> 1
print(a%b-c) -> -1
print(d//b*a) -> 4
print((a+b)*d//a) -> 76
print(b**a%a*c) -> 3
print(d/(a**(a**a+1))+1) -> 1.53125
print(c%(a*b)+d) -> 20
print(c*(a%a)//a) -> 0
print(d//(c**c-5)) -> 0

30번
a,b=3,7
c=b//a
print(a,b,c)

31번
9
1.25
26.25

32번
4
0
-3

33번
x,y,z,w=11,5,7,13
print(y+z-x)
print(x+y+z-w)
print((x+y+z-w)*(x+y+z-w))
print((x+y+z-w)*(x+y+z-w)*(x+y+z-w)) 

34번
a,b,c=1,3,5
print(a/a)
print((b-a)/a)
print(b/a)
print((c-a)/a)
print(c/a)

35번
int_1=0
int_2=3
long_1=12345678
long_2=0x142
float_1=0.0
float_2=1.35
complex_1=1j
complex_2=1+3j

print('변수 int_1과 int_2의 자료형은',type(int_1),type(int_2))
print('변수 long_1과 long_2의 자료형은',type(long_1),type(long_2))
print('변수 float_1과 float_2의 자료형은',type(float_1),type(float_2))
print('변수 complex_1과 complex_2의 자료형은',type(complex_1),type(complex_2))

36번
int_1=1
float_1=1.0
print('{}의 자료형은'.format(int_1),type(int_1))
print('{}의 자료형은'.format(float_1),type(float_1))

37번
3 <class 'int'>
3.5 <class 'float'>
(1.5+1j) <class 'complex'>

38번
a=0b10110101
b=0b11011001
c=a+b
print(a,b,c)
print(bin(a&b),a&b)
print(bin(a|b),a|b)
print(bin(a^b),a^b)
print(bin(a>>2),a>>2)
print(bin(a>>3),a>>3)
print(bin(a<<2),a<<2)
print(bin(~a),~a)

39번
1) 1101
2) 33
3) 5e
4) 11f
5) 95(16진수로 계산)

40번
0b1110
0b110
6
0b1001000
0b100010000

41번
0x11
0b1100001000
41392
0o5274
0b111110101

42번
a,b,c=11,22,33
print(bin(a))
print(hex(b))
print(oct(c))
print(bin(a+b+c))

43번
0b1111010 122

44번
0b10101000 168
0b1010111 87
0b11111111 255
0b1101001 105
-0b11101101 -237

45번
num1,num2,num3=3,6,2
print(num1&num2)
print(num1|num2)
print(num1^num2)
print(num1&num2|num3)

46번
num=-3
num=~num+1   *오차 1 생각하기
print(num)

47번
num=7
num<<=1
print(num)

48번
num=1
num<<=1
print(num)
num<<=1
print(num)
num<<=1
print(num)
num<<=1
print(num)
num<<=1
print(num)
num<<=1
print(num)
num<<=1
print(num)

49번
boolean_1=True
print(boolean_1)
boolean_2=False
print(boolean_2)

boolean_3=1>0
print(boolean_3)

50번
boolean_1=1>2
boolean_2=3==3
boolean_3=1>=1
boolean_4=4!=2

print(boolean_1)
print(boolean_2)
print(boolean_3)
print(boolean_4)

51번
boolean_1=True&True
boolean_2=True&False
boolean_3=False|False
boolean_4=True|False
boolean_5=True^True
boolean_6=True^False
boolean_7=False^False

print(boolean_1)
print(boolean_2)
print(boolean_3)
print(boolean_4)
print(boolean_5)
print(boolean_6)
print(boolean_7)

52번
num=13
result1=1<num<100
print("1초과 100미만인가? ",result1)

53번
boolean_1=False -> False
boolean_2=-True -> -1
boolean_3!=True -> error
boolean_4=True==True -> True
boolean_5=True==False -> False
boolean_6=True>True -> False
boolean_7=True>False ->True
boolean_8=False>True ->False

54번
print((3==3)!=(5<4)<=(0=0))

55번
print(True&False) -> False
print(True^(True|False)) -> False
print((True|False)|False) -> True
print((True^False)^(False^False)) -> True
print(True&(False^False)^True) -> True
print(False|(False|False)^False) -> False

56번
print(3>0!=2<1) -> False
print(2!=3==3!=2) -> True
print((3==1)^(4>2)&(1<0)) -> False
print((1!=1)|(3>0&5<1)) -> True
print(2<=3^5!=1^3==3) -> False

57번
print(True&False^True)

58번
num=1
boolean_1=num==0
print(boolean_1)

59번
num=5
print(num%3==0|num%2==0)

60번
print('작은따옴표')
a='''작은따옴표
        세 개'''
b="""큰따옴표
세 개"""
print(a)
print(b)

61번
text_1='문자열에서 \n을 쓰면 줄바꿈이 되고 \n을 사용하면 탭 공백이 넣어진다.'
text_2="문자열에서 '을 쓰려면 문자열을 큰 따옴표로 선언하거나 \'와 \"을 쓰면 된다"
text_3='마찬가지로 작은 따옴표 내에서"는 그냥 출력 된다'

print(text_1)
print(text_2)
print(text_3)

62번
text="item_1 + \
item_2 + \
item_3"
print(text)

63번
print("*"*40)
print("내 이름은"+"Tom이다")

first="내 이름은"
second=" Tom이다"
string=first+second
print(string)

a="안"
b="녕"
print(a+b+" "+first+second)

print("*"*40)

64번
이름은 Chan
나이는 18
키는 182.5
국가는 nation

65번
print('korea')

66번
1234
t6      7'
89"10

67번
가나
다라
마바    아
자차카
타
파하

68번
CARAIR

69번
print("국가 : 대한민국\n수도 : 서울\n언어 : 한국어\n인구 : 51,779,148")

70번
name="Julla"
age=21
height=162
weight=47
major="Mathematic"

print('='*40)
print("\nMy name is "+name)
print("\nI\'m",age,"years old")
print("\nI\'m",height,"cm and",weight,"kg")
print("\nI major in "+major+"\n")
print('='*40)

71번
print("Hello\nI\'m 20 years old\nand wand to be \'cool\' guy\nnice to meet you")

72번
print("C:\\\'aa\\\"abc.txt")

73번
motto="Enjoy my life"
print('='*40+"\nMy motto is",motto,"\nI will study so hard to achieve it\n"+'='*40)

74번
string="PYTHON"

print(string[0])
print(string[1])
print(string[5])

print(string[-1])
print(string[-3])
print(string[-6])

75번
mystr="ORANGE"

print(mystr[0])
print(mystr[4])
print(mystr[-3])
print(mystr[-6])

76번
string="PYTHON"

print("*"*5+"정방향"+"*"*5)
print(string[0:2])
print(string[4:5])

print("*"*5+"역방향"+"*"*5)
print(string[-3:-1])
print(string[-6:-5])

77번
mystr="GOOD NIGHT"

print(mystr[1:3])
print(mystr[4:10])
print(mystr[-3:-1])
print(mystr[2:4])

78번
string = "Hello, My name is Haemin Park"
print(string.upper())
print(string.lower())
print(string.title())
print()

print(string.count('i'))
print(string.endswith('k'))
print(string.startswith('h'))
print(string.lower().startswith('h'))
print()

string_1=string.split()
string_2=string.split(',')
print(string_1)
print(string_2)

79번
1)
string = "ABCDEFG"
print(string[0])
print(string[1])
print(string[5])
print(string[6])
print(string[3])
2)
string = "ABCDEFG"
print(string[0:3])
print(string[5:7])
print(string[0:2]+string[3:6])
3)
string = "ABCDEFG"
print(string[1:4])
print(string[5]+string[4]+string[3])
print(string[6]+string[4]+string[2])

80번
string="abcdefghijklmn"
num1,num2=5,8
print(string[num1-1:num2])

81번
string="동해물과 백두산이 마르고 닳도록 하느님이 보우하사 우리나라 만세 무궁화 삼천리 화려강산 대한 사랑 대한으로 길이 보전하세"
print(len(string)-len(string.split()))

82번
sentenve="I\'m form Korea, but I\' don\'t like Kimchi"
print(sentenve.upper())
print(sentenve.lower())
print(sentenve.title())

83번
print(string)
string="This is my favorite dish"
print(string.startswith('T'))
print(string.endswith('h'))
print(string.count('h'))

84번
a=input()
print("입력한 숫자는 : ",a)

85번
print("(사용자 기본정보)")
name=input("이름을 입력하세요 ")
age=input("나이를 입력하세요 ")
print("당신의 이름은",name,"당신의 나이는",age)

86번
a=int(input())
b=int(input())
print(a*b)

87번
name=input("이름을 입력하세요.")
cm=int(input("키를 입력하세요."))
kg=int(input("몸무게를 입력하세요."))
print(name+"의 키는",cm,"cm, 몸무게는",kg,"kg")

88번
a, b = input('숫자 두 개를 입력하세요: ').split()
a=int(a); b=int(b)
print("입력한 두 수의 합은",a+b)

89번
name=input("이름은?")
print(len(name))

90번
first=int(input("first number?"))
second=int(input("second number?"))
boolean_1=first>second
print(boolean_1)

91번
first=int(input("first number?"))
second=int(input("second number?"))
third=int(input("third number?"))
boolean_1=first+second==third
print(boolean_1)

92번
year=int(input("년도를 입력하세요 : "))
age=year-1997
print("{}년 지수의 나이는 {}입니다.".format(year,age))

93번
a,b,c,d=input("네 수를 입력하세요 : ").split()
a=int(a); b=int(b); c=int(c); d=int(d); 
average=(a+b+c+d)/4
bunsan=((a-average)**2+(b-average)**2+(c-average)**2+(d-average)**2)/4
print("평균 :",average)
print("분산 :",bunsan)

94번
string=input("문장을 입력하세요 : ")
print(f"해당 문장의 단어 수는 {len(string.split())}개입니다.")

95번
count=[1,2,3,4,5]
fruits=['apple','pear','peach','melon']
print(count)
print(fruits)
print(count[1:3])
print(fruits[2])

96번
colors=['red','orange','yellow','green','blue','purple']
print(colors)
print(colors[3])
colors[3]='black'
print(colors)
colors=colors+['white']
print(colors)

97번
colors=['red','yellow','blue']
print(colors)

print('yellow의 위치',colors.index('yellow'))
print('blue의 위치',colors.index('blue'))
print()

colors.append('purple')
print(colors)

colors.insert(2,'pink')
print(colors)

colors.extend(['white','black'])
print(colors)

boolean='red' in colors
print(boolean)

boolean='orange' in colors
print(boolean)

98번
colors=['red','yellow','blue']
print(colors)

colors.sort()
print(colors)

colors.reverse()
print(colors)

print(colors.pop())
print(colors)

colors.remove('red')
print(colors)

print(colors.count('yellow'))

99번
numbers=[14.26,5,426.4,0.221]
print(len(numbers))
print(max(numbers))
print(min(numbers))
print(sum(numbers))
print(sorted(numbers))
print(numbers)
string="python"
print(list(string))

100번
['Julio', 'Kane', 'Kaka', 'Messi']
KaneMessi
['Julio', 'Kane', 'Kaka', 'Messi']
['Henry']
['Kane', 'Kaka', 'Ronaldo', 'Henry']

101번
even_under10=[2,4,6,8]
print(even_under10)

102번
[[1, 2], 'samsung', 2.5, 'A']
[1, 2]
m
['samsung', 2.5]
[[1, 2], 'samsung']

103번
cars=['Hyundai']
print(cars)
cars.extend(['Benz','Toyota'])
print(cars)
del(cars[2])
print(cars)

104번
[1, 2, 3, 10, 20, 30]
[1, 2, 3, 1, 2, 3, 10, 20, 30]

105번
3
[5, 2]
music
17
['A', [5, 2, 10]]

106번
sports=['soccor']
print(sports)
sports.extend(['baseball','hockey'])
print(sports)
sports.insert(1,'tennis')
print(sports)
sports.sort()
print(sports)
print(sports[3])
sports.pop()
sports.reverse()
print(sports)

107번
mytuple=(1,2,3)
print(mytuple)

mytuple=('이것이 튜플',23.31,(1,2,3))
print(mytuple)

mytuple='소괄호 없어도 튜플',1.22,'을 만들 수 있다'
print(mytuple)

108번
mytuple=('a','b','c','d')
print(mytuple)
print(mytuple[1])

mytuple=("phthon",(1,2,3),[4,5,6])
print(mytuple[0])
print(mytuple[0][2])
print(mytuple[1][1])
print(mytuple[2][0])

mytuple=('p','y','t','h','o','n')
print(mytuple[1:4])
print(mytuple[:3])
print(mytuple[:])

yourtuple=(10,20,[1,3,5])
print(yourtuple)
yourtuple[2][1]
print(mytuple)

tu_1=(1,2,3)
tu_2=(4,5,6)
print(tu_1+tu_2)
print(tu_1*2)

109번
number=(1,2,3,4,5,6,7,8,9,10)
print(sum(number))

110번
('kim', 'lee', 'park', 'choi')
['choi', 'kim', 'lee', 'park']
('kim', 'lee', 'park', 'choi', 'oh', 'i')
('kim', 'lee', 'park', 'choi')
<class 'tuple'>

111번
0 1 2
1 2 5
True
(0, 2, 4, 6, 8)

112번
x={'a':10,'b':20,'c':30}
print('초기상태 :',x)

x['d']=40
print('d 추가: ',x)

x['b']=50
print('b 수정: ',x)

del(x['c'])
print('c 삭제: ',x)

x['a']=20
print('a 추가: ',x)

113번
list1=[['a','b'],['c','d'],['e','f']]
print(dict(list1))
list2=['12','34','56']
print(dict(list2))

114번
height={'Jun':178,'Mina':164}
print(height.get('Jun'))
height['Tom']=182
print(height)

a=height.pop('Mina')
print(a,height)
height['Robin']=146
b=height.popitem()
print(b,height)

newheight={'billy':188,'Dony':172}
height.update(newheight)
print(height)

print(height.keys())
print(height.values())
print(height.items())

115번
Dahyun={'height' : '158cm','age' : 21,'birth' : 'May 28th','group' : 'twice'}
print('Dahyun is',Dahyun.get('height'))
print('Dahyun belongs to',Dahyun.get('group'))

116번
tony={'korean':100,'english':93,'mathematics':98,'science':86}
average=sum(tony.values())/4
print(average)

117번
{'김연아': '피겨스케이팅', '박지성': '축구'}
{'김연아': '피겨스케이팅', '박지성': '축구', '정현': '테니스'}
{'김연아': '피겨스케이팅', '정현': '테니스'}

118번
jobs={'김연아':'피겨스케이팅',
'박지성':'축구',
'정현':'테니스',
'박태환':'수영'}
var=input('운동선수 입력 : ')
result=jobs.get(var)
print('{}(은)는 {} 선수이다.'.format(var,result))

119번
grade={'Wonjeong':99,'Kyunghoo':76,'Hyunsoo':83}
print(sum(grade.values())/len(grade))

120번
myset={1,2,3}
print(myset)
print(type(myset))

myset={'ice',1.2,(1,3,5)}
print(myset)

myset={1,2,3,2,3,2,2}
print(myset)

121번
a={1,2,3,5,6,8}
b={1,3,4,5,6,7}

print(a.union(b))
print(a.intersection(b))
print(a.difference(b))
print(a.symmetric_difference(b))

122번
myset={1,3,5}
print(myset)
myset.add('A')
print(myset)
myset.update({1,3},{2,3})
print(myset)

print(myset.pop())
print(myset)
print(myset.pop())
myset={'apple','melon','strawberry','grape'}
print(myset)

myset.discard('strawberry')
print(myset)
myset.remove('grape')
print(myset)

myset.clear()
print(myset)

123번
a={10,20,70,90}
b={10,30,40,70}

print(a|b)
print(a.union(b))

print(a&b)
print(a.intersection(b))

print(a^b)
print(a.symmetric_difference(b))

print({10,20,70,80,90}.issuperset(a))
print({20,30,50}<=a)
print({10,30,40}<=b)
print({10,20,30,50,70,90}>=a)

124번
True
False
3    
3  

125번
myset=set([1,2,3,4,5])
print(myset)
myset.remove(1)
myset.remove(3)
myset.remove(4)
myset.add(7)
myset.add('ferren')
myset.add(11)
print(myset)

126번
{1, 2, 4, 5}
{1, 2, 3, 4, 5, 6}
{1, 2, 3, 4, 5, 6}
True
True

127번
num16={1,2,4,16}
num30={1,2,3,5,6,10,15,30}
print(num16&num30)

128번
a,b,c,d,e,f,g,h,i,j=input().split()
a=int(a); b=int(b); c=int(c); d=int(d); e=int(e); f=int(f); g=int(g); h=int(h); i=int(i); j=int(j)
numset=[a,b,c,d,e,f,g,h,i,j]
print(max(numset))

129번
if(len(i)==5):
    b.append(i)

130번
list1.sort()
list1.reverse()
*list1.sort(reverse=True)

131번
Dohee={'수학':76,'과학':89,'영어':93}
Juwon={'수학':88,'과학':87,'영어':100}
SeoHee={'수학':86,'과학':93,'영어':82}
average={sum(Dohee.values())/len(Dohee),sum(Juwon.values())/len(Juwon),sum(SeoHee.values())/len(SeoHee)}
for i in average:
    print(i)
print(sum(average)/len(average))


143번
number=int(input("Enter the number:"))
if(number%2==0):
    print('even number')
else:
    print('odd number')

144번
number=int(input("Enter the number:"))
number/=10000
print(number)
if(number>=53):
    print('old')

145번
num=13
print(num%2==0|num%3==0)
*num=13
if(num%2==0|num%3==0):
    print('True')
else:
    print('False')

146번
height=int(input())
if(height>184):
    print('Tall')
elif(height<146):
    print('Short')
else:
    print('Regular')

147번
grade=input()
if(grade=='A'|grade=='B'):
    print('참 잘했습니다.')
if(grade=='C'|grade=='D'):
    print('좀 더 노력하세요.')
if(grade=='F'):
    print('다음 학기에 다시 수강하세요.')

148번
year=int(input())
if(year%4==0):
    if((year%100==0)&(year%400!=0)):
        print('평년')
    else:
        print('윤년')


149번
1) a,b=map(int,input().split())
print(abs(a-b))
2)num=list(map(int,input().split()))
print(max(num)*min(num)-(sum(num)-max(num)-min(num)))

150번
x,y=map(int,input().split())
print((x>50&x<100)&(y>40&y<80))

151번
string=input()
string = string.lower()
if(string.startswith('a')|string.startswith('b')|string.startswith('c')|string.startswith('d')|string.startswith('e')):
    print('Good Sentence')

152번
colors=['red','orange','blue','green','white','black','dark blue','purple']
add=input()
if add in colors:
    print('Sorry')
else:
    colors.append(add)
    print(colors)

153번
a=int(input('enter 1st number: '))
b=int(input('enter 2nd number: '))
print('Nice') if a+b>=0.5*a*b else print('Bad')

154번
a,b,c=map(int,input().split())
print(a) if (a<b)&(a<c) else print(b) if (b<a)&(b<c) else print(c)

155번
a=int(input())
print('양수') if a>0 else print('음수')
print('홀수') if a%2!=0 else print('짝수')
print('3의 배수',a%3==0) if a%3==0 else print('3의 배수',a%3==0)
print('5의 배수',a%5==0) if a%5==0 else print('5의 배수',a%5==0)

156번
a,b,c=input().split()
a=int(a); c=int(c)
if b=='+': print(a+c)
if b=='-': print(a-c)
if b=='*': print(a*c)
if b=='/': print(a/c)

157번
import random
list1=['a','b','c','d']
print(list1)
random.shuffle(list1)
print(list1)
random.shuffle(list1)
print(list1)
chr1=random.choice(list1)
print(chr1)

158번
import random
n = random.randrange(1,100)
while True:
    ans1=input("Guess number (Q to exit)")
    if ans1.upper()=="Q":
        break
    ans2=int(ans1)
    if(n==ans2):
        print("Correct!")
        break
    elif(n>ans2):
        print("Choice higher number")
    else:
        print("Choice lower number")

159번
import random
n=random.randrange(10,100)
print(n)

160번
import random
n=random.uniform(0,10)
print(round(n,1))
*import random
num=round(random.random()*10,1)
print(num)

161번
import random
a,b=map(int,input().split())
n=random.randrange(a,b)
if(abs(a-b)==1):
    print('no integer betwwen two numbers')
else:
    print(n)

162번
import random
num=[]
for i in range(4):
    num.append(random.randrange(10,21))
print(num)
print(sum(num)/4)
if(sum(num)/4>14):
    print('Big')
else:
    print('small')

163번
import random
n=random.randrange(1,3)
user=int(input('level1 (1~2) : '))
if(user!=n):
    print('Failure!\nAnswer is :',n)
else:
    print('Correct!')
    n=random.randrange(1,5)
    user=int(input('level2 (1~4) : '))
    if(user!=n):
        print('Failure!\nAnswer is :',n)
    else:
        print('Correct!')
        n=random.randrange(1,9)
        user=int(input('level1 (1~8) : '))
        if(user!=n):
            print('Failure!\nAnswer is :',n)
        else:
            print('Lucky')

164번
import random
cars=['Hyundai','Kia','BMW','Benz']
print(cars)
random.shuffle(cars)
print(cars)
print(cars[0]=='Hyundai')

165번
i=5
print("Count Down Starts!")
while i>=0:
    print(i)
    i-=1
print("Boom!")

166번
i=1
while True:
    i+=1
    if 3<=i<=5:
        continue
    print(i,'번째......')
    if i==7:
        break

167번
num=10
while num<=18:
    print(num)
    num+=2

168번
1248163264

169번
while True:
    str=input('Enter the alphabet : ')
    if(str=='q'):
        print('finish')
        break

170번















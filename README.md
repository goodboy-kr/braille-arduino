# E2B_arduino
English change to Braille

This library is english change to braille

please import E2B



E_B(char x) : return char[6 or 13(english or number)]
B_E(int x[]) : return char


a:{1, 0, 0, 0, 0, 0}, //value[0][]  
b:{1, 1, 0, 0, 0, 0},  
c:{1, 0, 0, 1, 0, 0},
d:{1, 0, 0, 1, 1, 0},  
e:{1, 0, 0, 0, 1, 0},  
f:{1, 1, 0, 1, 0, 0},  
g:{1, 1, 0, 1, 1, 0},  
h:{1, 1, 0, 0, 1, 0},  
i:{0, 1, 0, 1, 0, 0},  
j:{0, 1, 0, 1, 1, 0},  
k:{1, 0, 1, 0, 0, 0},  
l:{1, 1, 1, 0, 0, 0},  
m:{1, 0, 1, 1, 0, 0},  
n:{1, 0, 1, 1, 1, 0},  
o:{1, 0, 1, 0, 1, 0},  
p:{1, 1, 1, 1, 0, 0},  
q:{1, 1, 1, 1, 1, 0},  
r:{1, 1, 1, 0, 1, 0},  
s:{0, 1, 1, 1, 0, 0}, //s value[18][]  
t:{0, 1, 1, 1, 1, 0},  
u:{1, 0, 1, 0, 0, 1},  
v:{1, 1, 1, 0, 0, 1},  
w:{0, 1, 1, 1, 1, 1},  
x:{1, 0, 1, 1, 0, 1},  
y:{1, 0, 1, 1, 1, 1},  
z:{1, 0, 1, 0, 1, 1},  //value[25][]  
  
//특수기호  
',':{0, 1, 0, 0, 0, 0}, //value[26][]]  
'.':{0, 1, 0, 0, 1, 1},  
'-':{0, 1, 0, 0, 1, 0},  
'?':{0, 1, 1, 0, 0, 1},  
'_':{0, 0, 1, 0, 0, 1},  
'!':{0, 1, 1, 0, 1, 0},  
' ':{0, 0, 0, 0, 0, 0},//value[32][]  

//순서대로 대문자 숫자  
CAP : {0, 0, 0, 0, 0, 1}, //value[33][]  
NUM : {0, 0, 1, 1, 1, 1}  //value[34][]  

ex)   
a ->                   {1, 0, 0, 0, 0, 0}  
A -> {0, 0, 0, 0, 0, 1, 1, 0, 0, 0, 0, 0}  
1 -> {0, 0, 1, 1, 1, 1, 1, 0, 0, 0, 0, 0}  
, -> {0, 1, 0, 0, 0, 0}  
  
  


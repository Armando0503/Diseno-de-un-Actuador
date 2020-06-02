# Diseno-de-un-Actuador

%Fe[]= N I L B 

%Fm= Fe= (Fej)/w

%p= V I

%p= w torque 

%torque = F r

%V=RI 

%R=pcu*(L/Wt) 

%N= Rad/s

%n= Densidad de partículas libres cargadas por unidad de volumen 

%W=r*2 

%L=largo 

%t=groso

N=100;

w=310/(3*pi);

Vs=6;

I=70;

B=9;

pcu= 1.71x10−8;

%Paso 1: Sacar Fuerza

F=NILB;

F= (100 )(.07)(0.007)(9);

%F=0.441 N 

%Paso 2: Calculamos torque

%1.- Calculamos p 

p= V I ;

%p= (6 ) (70 x 10^-3) = 0.42 w 

%2.- Calculamos torque

torque = p/w;

torque= 0.42 w/(310/3*pi);

%torque=1.293 10x−3Nm C. 

%Paso 3: Sacamos r 

torque = F r;

r=(torque/F);

%r= 1.293 10x−3Nm/0.441N = 2.93mm 

W=2r;

%w=5.86 mm 

%Paso 4: Calculamos t, el cual es el grosor de la espira

Sacamos R: 

R=V/I;

%R=6v/0.07A

%R= 85.7142 

%pcu= 1.71x10−8∆m 

R=pcu*(L/Wt);

t=(pcuL)/RW;

%t=(1.71x10−8∆m ∗ 0.007m)/(85.7142 ∗0 .00293m)

%t=4.76 x 10−10m

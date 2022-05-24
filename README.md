# Programas en C++ de Gonzalez Isaac
## Información del Autor:
`Autor: Gonzalez Sanchez Isaac Exequiel`

`Correo: isaac.gonzalez.sanchez@utelvt.edu.ec`

## Programas
```
GonzalezIsaac-Compara.cpp
GonzalezIsaac-CuentaMoneda.cpp
GonzalezIsaac-PuntoVenta.cpp
GonzalezIsaac-SumaN.cpp
GonzalezIsaac-laedad.cpp
```
# Descripcion de los programas
### GonzalezIsaac-Compara.cpp
Este programa en C++ permite comparar dos numeros y determinar si son iguales, o si uno es mayor.
### GonzalezIsaac-CuentaMoneda.cpp
Este programa en C++ permite determinar la suma de varias monedas y de sus respectivas denominaciones.
### GonzalezIsaac-PuntoVenta.cpp
Este programa en C++ permite determinar el valor a pagar por la compra de varios productos tomando en cuenta el IVA y su respectivo descuento.
### GonzalezIsaac-SumaN.cpp
Este programa en C++ permite determinar la suma de varios numeros.
### GonzalezIsaac-laedad.cpp
Este programa en C++ permite calcular la edad de una persona.
# Funcionalidad
### GonzalezIsaac-Compara.cpp
```
float IS_x,IS_y;
```
#### Salida
```
si(IS_x==IS_y) //==> son iguales
si (IS_x<IS_y) //==> y es el mayor, caso contrario x es mayor
```
### GonzalezIsaac-CuentaMoneda.cpp
```
int IS_n,IS_c=0,IS_c1=0,IS_c2=0,IS_c3=0;
float IS_x,IS_a=0,IS_a1=0,IS_a2=0,IS_a3=0;
```
#### Salida
```
IS_c,IS_a,IS_c1,IS_a1,IS_c2,IS_a2,IS_c3,IS_a3 //==> Suma total de las monedas, suma de las monedas segun su denominacion por separado.
```
### GonzalezIsaac-PuntoVenta.cpp
```
int IS_C=0,IS_P;
float IS_A,IS_x,IS_vf,IS_IVA=0.12,IS_dsc,IS_Vb,IS_Vi,IS_Vd;
```
#### Salida
```
IS_Vb,IS_Vi,IS_Vd,IS_Vf //==> Valor final a pagar, valor bruto, IVA y descuento.
```
### GonzalezIsaac-SumaN.cpp
```
int IS_C=0,IS_B;
float IS_S,IS_x;
```
#### Salida
```
IS_S //==> La suma total de los numeros.
```
### GonzalezIsaac-laedad.cpp

```
int IS_dd,IS_mm,IS_yy,IS_dd1,IS_mm1,IS_yy1,IS_da,IS_ma,IS_ya;
```
#### Salida
```
IS_ya,IS_ma,IS_da //==> Su Edad.
```

# Instalación
1.- Descargar F-Droid.
```
https://f-droid.org/
```
2.- "Dentro de la aplicacion F-droid".
```
Descargar la termina (Termux) junto a todas sus actualizaciones
```
3.- Ingresar a la terminal(Termux) e instalar os paquetes de datos necesarios.
```
//==> pkg install git
//==> pkg install vim
//==> pkg install clang
//==> apt update
//==> apt upgrade
...
```

### Descargar el repositorio a la terminal(Termux)
1.- Clonar el repositorio en la maquina local.
```
git clone http://github.com/isaac2141/ACTIVIDAD-E2.git
```
2.- Ingresar al repositorio.
```
cd ~
cd ACTIVIDAD-E2
```
### Compilar y ejecutar
```
g++ GonzalezIsaac-SumaN.cpp -o GonzalezIsaac-SumaN
//==> Asi sucesivamente con los demas programas.
```
```
./GonzalezIsaac-SumaN
//==> Asi sucesivamente con los demas programas.
```




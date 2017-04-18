# USO DE LA CLASE SCANNER EN JAVA
![](https://lh3.googleusercontent.com/dsmDXAYUq3FvJknYp3JEm3hDcdxq3I6bzB29SDR2JE2eKwsVr3EOAiLn9XuAQ11QaDlyWS9lPi0OU_Regixl8luFHiX5o2YRKixTp_eubrXjv3fT7cnV22FMxtJ1Rrd0FYHIVvbil--YDt8h0DtD7G8sKeD7nEozP3Q6nlHHBG-8LpWW4UrADu0P8C2TF8WlAnLKC0DjVblAQpmfhrN-JBAsSz6Y7YdGqgdH-Js1aE_xgu7KmWxYaQsm56VPFlnUnHcWJfxp2t4rNTTZEqxdbwefC1TUig4wFL_blMiiIyVK3o5IGQ-NmKNiZqBjc0kaSzTLbsYrnbnFIHDHw2N0JP0Q-4q5qVH8p_AQ0sWGr6mILb4jAY2XKtCG70_ET3WyHsZsDddLPrBFnH2T5gBdsSaSmf8r7wb7diQduGNN2tfGSJHF4jJ_5cRnPd82nfv2yxDfJPF6xtjxqaOsWo0zfm8Sw0AQzhRU3_slAGrzRmJug1TLHWqoolf1jJcAqJ8cv8qmrsRUT_Zpa_xlfK0jRgy4BjpsdgjcwneD1WYD0qDfqjgIzTCoVkmgAWrsC8Gu0UVtAs6Gi4UMSCAwdrHjNXnrw8-0wS96YL2d0Rdz696oi4pN16lQ=w475-h287-no)
## USO DE LA CLASE SCANNER
La clase Scanner de Java provee métodos para leer valores de entrada de varios tipos y está localizada en el paquete java.util. Los valores de entrada pueden venir de varias fuentes, incluyendo valores que se entren por el teclado o datos almacenados en un archivo.
## 1. Escribir el import
### ****** import java.util.Scanner; ******
Para utilizar esa clase tenemos que crear primero un objeto de ella para poder invocar sus métodos. La siguiente declaración crea un objeto de la clase Scanner que lee valores de entrada del teclado.
### ****** Scanner teclado = new Scanner(System.in); ******
El propósito de pasar a System.in como argumento es conectar o establecer una relación entre el objeto tipo Scanner, con nombre teclado en la declaración anterior, y el objeto System.in, que representa el sistema estándar de entrada de información en Java. Si no se indica lo contrario, el teclado es, por omisión, el sistema estándar de entrada de información en Java.
Luego que se tenga un objeto de la clase Scanner asociado al sistema estándar de entrada System.in, llamamos, por ejemplo, su método nextInt para entrar un valor del tipo int. Para entrar otros valores de otros tipos de datos primitivos, se usan los métodos correspondientes como nextByte o nextDouble.
![](https://lh3.googleusercontent.com/UdLhD9f2teZ628LmPvnb4H5OQm39miaQpPIdIwZMmUZ8yTLROHB9ZqNJcodui9tilrehpnGuGed66bZIX7hTK-yDmSKJxMcvlXATO-dvTHAS8HULQIE_cwMFNDr8-VSJtyvl-uiqSagiHuIdC3YVFF-Wy3u1Btg6goMJjJcHEi_Xlfj_0ZgMH0Uy3Go-rtGKmrzLGC4Tyz6xjzFA-Xl92Tr7TXyU_yO32HBIvrOtGeZgm6lZ6oZyaR1j7LIZWwpPUFipRsnPiMD1y9G6a7ibgyLIaoQ2frYi9dhuti6Nj2jDrrhKpw2UDPw87bZv0FTFusWa_LT_3_UzXMk28jqOZBdm4qRle_mPW0zeAsnB-xRnbZ6lXOUMHFUfX5TUF4OOFAgw2N5Xu5JygaBtxnKfiAxvuhwQcPjpZujEsMcpzqu1omi15v2Iti-wD3AaSsLjjI0L8wprsuPB9v-Ua7g6uXMbqonwIfb9UR-JnoT_d_tg0dmvCC-u2GPA5h2kTrZyUXEED1Fy2NIJxQO9yCDvlcQMGBN6BmQUfWeA9MTLUX4rUTWfA4NSV7-79ZiGhfT8oyskZEGXOpiZamzpjkfKCvZ7GKHww4ZWxk8LmP1puWU4Qkc8VIXN=w688-h244-no)
## EJEMPLO DE LECTURA
### Metodo nextInt:
Da lectura por teclado de un número entero.
### int n;
### System.out.print("Introduzca un número entero: ");
### n = sc.nextInt();
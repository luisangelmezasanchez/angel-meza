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
## Método y ejemplo de la clase Scanner
![](https://lh3.googleusercontent.com/UdLhD9f2teZ628LmPvnb4H5OQm39miaQpPIdIwZMmUZ8yTLROHB9ZqNJcodui9tilrehpnGuGed66bZIX7hTK-yDmSKJxMcvlXATO-dvTHAS8HULQIE_cwMFNDr8-VSJtyvl-uiqSagiHuIdC3YVFF-Wy3u1Btg6goMJjJcHEi_Xlfj_0ZgMH0Uy3Go-rtGKmrzLGC4Tyz6xjzFA-Xl92Tr7TXyU_yO32HBIvrOtGeZgm6lZ6oZyaR1j7LIZWwpPUFipRsnPiMD1y9G6a7ibgyLIaoQ2frYi9dhuti6Nj2jDrrhKpw2UDPw87bZv0FTFusWa_LT_3_UzXMk28jqOZBdm4qRle_mPW0zeAsnB-xRnbZ6lXOUMHFUfX5TUF4OOFAgw2N5Xu5JygaBtxnKfiAxvuhwQcPjpZujEsMcpzqu1omi15v2Iti-wD3AaSsLjjI0L8wprsuPB9v-Ua7g6uXMbqonwIfb9UR-JnoT_d_tg0dmvCC-u2GPA5h2kTrZyUXEED1Fy2NIJxQO9yCDvlcQMGBN6BmQUfWeA9MTLUX4rUTWfA4NSV7-79ZiGhfT8oyskZEGXOpiZamzpjkfKCvZ7GKHww4ZWxk8LmP1puWU4Qkc8VIXN=w688-h244-no)
# EJEMPLO DE LECTURA DE ALGUNOS MÉTODOS
## Método nextInt: Da lectura por teclado de un número entero.
###  int n;
### System.out.print("Introduzca un número entero: ");
### n = sc.nextInt();
## Método nextDouble: Da lectura de un número de tipo double:
### double x;
### System.out.print("Introduzca número de tipo double: ");
### x = sc.nextDouble();
## Método next: Da lectura de una cadena
### String s;
### System.out.print("Introduzca texto: ");
### s = sc.next();
## CÓDIGO JAVA: UTILIZANDO LA CLASE SCANNER CON EL MÉTODO ENTERO.
### * Programa Ejemplo de Java: Calcular el producto de dos números.
![](https://lh3.googleusercontent.com/Q6sPLKzpGljBqzwcx0_TEiVVkYaAcmOwmJB9zFdGj_cmz_LjeNfTVShwonuoqs3Ln9e49KXAlIPm82xqip2_g0k0jX0qIzNcdcMkHe_Bs7Nl8DlwAEf1bW99V9_bYKM1xpvbXwtshNWkVPds6xKeEjxvrdSy2V5FDK5yGwOE3m-8OJtUotFRPsiZt0697jNILaPZusKpQlvVFJDT43FmeYn3o6tmbfskPD31QQ6gWnD68ffFNcAQcgKngH0cHnbJlFgm99FWZs0zkzhn7LRdkTqhU9Zp7at8U687t3h1JjpaRBrlbLkqLDBw90m6FITusRFY296XzkbradcNAye6w9vwloaskeYwKPI7unC8BI9PNSO-HCMeo9U1MMYJM-khrZ6kvKwGsCNPPSUMj-RCaDA_xv8B9WOqm17fjkJ12nWedjfmPS1-1ApkXAiw-nTlLUojYkpidCTtbFwdEDXfnUTPHe_UxiWgzrLf5ekNu2uNxRoOkDLoeAqF_c1a5AxcRx21DNGJGUIOuZLwtqct1X7OnlcfOKchPwEadLS1rVYg8QmX6S8XqxSc3NsqVnDEOhy2PqW8rI88OgBRppWoiQA-ZR7OH9BOEv6jmjm7xmG6wrRtt186=w635-h517-no)
## CÓDIGO JAVA: UTILIZANDO LA CLASE SCANNER CON EL MÉTODO DOUBLE
### * Programa Ejemplo de Java: Calcula y muestra el perímetro y área de un rectángulo, dados la longitud y anchura del rectángulo.
![](https://lh3.googleusercontent.com/pyNz9qPfwUSOaOuXxAvP9Ry4oqlDKW6lINjS_wXq7gY7F51FQD3xz0OlAfU5IKCG5la85zjCdDwuGNmnrTNFs0rDJoSxrLoUClNhJbdo-gTRXY08IEAEMkBOmuPVuzHMePAeIyZzfOo_Iw3SzPWRxGo2rTDLK6CftsvIcwAt4IUNBiGD6eGWQ06iuMyJ6a-xoIu6HytNiV391fqVt_Z0CwSS_7Sgm6L1KzBA6-odG1aWZ59pVxdFB4x8_3xjn9vKSZAn4X28Mb9yL6nOe8t0x5Hcxn15zZTKSByWBGYWL4o-1h9k8no9Wgc4mvfLquny0lFDNXqIe8YNR8cHoCBJXWUpQ1I_j_4eft27e0MXAwx1r0Mu3Qvt_TQr6VAiMH6dRXgnw_KXgSGVoDFKmZFGyZyC3hqH1b-2UnLHTljUFt0FQn-994SHWxtP74qqmTgg5HUBHeEidUQQOrHquT47t3St474jzONBsAubsQfWkb0CEZXT4lUbKTYo6UvqSKN-90TEXJLVEb2CJGGORunlEAE8WI1j1BCM8ytTh-yiSa3WrdmvXJXqL5IBEWOC3S_gRsEDfXmfrdZiI-JhhqH7-LRTd3QsbSGcLIgfJBvlJ_ARJkaO-KmB=w750-h585-no)
## CÓDIGO JAVA: UTILIZANDO LA CLASE SCANNER CON EL MÉTODO STRING.
### * Programa Ejemplo de Java: Hacer un programa el cual nos pregunte nuestro nombre y apellido.
![](https://lh3.googleusercontent.com/cuHlrlEtHZDk8yKinMbbsnbjVq5ok8omhGrmgJlMI0S35p7jnstkmTiu6GzEFMcjNA4VpOmwRHy76xgnKGZxyV2CSRVJ8SMFcYoCEpZjglX0fqCmb6vpwVuXy4okak0Jn9VWa5TaBK0eGcQ9C8F4CGWYyckVqZM3bte8TMAZ8karJFNf5iTY77KWEL3-180H7GjZShaHFsLPtsVZmes6EvgoF1ohYD0x9wFq8n7E_AaTEmFS7WH2OWk9yc8hBzoqJRlOuDHBgETN-lCETooSEdfimujKo_VvA4Aix5zHRZqEscCEQyVQgOg47fuUssZBtb50mrA10v39U8XefpRsbUIt26fs267SXgSYrZs2I6BbyZY3fBVfa90bMjiZr2AP2Nr62QjADR9WYJsEDOQ_qtsWmcRYVyvI9ctlLuggxlMEjeYb0RhZ4LyOY6cU3E-wBw35LUy9WEzNx4lA-IhK4v9g_-pUJbRn7f5xfLLHL5h5mDlMB6UpUv5TX2J-OKxmQUoDy4qli3WHXUa_Cx6ajQ4ZZaDBN5XIN7kSsUp8xHs_Aa5McnWVj4QaQ9GnNglZ_L7XmWffk320Kk5JAlzqkLWR1m9vIxLMSJlbr6QxsBI05WjyABcf=w625-h433-no)
# BIBLIOGRAFÍAS
## USO DE LA CLASE JAVA
### http://www.programacion-java.carimobits.com/Documentos%20en%20PDF/La_clase_estandar_Scanner_de_Java%20v%202Web.pdf

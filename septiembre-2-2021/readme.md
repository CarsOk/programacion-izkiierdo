| ***REPRESENTACION DE VARIABLES EN DISTINTOS ESCENARIOS*** |
| --------------------------------------------------------- |

 En la clase de hoy aprendi con el instructor henry las diferentes formas de representar el inicio y el fin de un programa y como mostrar texto en un sencillo programa.<br>  <br>  <br> **Formas de como se representa inicio y fin de un programa**<br>  
 ***.STARUML*** se crea un diagrama de flujo y se representa
```
  inicio y fin
  ```
 ***EXEL (VISUAL BASIC)*** se escribe
 ```
 sub ejemplo ()
End Sub"  
```

 **ejemplo:** (de inicio de programa usando la varriable **msgbox** )
  ```
 Sub bienvenido()

MsgBox "hola bienbenidos"

End Sub"   
```        

**tarea 3 mesages en MsgBox:**
```
Sub prueba()
MsgBox "pon a prueba tu conocimiento que tal si repasamos las tablas del 5"

  Dim pregunta As String

  pregunta = MsgBox("5x3 es 10", vbYesNo + vbQuestion, "tabla de 5")

   If pregunta = vbNo Then
   MsgBox "respuesta correcta 5x3=15"

   Else

    MsgBox "es incorrecto 5x3=15"

    End If

End Sub
```
![STARUML](1.jpg)

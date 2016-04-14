# Python

## Einführung
Python ist eine einfach anwendbare Programmiersprache, die viel mehr Struktur als andere Programmiersprachen wie z.B. C/Java bietet. Durch das Aufteilen von Programmen in Modulen, die in jedem Programm wiederverwendet werden können, wird Coderedundanz vermieden und erheblich Zeit bei der Programmentwicklung eingespart. Da es sich bei Python um eine Interpretersprache handelt entfällt das Kompilieren und das Linken. Ein weiterer Vorteil ist, dass Python dadurch erweiterbar ist und man eigene Module zum Interpreter hinzufügen kann. Auch spielt das Format der eingegebenen Anweisungen eine Rolle. Durch z.B. explizites einrücken von Befehlen in Schleifen oder Bedingungen, wird der Programmcode übersichtlicher und die aus C bekannten geschweiften Klammern entfallen.

## Befehle und Datentypen
In Python gibt es eine Menge von Befehlen, deren Syntax stark der von C ähnelt. Anders als in C jedoch muss der Datentyp einer Variable nicht angegeben werden.

**Zahlen**
Der Python Interpreter kann in seiner einfachsten Form als Taschenrechner genutzt werden, wobei die Arithmetischen Operatoren, wie in den meisten Programmiersprachen, durch "+","-","*" und "/" gegeben sind.
```python
 >>>3+3
6
>>>5/8 #Brüche gehen nicht verloren, '#' kennzeichnet einen Kommentar wie man sieht
0.625
 ```
 Zum Vergleich von Zahlen, dienen die normalen Vergleichsoperatoren, wie sie schon aus C bekannt sind ">","<" und "==", sowie deren Verknüpfung ">=","<=" und "!=" (ungleich). Wie in C gilt jede Zahl größer Null besitzt den Wert "True", Nulll ist "False".
 **Strings**
 Strings(Zeichenketten) können (genau wie in C) mit doppelten Anführungszeichen gekennzeichnet werden oder aber auch in einfachen Anführungszeichen.
 ```python
 >>>"Ein String wie in C"
'Ein String wie in C'
 >>> 'Oder auch nicht'
'Oder auch nicht'
 ```
**Variablen**
Variablen werden wie in C mit dem Zuweisungsoperator "=" initialisiert, jedoch entfällt die Variablendeklaration (-> Zeitsparend).
```python
>>>x=y=z=24 # Mehreren Variablen den gleichen Wert zuweisen
>>>x
24
>>>Länge=5
>>>Breite=4
>>>Fläche=Länge*Breite # Arithmetische Operationen auch auf Variablen anwendbar
>>>Fläche
20
```
Natürlich können Strings auch Variablen zugewiesen werden und mit dem "+" Operator konkateniert werden
```python
>>>string1="Ein String"
>>>string2=" wie in C"
>>>string3=string1 + string2
>>>string3
'Ein String wie in C'
```
Die Indizierung der Zeichenkette erfolgt genauso wie in C, also bei 0 beginnend.
Der Zugriff auf Abschnitte des Strings erfolgt mittels dem "[]"-Operator
```python
>>>string1="Ein String"
>>>string1[4]
S
>>>string1[:2] # Die ersten beiden Zeichen
Ei
```

**Zusammengesetzte Datentypen**
Zusätzlich zu den vorher vorgestellten elementaren Datentypen, gibt es in Python auch eine Reihe von zusammengesetzten Datentypen, die zur Gruppierung unterschiedlicher Werte genutzt werden können.

**Listen**
Die Liste stellt eine flexibele Möglichkeit dar, um Elemente unterschiedlichen Datentyps in einem Listenelement darzustellen.
```python
>>>liste1=["string",24,2+3]
>>>liste1
['string',24,5]
```
Die Listenindizierung, ist wie bei Strings nullbasiert, daher kann auf die einzelnen Elemente wieder mittels dem  "[]"-Operator zugegriffen werden.  

.... to be continued

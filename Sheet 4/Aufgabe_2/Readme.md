# 2 Plus Minus

Implementieren Sie eine Methode *analyseArray* welche als Parameter einen vector mit Integer
Werten bekommt. Diese Werte sind entweder Positiv, Negativ oder Null. Die Methode soll nun
berechnen, wie viel Prozent der Werte Positiv, Negativ resp. Null sind. Diese drei Werte werden als
*Objekt* der Klasse *Result* zurückgeliefert.

```cpp
class Result {
	public :
		int nPositive;
		int nZero;
		int nNegative;
};
```

```cpp
class ArrayUtil {
	public :
		static Result analyseArray(vector<int> input ) ;
};
```

**Beispiel:**

**Input:** 1, 10, 0, -6, -9, 2, 5

**Lösung:** [nPositive: 57.1%; nZero: 14.3%; nNegative: 28.6%]

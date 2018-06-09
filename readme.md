## NonoPy: Nonogram generator for Python
* Based on Python 3 + Pillow
* Includes [Apache Licensed product](http://www.apache.org/licenses/LICENSE-2.0) , Open Sans.

### Dependencies
* Pillow
* NumPy

### Example
```python
import nonogram

#input filename
n = nonogram.Nonogram('young2.jpg')
#width, height, threshold, output filename
n.convert(32, 32, 550, "young2")
```

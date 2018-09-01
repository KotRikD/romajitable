# RomajiTable

> RomajiTable - This is a util to convert english or maybe translited word to kata (Hiragana, Katakana)
> Lib for Python 3+

## Installing

```bash
pip install romajitable
```

Update

```bash
pip install --upgrade romajitable
```

## Example

```python
import romajitable

word = "My name is Mikhail"
result = romajitable.to_kana(word)

hiraganed = result.hiragana
# むゆ・なめ・いす・みくはいる

katakaned = result.katakana
# ムユ・ナメ・イス・ミクハイル

```
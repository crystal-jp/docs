# 3項演算子

`if`をより簡潔に書く方法として、3項演算子という構文があります。

```crystal
a = 1 > 2 ? 3 : 4

# 上記は以下と同じ
a = if 1 > 2
      3
    else
      4
    end
```
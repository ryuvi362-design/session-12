[Uploading README 12.md…]()
```python

add_gst = lambda price: price * 1.18

print(add_gst(100))
print(add_gst(250))
print(add_gst(500))
```

```python
songs = ['shape Of you', 'blinding LIGHTS', 'perfect', 'believer']

cleaned_songs = list(map(lambda song: song.strip().title(), songs))

print(cleaned_songs)
```

```python
products = ['Shoes', 'shirt', 'Laptop', 'Smartphone', 'Watch', 'speaker']

filtered_products = list(filter(lambda product: product.lower().startswith('s'), products))

print(filtered_products)
```

```python
orders = [120, 340, 560, 80]

total = reduce(lambda x, y: x + y, orders)

print(total)
```

```python
numbers = [40, 60, 80, 120]

doubled = map(lambda x: x * 2, numbers)
filtered = filter(lambda x: x > 100, doubled)
total = reduce(lambda x, y: x + y, filtered)

print(total)
```

# Exercise 6

### sorting

### sort words by alphabet with `:sort`

talk
backpack
act
bail
camel
yellow
bandage
camper
kazoo
tanker
zoom
key
day
nail
kiwi
adage
nasturium
cabin
nebula
baboon
tea
dart
actor
yoka

### sort numbers, by typing `:sort n` 

1
2
3
4
5
6
7
8
10

### you can increment and decrement numbers by pressing <C-a> and <C-x>

10

```
const number = 20;
```

### another cool thing is you can indent line by pressing ==

```javascript
const sum = (a, b) => {
	return a + b;
}
```

### we can add remap in ~/.vimrc file to indent whole file

### for this we will need to go to the first line (gg) then press = once
### and then go to the last line by pressing G, after that we can return our cursor where it was by pressing <C-o>
### so our remap should look something like this gg=G2<C-o>

### you can also indent line by pressing <<

```javascript
const someFunction = () => {
console.log("Hello");
    console.log("World");
}
```

### you can repeat last thing you did by pressing .
### lets say you have to change function name, you can do cw, to delete word and put yourself in insert mode
### and then rename function.

```javascript
const subtract(a, b) => {
  return a + b;
}

subtract(10, 20);
```

### there is another way to change function name in vim.

```javascript
const subtract(a, b) => {
  return a + b;
}

subtract(10, 20);
```

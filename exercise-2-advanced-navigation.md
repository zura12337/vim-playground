# Exercise 2: Advanced Navigation


### use gg to go to the first line, use G to go to the last line

### Use relative numbers to go to the line that contains o and replace it with + by pressing $ and s

+------+
+----------+
+---+
+-------------+
+--------+

### jump paragraphs by pressing } and {

+--+
+------+
+----+
+------+

+-----------+
+----+
+-------+

Remove
this
paragraph
by pressing
dip (Delete into paragraph)

+-----------+
+---------+
+----------+
+----+
+-----------+

### lets jump between braces opening and closing tags, by pressing %

### write right function content and remove current one, you can press ci{ 
### to remove all content of function and put yourself in insert mode

```javascript
function sum (a, b) {
  return a + b;
}
```

### you can find symbol by pressing f and letter you want to find on the line you are currently on.

### lets find o by pressing fo and replace it with + by pressing s

+---+ +------+ +--o +--+ +-----+ +----+ +--+ +----o

### t is like f, but it moves cursor with one letter before

### remove whole line but leave only ;, by pressing dt;

```javascript
function sum = (a, b) => return a + b;
```

### lets finish this function by pressing o and typing return a + b;

```javascript
const sum = (a, b) => {
}
```

### lets press zz to center buffer

### search for 0 by pressing /0
### and in command mode type `:set hls` to highlight all searched text
### to remove highlight from all searched text, in command mode type `:set nohlsearch`

01111111100000000111111111111000000000000000
00111111000000000001111111100000000000000000
00111111000000000011111111000000000000000000
00111111000000000111111110000000000000000000
00111111000000001111111000000000000000000000
00111111000000011111110000000000000000000000
00111111000000111111100000000000000000000000
00111111000001111111000111000111000000000000
00111111000011111110001110001111111111111110
00111111000111111100000000011110011100111100
00111111111111110000111000111100111001111000
00011111111111000001110001111000000011110000
00001111111100000011100011110000000111100000

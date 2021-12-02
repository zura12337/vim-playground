# Exercise 1: delete, yank, paste and change

## Delete a line with dd

delete me delete me delete me delete me (dd)

## Yank a line with yy, p to paste it below, P above

yank me and paste below (yyp)

yank me and paste above (yyP)
## visual mode

### visual mode

highlight part of this line by pressing v, then navigate around escape to leave visual mode

### visual line mode

highlight this line by pressing v, then navigate around escape to leave visual mode

### visual mode + yank and paste

Highlight this line by pressing V, then press y press p 

Highlight ---this point--- by pressing v, press y (What happened?) press p (What happened?)
---this point---

Highlight this line by pressing V, then press d

### visual block mode

// highlight slashes by pressing <c-v> and
// remove
// slashes
// from
// all
// lines

# registers

type `:reg` in command mode

access registers in normal mode by "{name}p
                 in instert mode by <C-r>{name}



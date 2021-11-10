# Doglang 🐶

**The Cutest Esolang With Doggies**

Doglang is to BF what Typescript is to Javascript (in the future),

while for now it's just the same as BF (but cuter).

(BF means brainfuck btw)

## Dogs

Here let me introduce some cute dogs to you:

🐕 - Dog

🦮 - Guide Dog

🐶 - Dog Face

🐩 - Poodle

And they play important roles in `Doglang` :

| Instruction |  Function    |  In BF  |  In C  |
| ---- | ---- | ---- | ---- |
| "🐕"   | Move the pointer to the right | < | `p++;` |
| "🐕 "   | Move the pointer to the left | > | `p--;`|
| "🦮"   | Increment the memory cell at the pointer | + |   `*p++;` |
| "🦮 "   | Decrement the memory cell at the pointer | - |  `*p--;` |
| "🐶"   | Output the character signified by the cell at the pointer | . |  `putchar(*p);` |
| "🐶 "   | Input a character and store it in the cell at the pointer | , |    `*p=getchar();` |
| "🐩"   | Jump past the matching `🐩 ` if the cell at the pointer is 0 | [ |  `while(*p){` |
| "🐩 "   | Jump back to the matching `🐩` if the cell at the pointer is nonzero | ] |   `}` |



## Hello World

```Doglang
🦮🐩🦮 🦮 🐕 🦮 🐩🐕 🐕 🦮🐕 🦮 🦮 🦮 🦮 🦮 🐕🐕🐩 🐕🦮 🦮 🐕🦮 🦮 🦮 🐩 🐕 🦮 🐶🐕 🐕 🐕 🦮🐶🐕 🐕 🐶🐶🦮🦮🦮🐩🐶🐕 🐩 🐕🐕🐕🐕🐶🦮🦮🦮🐶🦮 🦮 🦮 🦮 🦮 🦮 🐶🐕🐕🦮 🐶🐕 🐕 🐕 🐕 🦮🐶
```


## Todo
- [ ] Might abandon ' '(blankspace)
- [ ] Add more dogs like 
  - 🐕‍🦺 Service Dog
  - 🐺 Wolf
- [ ] Make it less brainfuck (also we can say, more than brainfuck)
- [ ] Its own compiler

- [x] Compile Doglang to BF
  - [ ] cli version

## Similar

[Esolang](https://esolangs.org/wiki/Main_Page) - Esoteric programming languages

[Brainfuck](https://esolangs.org/wiki/Brainfuck) - One of the most famous esoteric programming languages
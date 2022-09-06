# Sardar Iskandarov

---

### Contact information
- **@sardarz** - telegram
- **sardar8go@gmail.com** - email
- **+79650900688** - mobile

---

### About myself
I finished my bachelor's degree at ITMO university and now I'm looking forward to become a front-end developer. I have already tried to learn programing several times but failed because of my lack of patience and making the mistake of setting very high expectations of myself. Now I just enjoy coding and love to solve different code challenges on codewars and create websites from challenges on frontendmentor. To me, the field of front-end is vast and I want to become a great programmer who is able to create complex apps. In the future after learning React and Typescript I want to learn a staticly typed language and maybe try out ML. I have become really curious about programming and I want to learn as much as possible from any resource I can get my hands on

---

### Skills
- HTML, CSS
- JavaScript
- Git, GitHub
- React beginner

---

### Code example 
Solution from codewars.com "Sudoku solution validator"
```
function validSolution(board){
  if (board.some(x => x.includes(0))) return false
  
  for (let i = 0; i < board.length; i++) {
    let set = new Set()
    for (let j = 0; j < board.length; j++) {
      set.add(board[i][j])
    }
    if (set.size !== 9) return false;
  }
  
  for (let i = 0; i < board.length; i++) {
    let set = new Set()
    for (let j = 0; j < board.length; j++) {
      set.add(board[j][i])
    }
    if (set.size !== 9) return false;
  }
  
  for (let i = 0; i < board.length; i++) {
    let set = new Set()
    for (let j = 0; j < board.length; j++) {
      set.add(board[Math.floor(i / 3) * 3 + Math.floor(j / 3)][(i * 3 + j % 3) % 9])
    }
    if (set.size !== 9) return false;
  }
  return true
}
```

---

### Skills
- HTML, CSS
- JavaScript
- Git, GitHub
- React beginner

---

### Code example 
Solution from codewars.com "Sudoku solution validator"
```
function validSolution(board){
  if (board.some(x => x.includes(0))) return false
  
  for (let i = 0; i < board.length; i++) {
    let set = new Set()
    for (let j = 0; j < board.length; j++) {
      set.add(board[i][j])
    }
    if (set.size !== 9) return false;
  }
  
  for (let i = 0; i < board.length; i++) {
    let set = new Set()
    for (let j = 0; j < board.length; j++) {
      set.add(board[j][i])
    }
    if (set.size !== 9) return false;
  }
  
  for (let i = 0; i < board.length; i++) {
    let set = new Set()
    for (let j = 0; j < board.length; j++) {
      set.add(board[Math.floor(i / 3) * 3 + Math.floor(j / 3)][(i * 3 + j % 3) % 9])
    }
    if (set.size !== 9) return false;
  }
  return true
}
```

---

### Working experience
I do not have a real work experience, but I practice a lot by doing the challenges on frontendmentor.com. [completed challenges](https://sardarz.netlify.app/)

---

### English proficiency
I posess an 8 band IELTS certificate, which makes me a C1 speaker
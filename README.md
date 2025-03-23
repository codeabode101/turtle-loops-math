# 7-Day Shape Evolution Challenge 🌀

**Google Anything You Don't Understand!**
Avoid asking for help until you've tried Googling a couple of times and clicked and read through a few articles.

### Day 1: Rectangle Roots 🔳  
**Math Warm-Up:**  
`(15.5 × 2) + 7.25 = ?`  

**Turtle Mission:**  
- Draw a rectangle with sides `100.5` and `50.25`  
- Use a **while loop** (Google it!) with a counter  
- After each side, print:  
  `"Side [counter] done! 🟦"`  

**Comment Quest:**  
Add a comment explaining why rectangles need *two* different lengths.  

**Debug Dungeon:**  
```python
# Fix the infinite loop! 🚨
counter = 1
while counter < 4
    t.forward(100)
    t.right(90)
```
Hint: Google "infinite loops"

---

### Day 2: Triangle Trouble 🔺  
**Math Warm-Up:**  
`(25.0 ÷ 2) + 3.3 = ?`  

**Turtle Mission:**  Draw an equilateral triangle with sides `75.75`  Use a **while loop** that stops after 3 sides  Print after each turn:  `"Turned [angle]°! 🔄"`  **Comment Quest:**  Explain why the angles must total 360° (use a comment!).  Google it if you don't understand yourself.
**Debug Dungeon:**  
```python
# Why does this make a line? 🚨
sides = 0
while sides < 3:
    t.forward(75.75)
    sides += 1
```

---

### Day 3: Pentagon Portal ⬟  
**Math Warm-Up:**  
`(12.5 × 4) - 10.0 = ?`  

**Turtle Mission:**  
- Draw a pentagon with sides `55.5`  
- **New tool:** Use `while counter < 5`  
- After drawing, print:  
  `"Portal has [counter] sides! ✨"`  

**Comment Quest:**  
Add a comment guessing what happens if you use 144° turns.  

**Debug Dungeon:**  
```python
# Portal won't close! 🚨
angle = 72
sides = 0
while sides < 5
    t.forward(55.5)
    t.left(angle)
```

---

### Day 4: House Builder 🏠  
**Math Warm-Up:**  
`(60.25 + 35.75) ÷ 2 = ?`  

**Turtle Mission:**  
- Build a house:  
  - **Base:** Rectangle (your Day 1 code)  
  - **Roof:** Triangle (Day 2)  
- Print when each part is done:  
  `"Roof complete! 🏡"`  

**Comment Quest:**  
Comment where the turtle should start drawing the roof.  

**Debug Dungeon:**  
```python
# Roof floats in space! 🚨
# (Student must fix positioning)
t.forward(100.5)
t.left(90)
# Missing code here!
draw_triangle_roof()
```

`draw_triangle_roof()` is a function. You can choose to Google how to make your own functions, or just put your code there instead. It doesn't matter.

---

### Day 5: Starry Night 🌟  
**Math Warm-Up:**  
`(180 ÷ 5) × 2 = ?`  

**Turtle Mission:**  
- Draw a 5-point star with sides `40.4`  
- **Hint:** Use a loop with *sharp* turns  
- Print at each point:  
  `"Star point [number]! 🌟"`  

**Comment Quest:**  
Explain why the turns can’t be 90° (use math!).  

**Debug Dungeon:**  
```python
# Star looks broken! 🚨
points = 0
while points < 5:
    t.forward(40.4)
    t.left(144)  # Is this right?
```

---

### Day 6: Shape Monster 👾  
**Turtle Mission:**  
- Create a monster using:  
  - 1 rectangle (body)  
  - 2 circles (eyes)  
  - 1 triangle (mouth)  
- Use **while loops** for ALL shapes  
- Print when each part is added:  
  `"Added [body part]! 👁️"`  

**Debug Dungeon:**  
```python
# Eyes don't show! 🚨
# (Student must fix circle code)
t.forward(50)
while count < 2:
    draw_eye()
```

---

### Day 7: Final Project: Alien Spaceship 🛸  
**Requirements:**  
- Combine:  
  - Pentagon (cockpit)  
  - Rectangles (engines)  
  - Triangles (wings)  
- Use **while loops** everywhere  
- Print progress for each part:  
  `"Wing [number] attached! 🚀"`  
- Add **5+ comments** explaining design choices  

**Debug Dungeon:**  
```python
# Teacher's Broken Spaceship 🚨
# Fix 5 errors:
counter = 1
whle counter < 4
    t.forward(100.5
    t.right(90)
    print(f"Engine {counter} done!")
```

### **Month 1: Go Fundamentals**
| Week | Topics | Hands-on Project | Status |
|------|--------|------------------|--------|
| 1 | Go Setup, Syntax, Types, Variables, Control Flow | CLI Calculator (`+`, `-`, `*`, `/`) | [ ] |

#### Week 1 Detailed Breakdown

**Day 1-2: Go Setup & Environment**
- **Sub-topics:**
  - Installing Go on your system
  - Understanding GOPATH vs Go Modules (modern approach)
  - Setting up your IDE/editor (VS Code with Go extension recommended)
  - Hello World program
  - Go command line tools (`go run`, `go build`, `go fmt`)
  - Code organization (packages, files, naming conventions)

- **Exercises:**
  1. Install Go and verify with `go version`
  2. Create and run a "Hello, World!" program
  3. Build a standalone executable and run it
  4. Experiment with `go fmt` to auto-format your code
  5. Create a multi-file program with a main package

**Day 3: Go Syntax & Basic Types**
- **Sub-topics:**
  - Go's syntax vs Python (semicolons, braces, etc.)
  - Variable declaration (`var`, `:=` short declaration)
  - Basic types (int, float64, string, bool)
  - Type conversion (explicit vs Python's implicit)
  - Constants and iota
  - Zero values (vs Python's None)
  - String manipulation in Go

- **Exercises:**
  1. Create variables using both `var` and `:=` syntax
  2. Demonstrate type conversion between numbers
  3. Create a program that shows zero values for each basic type
  4. Define constants using iota for days of the week
  5. Build a string formatting example showing Go's approach

**Day 4: Control Flow in Go**
- **Sub-topics:**
  - If statements and initialization syntax
  - For loops (3 forms: C-style, while-style, infinite)
  - Switch statements (with fallthrough differences)
  - Deferred execution with `defer`
  - Early returns vs Python's style

- **Exercises:**
  1. Write an if statement with initialization
  2. Create a program using all three forms of for loops
  3. Build a switch statement with multiple cases
  4. Use `defer` to demonstrate execution order
  5. Create a function with multiple return points

**Day 5: CLI Calculator Project**
- **Sub-topics:**
  - Command line arguments with `os.Args`
  - Converting strings to numbers
  - Error handling basics
  - Program organization
  - Edge case handling

- **Project Steps:**
  1. Create a CLI calculator that accepts input like: `./calc 5 + 3`
  2. Support addition, subtraction, multiplication, and division
  3. Handle errors like invalid operations or non-numeric inputs
  4. Add support for floating-point calculations
  5. **Bonus:** Implement parentheses for order of operations

**Example Usage:**
```
$ ./calc 5 + 3
8
$ ./calc 10 / 2
5
$ ./calc 2.5 * 3
7.5
$ ./calc 10 % 3  # Bonus: modulo operation
1
```


## 📝 Weekly Learning Template

For each week, consider documenting your progress using this template:

```markdown
## Week X: [Topic]

### Concepts Learned
- Concept 1
- Concept 2
- Concept 3

### Project Progress
- [x] Requirement 1 implemented
- [ ] Requirement 2 in progress
- [ ] Requirement 3 planned

### Code Snippet of the Week
```go
// Add your favorite code snippet here
func example() {
    fmt.Println("Learning Go!")
}
```

### Challenges & Solutions
- Challenge: [Describe a problem you encountered]
- Solution: [How you solved it]

### Resources Used
- [Link to helpful resource]
- [Another helpful resource]

### Next Week's Focus
- What to learn next
- Project next steps
```

---

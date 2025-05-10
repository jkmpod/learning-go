# 🧠 Go Learning Curriculum – 5 Month Plan (5 hrs/week)

This is a structured learning plan to master the Go programming language in 5 months, with a focus on building tangible, hands-on projects while accommodating prior Python experience but limited familiarity with interfaces and concurrency.

---

## ✅ Progress Checklist

### **Month 1: Go Fundamentals**
| Week | Topics | Hands-on Project | Status |
|------|--------|------------------|--------|
| 1 | Go Setup, Syntax, Types, Variables, Control Flow | CLI Calculator (`+`, `-`, `*`, `/`) | [ ] |
| 2 | Functions, Basic Error Handling, Packages | Temperature Converter CLI Tool + Error Cases | [ ] |
| 3 | Structs, Methods, Pointers | Simple Address Book CLI (Create/Read contacts) | [ ] |
| 4 | Arrays, Slices, Maps, Loops | Word Frequency Counter + Basic Tests | [ ] |

**End of Month 1 Reflection**: Review your projects, identify patterns in Go syntax that differ from Python, and document your learnings about Go's type system.

---

### **Month 2: Go Data Handling & Error Management**
| Week | Topics | Hands-on Project | Status |
|------|--------|------------------|--------|
| 5 | Introduction to Interfaces (Concepts) | Geometry Library (Calculate area/perimeter) | [ ] |
| 6 | Interfaces in Practice, Type Assertion | Shape Interface + Multiple Implementations | [ ] |
| 7 | File I/O, Error Propagation Patterns | File-based Key-Value Store with Error Handling | [ ] |
| 8 | JSON Parsing, Go Testing Basics | Task Manager CLI with JSON persistence + Tests | [ ] |

**End of Month 2 Reflection**: Compare Go's interface approach to Python's duck typing, analyze the error handling patterns you've implemented so far.

---

### **Month 3: Error Management & Testing**
| Week | Topics | Hands-on Project | Status |
|------|--------|------------------|--------|
| 9 | Advanced Error Handling, Error Wrapping | Enhance Task Manager with Better Errors | [ ] |
| 10 | Table-driven Tests, Mocking | Add Comprehensive Tests to Task Manager | [ ] |
| 11 | Modules, Dependency Management | Refactor Task Manager Using Proper Modules | [ ] |
| 12 | Mid-Project Review | Enhance Task Manager with Search/Filter Features | [ ] |

**End of Month 3 Reflection**: Evaluate how Go's strict typing and error handling have improved your code quality compared to Python practices.

---

### **Month 4: Introduction to Concurrency & Web**
| Week | Topics | Hands-on Project | Status |
|------|--------|------------------|--------|
| 13 | Concurrency Concepts (Theory) | Research Paper on Go Concurrency Models | [ ] |
| 14 | Goroutines, Basic Channels | Simple Parallel Counter | [ ] |
| 15 | `net/http`, Basic Server | "Hello Go" Web Server with Routes | [ ] |
| 16 | RESTful APIs, JSON Marshalling | Notes API (GET, POST) with Error Handling | [ ] |

**End of Month 4 Reflection**: Document your understanding of Go's concurrency model compared to traditional threading, and how the language facilitates web development.

---

### **Month 5: Advanced Concepts & Real-World Application**
| Week | Topics | Hands-on Project | Status |
|------|--------|------------------|--------|
| 17 | Select, Buffered Channels, Timeouts | Concurrent File Processor | [ ] |
| 18 | API Development with 3rd-party libs | Refactor Notes API with Gorilla Mux | [ ] |
| 19 | `go build`, Docker Basics | Dockerize Your API | [ ] |
| 20 | Capstone Project | Integrate Learning: Concurrent Web Service with Tests | [ ] |

**End of Month 5 Reflection**: Complete self-assessment comparing your Go knowledge to your Python experience, identifying strengths and areas for future growth.

---

## 🛠 Tools & Resources

- [Go Tour](https://tour.golang.org/) - Interactive introduction to Go
- [Go by Example](https://gobyexample.com/) - Hands-on introduction to Go with annotated examples
- [Go.dev](https://go.dev/) - Official Go website with documentation and resources
- [Effective Go](https://go.dev/doc/effective_go) - Tips for writing clear, idiomatic Go code
- [Go Playground](https://play.golang.org/) - Write and share Go code online without installation

### Additional Resources

- [Learn Go with Tests](https://quii.gitbook.io/learn-go-with-tests/) - Learning Go through test-driven development
- [Go Concurrency Patterns](https://go.dev/blog/pipelines) - Official Go blog post on concurrency patterns
- [The Go Programming Language (book)](https://www.gopl.io/) - Comprehensive book by Alan A. A. Donovan and Brian W. Kernighan

---

## 🚀 Capstone Project Ideas

Choose one of these projects to demonstrate your Go proficiency:

1. **Task Management API**
   - REST API with persistence
   - Concurrent task processing
   - Authentication & authorization
   - Comprehensive test suite

2. **File Processing Service**
   - Concurrent file processor
   - Support for various file formats
   - Progress tracking and reporting
   - Dockerized deployment

3. **Simple Message Queue**
   - Producer/consumer architecture
   - Concurrent message handling
   - REST API interface
   - Persistence and recovery

---

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

> ✅ **Tip**: Commit your code daily, even if incomplete. Review your code regularly to identify patterns and improvements. Don't be afraid to refactor as you learn new concepts.
# Go Study Case

Tracking my progress while learning Go (Golang).

## Progress

### Completed

- [x] **Hello World** — Basic `main` package using an external module (`rsc.io/quote`) → `hello/`
- [x] **Greetings module** — Created a reusable local module with a public `Hello` function → `greetings/`
- [x] **Calling a local module** — Consumed the `greetings` module from another program → `hello-with-greetings/`
- [x] **Error handling** — Return and handle errors in the `greetings` module
- [x] **Random greetings** — Return a random greeting from a predefined list
- [x] **Greet multiple people** — Accept and greet a slice of names


### Up Next

- [ ] **Unit tests** — Write tests for the `greetings` package
- [ ] **Compile & install** — Build and install a Go binary

## Concepts Covered So Far

| Concept | Where |
|---|---|
| Packages & `main` | `hello/`, `hello-with-greetings/` |
| Modules & `go.mod` | `hello/go.mod`, `greetings/go.mod` |
| Exported functions | `greetings/greetings.go` |
| `fmt.Sprintf` / `fmt.Println` | `greetings/`, `hello-with-greetings/` |
| Using external modules | `hello/` (`rsc.io/quote`) |
| Using local modules | `hello-with-greetings/` |

## How to Run

```bash
# Hello World
cd hello && go run .

# Hello with Greetings
cd hello-with-greetings && go run .
```

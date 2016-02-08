---
title: FizzBuzz Code Examples
---


### Ruby

```ruby
(1..100).each do |n|
  puts if (n % 15).zero?
    "FizzBuzz"
  elsif (n % 5).zero?
    "Buzz"
  elsif (n % 3).zero?
    "Fizz"
  else
    n
  end
end
```

### Go

```go
package main
 
import "fmt"
 
func main() {
    for i := 1; i <= 100; i++ {
        switch {
        case i%15==0:
            fmt.Println("FizzBuzz")
        case i%3==0:
            fmt.Println("Fizz")
        case i%5==0:
            fmt.Println("Buzz")
        default: 
            fmt.Println(i)
        }
    }
}
```



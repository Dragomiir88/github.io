package main
 
import "fmt"
 
type Number struct {
  value int
}
 
func (n *Number) sum(a, b int) int {
  return a + b
}
 
// Функция clone создает копию Number. 
func (n *Number) clone() *Number { 
  return &Number{value: n.value} 
} 
 
func main() { 
  number1 := Number{value: 5} 
  number2 := Number{value: 10} 

  sum := number1.sum(number2.value, number1.value) 
  clone := number1.clone() 

 fmt.Println("Сумма:", sum) 
 fmt.Printf("Копия: %v\n", *clone) 
}

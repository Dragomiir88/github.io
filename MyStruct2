package main
import (
"fmt"
)
type MyStruct struct {
id int
name string
Value int
}
func (ms MyStruct) Name() string {
return ms.name
}
func (ms MyStruct) Id() int {
return ms.id
}
func (ms *MyStruct) ChangeValue(newValue int) {
ms.Value = newValue
}
func NewMyStruct(name string, id int) MyStruct {
return MyStruct{
id: id,
name: name,
}
}
func main() {
myStruct := NewMyStruct("Иван Петров", 123)
fmt.Println("Name:", myStruct.Name())
fmt.Println("Id:", myStruct.Id())
myStruct.ChangeValue(1990)
fmt.Println("New Value:", myStruct.Value)
}


## Scopes
Scopes are defined by open and closed curly brackets. A scope is started on a '{' and dropped on a '}'. All data within a scope is dropped when it ends, unless<br/>
  1. a call is immediately followed by an arrow ("=>"), in which case the variable will be carried to the next line. i.e. <br/>
  `fn add(int num1, int num2)
  {
   number = num1+num2
  }
  fn main(str text){
  add(1, 2) =>
}
  `

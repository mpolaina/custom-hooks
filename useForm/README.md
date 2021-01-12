# useForm Hook

Ejemplo de uso:
```js
const initialForm = {
  name: '',
  age: 0
  email: ''
}
const [ values, handleInputChange, reset ] = userForm( initialForm )
```
> useForm() // recibe un initialState
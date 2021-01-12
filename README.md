# Custom Hooks

Repositorio con custom hooks de React para reutilizar

## useCounter
Contador con state y 3 funciones:
* Increment
* Decrement
* Reset

## useFetch
Hook para hacer peticiones Fetch con:
* State
```js
const [state, setState] = useState({ data: null, loading: true, error: null })
```
* useEffect
Para ejecutar el **setState** y hacer la **petición fetch**

## useForm
Con su state 
```js
const [values, setValues] = useState(initialState)
```
Y dos funciones: 
* handleInputChange
* reset
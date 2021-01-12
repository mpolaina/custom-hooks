# Custom Hooks

Repositorio con custom hooks de React para reutilizar

## Hooks

### useCounter
Contador con state y 3 funciones:
* Increment
* Decrement
* Reset

### useFetch
Hook para hacer peticiones Fetch con:
#### State
```
initialState { data:null, loading:true, error:null}
```
#### useEffect
Para ejecutar el **setState** y hacer la **petición fetch**

### useForm
Con su state de values y funciones **handleInputChange** y **reset**.
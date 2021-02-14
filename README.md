### Sort

```js
const alumnas = ["Angie", "Sol", "Flor"]
const edades = [1, 23, 75, 33, 111, 12, 101]
const alumnasObj = [
  {
    nombre: "Sol", 
    edad: 17
  }, {
    nombre: "Angie",
    edad: 52
  }, {
    nombre: "Flor", 
    edad: 25
  }
]
```

Utilizando el metodo `sort` ordenar alfabeticamente el array alumnas, de menor a mayor el array edades, y de la edad mas pequeña a la mas grande el array alumnasObj

### Arrays de objetos

En index.js tienen un array de objetos que representan artistas.

Utilizando los métodos de array vistos (map, filter, every, some, find, reduce, sort), crear las siguientes funciones:

`artistasSolistas`, que tome por parámetro un array de artistas y devuelva un array con les artistas que sean solistas

`artistasPorEdad`, que tome un parámetro "edad" y un array de artistas y devuelva un array con les artistas que tengan dicha edad

`artistasConMasDiscosQue`, que tome por parámetro "cantidadDeDiscos" y un array de artistas y devuelva un array con les artistas que tiene más de esa cantidad de discos, ordenados de mayor a menor según cantidad de discos

`artistaConMasEntradasVendidas`, que tome por parámetro un array de artistas y devuelva el objeto artista que vendió más entradas en su último recital

`artistaConMayorRecaudacion`, que tome por parámetro un array de artistas y devuelva el objeto artista que más recaudó en su último recital (entradasVendidas * costoEntradas)

`artistasConDiscoEnAnio`, que tome por parámetro un parámetro "anio" y un array de artistas, y devuelva un array con los artistas que tengan publicado al menos un disco en dicho año

`artistaConMasCopias`, que reciba como parametro un array de artistas y devuelva el objeto artista que más copias de discos en total vendió

`cantidadDeArtistasPorInstrumento`, que tome por parámetro un array de artistas y devuelva un objeto donde cada "instrumento" es una propiedad y su valor la cantidad de artistas que tocan dicho instrumento

`cantidadDeArtistasPorGenero`, que tome por parámetro un array de artistas y devuelva un objeto donde cada "género" es una propiedad y su valor la cantidad de artistas de dicho género

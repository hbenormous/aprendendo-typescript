# Definindo Tipos

### Criando uma interface
- `interface` Usada pra definir a estrutura de uma Classe, Objeto ou Função.
- `Usuario` Nome da interface
- `nome` & `idade` Propriedades da interface
- `string` & `number` Tipo de propriedade
```ts
interface Usuario {
	nome: string,
	idade: number
}
```

### Usando uma interface
- `usuario` Nome do objeto
- `: Usuario` Sintaxe `: TypeName`
```ts
const usuario: Usuario = {
	nome: "Steve",
	idade: 19
}
```

### RESULTADO(log)
```js
{
  "nome": "Steve",
  "idade": 19
}
```
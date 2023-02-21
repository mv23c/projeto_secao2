# Notas sobre o projeto

## Componente de classe
Para criar um componente de classe, fazemos:

```jsx
class App extends Component {
    render() {
        return <h1>Olá mundo</h1>
    }
}
```
Ou seja, criamos uma classe cujo nome inicia com letra maiúscula e que estende Component (que deve ser importado). Essa classe contém um método render() que vai retornar um jsx.
O método render() é responsável por renderizar o conteúdo jsx que deve ser exibido na tela, com base no estado atual do componente e nas props recebidas. É um método obrigátorio em componentes de classe. 


## State

Todo componente pode ter estado e este é basicamente os dados desse componente.
O estado (state) em react é um objeto que contém as informações (dados) internas de um componente e pode ser alterado ao longo do tempo, afetando renderizzação do componente e de seus filhos. 
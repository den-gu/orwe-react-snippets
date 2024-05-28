# ORWE React Snippets for VSCode

## Descrição

ORWE React Snippets é uma coleção de snippets úteis para desenvolvimento em React, projetada para acelerar o seu fluxo de trabalho e aumentar a produtividade. Com esta extensão, você pode facilmente inserir códigos comuns do React com apenas alguns toques no teclado.

## Funcionalidades

- **Componentes Funcionais**: Snippets para criação rápida de componentes funcionais.
- **Componentes de Classe**: Snippets para criação de componentes de classe.
- **Hooks**: Snippets para alguns dos hooks mais comuns, como `useState` e `useEffect`.

## Instalação

1. Abra o VSCode.
2. Vá para a aba de Extensões (`Ctrl+Shift+X` ou `Cmd+Shift+X` no Mac).
3. Procure por "ORWE React Snippets".
4. Clique em "Instalar".

## Uso

Após instalar a extensão, você pode usar os snippets digitando os prefixos dos snippets em seus arquivos `.ts`, ou `.tsx`.

### Exemplos de Snippets

- **rxf**: cria um componente funcional.

  ```typescript
  // rxf
  import React from "react";

  export const Component: React.FC = () => {
    return "your code goes here";
  };
  ```

- **rush**: cria um componente funcional com useState.

  ```typescript
  // rush
  import React, { useState } from "react";

  const Component: React.FC = () => {
    const [state, setState] = useState(0);
    return "your code goes here";
  };
  export default Component;
  ```

- **rueh**: cria um componente funcional com useEffect.

  ```typescript
  // rueh
  import React, { useEffect } from "react";

  const Component: React.FC = () => {
    useEffect(() => {
      "your code goes here";
    }, []);
    return "your code goes here";
  };

  export default Component;
  ```

- **rcr**: cria um componente funcional com renderização condicional.

  ```typescript
  // rcr
  import React from "react";

  const Component: React.FC = (condition) => {
    return condition ? "your code goes here" : "your code goes here";
  };

  export default Component;
  ```

### Todos os Snippets

`rxf` - react export function: cria um componente funcional  
`rxfd` - react export function default: cria um componente funcional e o exporta como default  
`rxc` - react export class: cria um componente de classe  
`rxcd` - react export class default: cria um componente de classe e o exporta como default  
`rush` - react useState hook: cria um componente funcional com useState  
`rueh` - react useEffect hook: cria um componente funcional com useEffect  
`rcr` - react conditional rendering: cria um componente funcional com renderização condicional

## Contribuição

Contribuições são bem-vindas! Se encontrares um bug ou tiveres sugestões de novos snippets, por favor, abra uma issue ou envie um pull request no [repositório do GitHub](https://github.com/den-gu/orwe-react-snippets).

### Como Contribuir

1. Faça o fork deste repositório.
2. Crie uma nova branch: `git checkout -b minha-feature`.
3. Faça as suas modificações.
4. Faça o commit: `git commit -m 'Adiciona minha feature'`.
5. Push para a branch: `git push origin minha-feature`.
6. Abra um pull request.

## Licença

Este projeto está licenciado sob a Licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

---

# ORWE React Snippets for VSCode

![Logo](path-to-your-logo.png)

## Descrição

ORWE React Snippets é uma coleção de snippets úteis para desenvolvimento em React, projetada para acelerar o seu fluxo de trabalho e aumentar a produtividade. Com esta extensão, você pode facilmente inserir códigos comuns do React com apenas alguns toques no teclado.

## Funcionalidades

- **Componentes Funcionais**: Snippets para criação rápida de componentes funcionais.
- **Hooks**: Snippets para os hooks mais comuns, como `useState`, `useEffect`, `useContext` e mais.

## Instalação

1. Abra o VSCode.
2. Vá para a aba de Extensões (`Ctrl+Shift+X` ou `Cmd+Shift+X` no Mac).
3. Procure por "ORWE React Snippets".
4. Clique em "Instalar".

## Uso

Após instalar a extensão, você pode usar os snippets digitando os prefixos dos snippets em seus arquivos `.ts`, ou `.tsx`.

### Exemplos de Snippets

- **rfc**: Cria um componente funcional básico.
  ```typescript
  // rfc
  import React from 'react';

  const ComponentName = () => {
    return (
      <div>
        {/* Content here */}
      </div>
    );
  };

  export default ComponentName;
  ```

- **useState**: Cria um hook useState.
  ```typescript
  // useState
  const [state, setState] = useState(0);
  ```

- **useEffect**: Cria um hook useEffect.
  ```typescript
  // useEffect
  useEffect(() => {
    // effect
    return () => {
      // cleanup
    };
  }, [dependencies]);
  ```

## Contribuição

Contribuições são bem-vindas! Se encontrares um bug ou tiveres sugestões de novos snippets, por favor, abra uma issue ou envie um pull request no [repositório do GitHub](https://github.com/den-gu/orwe-react-snippets).

### Como Contribuir

1. Fork este repositório.
2. Crie uma nova branch: `git checkout -b minha-feature`.
3. Faça as suas modificações.
4. Faça o commit: `git commit -m 'Adiciona minha feature'`.
5. Push para a branch: `git push origin minha-feature`.
6. Abra um pull request.

## Licença

Este projeto está licenciado sob a Licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

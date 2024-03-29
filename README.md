# Practicing React
Praticando os principais conceitos do React

### Checklist
- [X] 1. Crie um projeto React com TS usando Vite 
```npm create vite@latest```

- [X] 2. Entre na pasta do projeto, instale as dependências e, depois, instale o eslint da Trybe 
```npm install @trybe/eslint-config-frontend```

- [X] 3. Crie o arquivo .eslintrc.json e faça o extends para 
```@trybe/eslint-config-frontend/typescript```

- [X] 4. Inicie o projeto e veja se está tudo funcionando.
Como sugestão, você pode deletar todo o conteúdo que não é necessário, do arquivo App.tsx e deixar apenas o return do componente com algo como ```<div>Work in progress</div>```.

- [X] 5. Crie um componente chamado Title que exiba o título                                     ```<h1>Desenvolvimento Web</h1>``` na tela.

- [X] 6. Crie um componente chamado ```ModuleDetails``` que exiba o nome dos módulos deste curso.

- [x] 7. Crie um componente chamado ```HelloWorld``` que importa e renderiza os componentes criados anteriormente.

- [X] 8. Renderize o componente ```HelloWorld``` no componente ```App```.

- [ ] 9. No componente ```HelloWorld```, crie uma função que calcule a idade do usuário a partir da data de nascimento e a exiba na tela. 

Dica: você poderá pegar essa fórmula pronta da internet.

Para realizar o cálculo da idade, você pode criar uma função utilitária, colocá-la dentro da pasta ```src/utils/age.ts``` e importá-la no componente HelloWorld ou, se preferir, pode criar a função diretamente no componente HelloWorld.

# Projeto Flutter - Produtos e Funcionários

Aplicativo em Flutter que exibe dados de produtos e funcionários a partir de arquivos JSON locais.

---

## Como testar

1. Clone o repositório
2. Abra no VSCode
3. Abra o terminal (CTRL + ")
4. Execute:
   flutter pub get
5. Depois execute:
   flutter run
6. Escolha um navegador ou emulador

---

## Sobre o projeto

O app possui:

- Tela Splash com animação
- Tela Home com navegação entre itens
- Leitura de arquivos JSON locais
- Botões de próximo e anterior
- Menu dropdown na tela de funcionários

---

## Estrutura

- lib/main.dart → inicialização do app  
- lib/pallet.dart → cores do projeto  
- lib/theme.dart → tema dos widgets  
- assets/mockup/produtos.json → lista de produtos  
- assets/mockup/funcionarios.json → lista de funcionários  

---

## JSON de Funcionários

Cada funcionário possui:

- id  
- nome  
- cargo  
- salario  
- dataContratacao  
- avatar (imagem da internet)  

---

## Configuração importante

No pubspec.yaml:

flutter:
  uses-material-design: true
  assets:
    - assets/
    - assets/mockup/

---

## Tecnologias

- Flutter  
- Dart  
- JSON  








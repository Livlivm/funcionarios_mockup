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

---

## Print 
https://scontent.cdninstagram.com/v/t1.15752-9/670823568_1252250000311227_1933924541445223460_n.png?_nc_cat=100&ccb=7-5&_nc_sid=fc17b8&efg=eyJxZV9ncm91cHMiOlsiaWdkX2Jlc3RfZWZmb3J0X2ltYWdlOnRlc3QiXX0%3D&_nc_ohc=v5nyW93QhtAQ7kNvwHnKPTz&_nc_oc=Adqam8U2KN9AiNnH3qlvC3h1Md2KqJ6NisvsiiBPwh7JdGJZrO4s6St31uV66YPnRjV7EQ195KkKdbGDWUWbzOQE&_nc_ad=z-m&_nc_cid=0&_nc_zt=23&_nc_ht=scontent.cdninstagram.com&_nc_ss=7a32e&oh=03_Q7cD5AEVYw1YzWErQL0SV0FH-Vg9EiCQkmC4GUs5duxcXXK3yg&oe=6A1034AC




## Autor

Livia Morais

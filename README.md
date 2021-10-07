# Trabalhando com Módulos em JavaScript
## O que são módulos
Módulos arquivos JavaScript que tem a capacidade de exportar e importar informações de outros arquivos do mesmo tipo.

## Algumas vantagens 
- Organização do código;
- Compartilhamento de variáveis em escopos diferentes;
- Explicitaas dependências dos arquivos.

## Named Exports
- É quando você quer exportar mais de um arquivo
1. Exemplo <br>
![Screenshot_3](https://user-images.githubusercontent.com/72028645/136434777-6243b10f-e7b7-452d-85ec-ba1b4a62e648.png)

2. Exemplo <br>
![Screenshot_4](https://user-images.githubusercontent.com/72028645/136434789-3a3eff1c-07c4-4804-b278-ef58f7794f20.png)

## Atividade
Esta atividade tem como objetivo que você veja **no console do seu navegador** como os módulos funcionam.

1. Instale a extensão "Live Server" no seu VSCode;
2. Crie um arquivo com uma estrutura HTML padrão;
3. Crie dois arquivos `.js` ou `.mjs`, um chamado `funcoes` e outro chamado `main`;
4. No arquivo `funcoes`:
   1. Crie uma função chamada `mostraIdade`, que recebe `nome` e `idade` e retorna a string: `A idade de ${nome} é ${idade}`;
   2. Siga o mesmo padrão para outras funções como `mostraCidade` e `mostraHobby`;
   3. Exporte estas funções.
5. No arquivo `main`:
   1. Importe as funções do arquivo `funcoes`;
   2. Faça a chamada de todas elas;
6. Utilizando a extensão "Live Server", abra o seu navegador e veja no console que as informações foram logadas corretamente.

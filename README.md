# Trabalhando com Módulos em JavaScript
## Requisitos
- Terminal
- IDE

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
7. Ou entre no projeto no terminal e digite:
>node main.mjs

## O que são módulos
Módulos arquivos JavaScript que tem a capacidade de exportar e importar informações de outros arquivos do mesmo tipo.

## Algumas vantagens 
- Organização do código
- Compartilhamento de variáveis em escopos diferentes
- Explicitaas dependências dos arquivos

## Named Exports
- É quando você quer exportar mais de um arquivo
1. Exemplo <br>

![Screenshot_14](https://user-images.githubusercontent.com/72028645/136436287-da4ad893-408b-455a-bbe7-ae5dff73a454.png)

2. Exemplo <br>

![Screenshot_15](https://user-images.githubusercontent.com/72028645/136436403-e4c014fe-9934-49d8-9a44-920ca38dc072.png)

## Default Exports
- Só pode haver um por arquivo
- Será o retorno padrão do seu arquivo

![Screenshot_6](https://user-images.githubusercontent.com/72028645/136435300-1ed50c00-4980-4524-8c96-5cf5d6dbb0cd.png)

## Importar
### Named Exports
![Screenshot_7](https://user-images.githubusercontent.com/72028645/136435505-1957d23b-c5b0-4504-9d7a-fdfd9d2540ea.png)

### Default Exports
![Screenshot_8](https://user-images.githubusercontent.com/72028645/136435560-da3b2c0b-a834-414f-8af1-aaef88ead5de.png)

### Trocando nome de imports
![Screenshot_9](https://user-images.githubusercontent.com/72028645/136435638-0428e82b-0852-4063-9ce6-0701cfbdf04d.png)

### Importando todos os dados de um arquivo
![Screenshot_10](https://user-images.githubusercontent.com/72028645/136435717-d08b1661-a5fd-49c6-8fe0-b0bad84be57b.png)

### Vinculando ao HTML

Para fazer testes localmente (de um arquivo no seu computador), será necessário estar rodando um servidor. Isso pode ser feito utilizando a extensão “Live Server”, do VSCode.
![Screenshot_12](https://user-images.githubusercontent.com/72028645/136435876-4e5cdec7-bb94-44a6-8d20-bb13503add5e.png)

## Curiosidades
- Módulos sempre estão em “strict mode”
- Podem ser utilizadas as extensões .js e .mjs
- Para testes locais, é necessário utilizar um servidor
- Ao importar, sempre lembre da extensão (.js, .mjs)
- Ao importar, sempre utilize “./” como ponto de partida

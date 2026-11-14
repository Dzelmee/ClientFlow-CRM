# ClientFlow CRM

Quis montar um CRM que fosse direto ao ponto: cadastrar contatos, encontrar informações rapidamente e acompanhar o que está acontecendo com os registros comerciais. O desafio foi fazer o painel ser útil sem deixar a interface carregada.

## O que funciona

- Cadastro, edição e exclusão de registros, com validação no servidor.
- Pesquisa e formulários para consultar e atualizar informações.
- Indicadores calculados a partir dos dados cadastrados.
- Layout responsivo, temas claro e escuro e animações que respeitam a preferência por movimento reduzido.

## Como executar

```bash
npm test
npm start
```

O servidor inicia em `http://localhost:3000`. Para usar outra porta, configure `PORT`.

## Tecnologias e armazenamento

Usei HTML, CSS e JavaScript com ES Modules no front-end. O servidor é feito em Node.js, usando o módulo HTTP nativo. Os registros ficam em um arquivo JSON local.

## Limitações

Esta é uma aplicação de demonstração, não um serviço pronto para produção. Ainda não há autenticação, permissões por usuário nem banco de dados de produção. O armazenamento em JSON também não foi pensado para várias instâncias simultâneas.

## Imagens

Usei fotografias do [Unsplash](https://unsplash.com/license):
- https://images.unsplash.com/photo-1552664730-d307ca884978?auto=format&fit=crop&w=1600&q=85
- https://images.unsplash.com/photo-1556761175-b413da4baf72?auto=format&fit=crop&w=1100&q=85

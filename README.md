# Teste para Desenvolvedor(a) Android do Zap Imóveis

Seja bem vindo! Agradecemos o seu interesse em participar do nosso processo seletivo.

Por favor atente-se as instruções abaixo e entre em contato conosco ao menor sinal de dúvidas.

## Objetivo

* Criar uma aplicativo que consulte uma REST API e mostre uma listagem de itens;
* Cada item da lista deve permitir acesso ao detalhe do item;
* No detalhe do item deve haver uma opção para que o usuário envie uma mensagem. 

## Layout

Os itens tratam-se de anúncios de imóveis. Fique a vontade para apresentar os dados da forma que achar melhor (o layout é livre) mas procure exibir todos os campos que estão disponíveis no JSON.

Dê atenção especial às recomendações do [Material Design](https://developer.android.com/design/material/index.html).

## Sobre seu código

Analisaremos:

* Organização do código;
* Boas práticas de programação;
* Possíveis bugs;
* Tratamento de erros.

## API

A listagem de itens está disponivel em http://demo4573903.mockable.io/imoveis

Para acessar cada detalhe do item basta adicionar o ID do item ao final da URL. Ex: http://demo4573903.mockable.io/imoveis/1

Para enviar uma mensagem faça um POST no seguinte endereço: http://demo4573903.mockable.io/imoveis/contato

O POST deve conter os dados do interessado (Nome, e-mail e telefone) e o código do anúncio. O corpo pode enviado por _form_ ou _json_. 

## Itens extras (não obrigatórios)

* Tente implementar ordenação na listagem (Ex: por preço, vagas, suites etc...);
* Implemente testes unitários e de aceitação (interface).

## Dicas

* Caso não saiba por onde começar em termos de layout, instale o aplicativo do [Zap Imóveis](https://play.google.com/store/apps/details?id=br.com.zap.imoveis) e tente fazer algo parecido com o que temos hoje;
* Fique a vontade para utilizar animações e recursos especias (ex: parallax etc...);
* Não se esqueça de validar os campos do formulário de contato;
* Teste bem seu aplicativo, evite crashes.
 
### Bom teste!

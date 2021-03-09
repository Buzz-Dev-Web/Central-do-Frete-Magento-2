# Central do Frete (Magento 2)


## Requisitos:

* Pasta **Buzz** criada dentro da app/code (obrigatório);
* Módulo **BUZZ Base** previamente instalado (recomendado);
* Acesso ao terminal do Magento;
* Loja em modo de desenvolvimento;

## Como instalar:

1 -> Descompacte o contéudo do módulo na pasta: app/code/Buzz/CentralDoFrete caso não crie automaticamente, é interessante que seja criado.

2 -> Feito isso via terminal digite:

```

bin/magento module:status
```

O resultado esperado deve ser:

imagem aqui (lista exibindo modulo pendente)

1-module-disable.png

3 -> Havendo êxito no processo anterior, também no terminal digite:

```

bin/magento setup:upgrade
```

imagem do setup:upgrade

2-setup-upgrade.png

4 -> Após finalizar esta etapa, recompile o Magento, através do comando:

```

bin/magento setup:di:compile
```

imagem do recompilar 3-imagem-recompilar.png

5 -> Caso queira verificar se o módulo foi instalado e ativado digite novamente o comando da etapa 2;

## Como configurar:

6 -> Acesse o painel administrador do Magento, 

7 -> Navegue até a sessão: LOJAS > CONFIGURAÇÃO > MÉTODO DE ENVIO > CENTRAL DO FRETE;

8 -> Altere o status de Habilitado para **Sim**,

9 -> Personalize o Titulo e Nome caso achar conveniente,

10 -> Insira o Token de integração disponibilizado pela equipe da **CENTRAL DO FRETE** no campo indicado na imagem abaixo,

imagem 4-token-central.png

11 -> Selecione o tipo de carga padrão conforme instrução da equipe comercial da **CENTRAL DO FRETE**,

12 -> Caso necessário, você pode alterar o mapeamento dos atributos em **MAPEAMENTO DE ATRIBUTOS**,

13 -> Informe as medidas padrões da sua carga em **MEDIDAS PADRÃO**,

14 -> Pronto, módulo instalado e configurado !

Boas vendas !

## Dúvida/Suporte:

Em caso de dúvidas entre em contato com o dept de suporte.
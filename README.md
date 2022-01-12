# Rentalx

## Cadastro de Carro

**RF** => Requisitos Funcionais
Deve ser possível cadastrar um novo carro.

**RN** => Regra de negócio
Não deve ser possível cadastrar um carro com uma placa já existente.
O carro deve ser cadastrado, por padrão, com disponibilidade.
* O usuário responsável pelo cadastro deve ser um usuário administrador.
## Listagem de Carros

**RF** => Requisitos Funcionais
Deve ser possível listar todos os carros disponíveis.
Deve ser possível listar todos os carros disponíveis a partir da marca.
Deve ser possível listar todos os carros disponíveis a partir da categoria.
Deve ser possível listar todos os carros disponíveis a partir da nome do carro.

**RN** => Regra de negócio
O usuário não precisa estar logado no sistema para fazer a listagem.

## Cadastro de Especificação no carro

**RF** => Requisitos Funcionais
Deve ser possível cadastrar uma especificação para um carro.
Deve ser possível listar todas as especificações.
Deve ser possível listas todos os carros.

**RN** => Regra de negócio
Não deve ser possível cadastrar uma especificação para um carro não cadastrado.
Não deve ser possível cadastrar uma especificação já existente para o mesmo carro.
O usuário responsável pelo cadastro deve ser um usuário administrador.

## Cadastro de imagens do carro

**RF** => Requisitos Funcionais
Deve ser possível cadastrar a imagem do carro
Deve ser possível listar todos os carros

**RNF** => Requisitos Não Funcionais
Utilizar o multer para upload dos arquivos

**RN** => Regra de negócio
O usuário deve poder cadastrar mais de uma imagem para o mesmo carro.
O usuário responsável pelo cadastro deve ser um usuário administrador.

## Aluguel de carro

**RF** => Requisitos Funcionais
Deve ser possível cadastrar um aluguel.

**RNF** => Requisitos Não Funcionais

**RN** => Regra de negócio
O aluguel deve ter duração miníma de 24 horas.
Não deve ser possível cadastrar um novo aluguel caso já exista um em aberto para o mesmo usuário.
Não deve ser possível cadastrar um novo aluguel caso já exista um em aberto para o mesmo carro.
O usuário responsável pelo cadastro deve ser um usuário administrador.
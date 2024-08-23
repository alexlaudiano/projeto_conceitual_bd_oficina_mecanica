<h1 align="center">Projeto Esquema Conceitual de Banco de Dados - Oficina Mecânica</h1>

<p align="center">
    <img src="http://img.shields.io/static/v1?label=STATUS&message=EM%20ANDAMENTO&color=yellow&style=for-the-badge"/>
    <img src="http://img.shields.io/static/v1?label=License&message=MIT&color=green&style=for-the-badge"/>
</p>

<div align="center">

### Tópicos

:small_blue_diamond: [Descrição do Projeto](#descrição-do-projeto)
:small_blue_diamond: [Contexto](#contexto)
:small_blue_diamond: [Estrutura do Esquema Conceitual](#estrutura-do-esquema-conceitual)
:small_blue_diamond: [Pontos Adicionais](#pontos-adicionais)

:small_blue_diamond: [Tecnologias Utilizadas](#tecnologias-utilizadas)
:small_blue_diamond: [Contribuição](#contribuição)
:small_blue_diamond: [Realizado por](#realizado-por)
:small_blue_diamond: [Licença](#licença)

</div>

## Descrição do Projeto:

Este projeto apresenta o esquema conceitual de um sistema de controle e gerenciamento de ordens de serviço para uma oficina mecânica. O objetivo do sistema é gerenciar a execução das ordens de serviço, que incluem tanto os serviços prestados quanto as peças utilizadas em reparos ou revisões de veículos.

## Contexto:

* Os clientes levam seus veículos à oficina para conserto ou revisão.
* Cada veículo é designado a uma equipe de mecânicos, que identifica os serviços necessários e preenche uma Ordem de Serviço (OS).
* A OS contém a descrição dos serviços e peças necessárias, bem como as datas de emissão e conclusão, e o valor total dos serviços.
* Cada serviço e peça têm um valor de referência, e o sistema permite que o cliente autorize a execução dos serviços antes de serem realizados.

## Estrutura do Esquema Conceitual:

* **Clientes** são identificados por um código e podem ser Pessoa Física (PF) ou Pessoa Jurídica (PJ). Eles podem ter um ou mais veículos associados.
* **Veículos** são associados a clientes e têm atributos como placa, modelo e ano.
* **Ordens de Serviço (OS)** são atribuídas a veículos e incluem os serviços e peças necessários para a execução do trabalho.
* **Serviços** e **Peças** são incluídos nas OSs por meio de entidades associativas, que registram a quantidade e o valor de cada item.
* **Equipes de Mecânicos** são responsáveis pela execução das OSs, e cada mecânico é associado a uma equipe.

## Pontos Adicionais:

Qualquer aspecto que não tenha sido especificado diretamente na narrativa foi inferido com base em práticas comuns de gerenciamento de oficinas mecânicas. As descrições e relacionamentos propostos no esquema conceitual visam garantir que o sistema seja robusto e flexível o suficiente para atender às necessidades de uma oficina real.

## Tecnologias Utilizadas

* MySQL Workbench

## Contribuição

Sinta-se à vontade para contribuir com este projeto. Para isso, siga os passos abaixo:

1. Faça um fork deste repositório.
2. Crie uma branch com a sua feature: `git checkout -b minha-feature`
3. Commit suas mudanças: `git commit -m 'Minha nova feature'`
4. Faça um push para a branch: `git push origin minha-feature`
5. Abra um Pull Request

## Realizado por

* Alex Laudiano

Para mais informações, entre em contato:

[![LinkedIn Badge](https://img.shields.io/badge/-LinkedIn-373737?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/laudiano/)
[![Gmail Badge](https://img.shields.io/badge/Gmail-373737?style=flat&logo=Gmail&logoColor=white)](mailto:laudiano@gmail.com)
[![Instagram Badge](https://img.shields.io/badge/-Instagram-373737?style=flat&logo=instagram&logoColor=white)](https://www.instagram.com/laudianoalex/?hl=pt-br)

## Licença

Este projeto está licenciado sob a Licença MIT - veja o arquivo [LICENSE](LICENSE) para mais detalhes.

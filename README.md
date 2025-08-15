<h1 align="center">Wordpress em Alta Disponibilidade na AWS</h1>

<div align="center">
  <strong>💻 Implantação do WordPress na AWS de forma escalável e tolerante a falhas, garantindo alta disponibilidade e desempenho. 💻</strong>
</div>

</br>

<p align="center">
	<img alt="Status Em Desenvolvimento" src="https://img.shields.io/badge/STATUS-EM%20DESENVOLVIMENTO-green">
    <a href="https://img.shields.io/github/repo-size/sahyneer/wordpress-aws">
        <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/sahyneer/wordpress-aws">
    </a>
    <img alt="Tamanho do Repositório" src="https://img.shields.io/github/repo-size/sahyneer/wordpress-aws">
</p>

<p align="center">
    <a href="#-visão-do-projeto">Visão do projeto</a> •
    <a href="#-tecnologias">Tecnologias</a> •
    <a href="#-etapas-do-projeto">Etapas do Projeto</a> •
    <a href="#-testes">Testes</a> •
    <a href="#-autora">Autora</a>
 </p>

</br>

## 🔭 Visão do projeto

O projeto foi desenvolvido durante a 2º Sprint do Programa Compass.Uol Scholarship, na qual implementa uma arquitetura altamente disponível do WordPress na AWS, utilizando EC2 em Auto Scaling Group (ASG) atrás de um Application Load Balancer (ALB) para garantir escalabilidade e balanceamento de tráfego. 

Os arquivos da aplicação são armazenados de forma centralizada no Amazon EFS, permitindo que múltiplas instâncias compartilhem o mesmo conteúdo, enquanto o Amazon RDS fornece um banco de dados relacional gerenciado, assegurando alta disponibilidade e resiliência.

</br>


## 💻 Tecnologias

[![Tenologias](https://skillicons.dev/icons?i=linux,bash,ubuntu,docker,wordpress,aws,git)](https://skillicons.dev)

</br>

## ⚙️ Etapas do Projeto

### Índice

- [Configuração da VPC](#configuração-da-vpc)

    + [Configurando Subredes](#criando-subredes)

    + [Criando o Internet Gateway](#criando-o-internet-gateway)

    + [Tabelas de Rotas](#criando-tabelas-de-rotas)

    + [Mapa de Recursos](#mapa-de-recursos)

- [Configuração dos Grupos de Segurança](#configuração-dos-grupos-de-segurança)

- [Configuração do Elastic File System (EFS)](#configuração-do-elastic-file-system)

- [Configuração do Relational Database Service (RDS)](#configuração-do-relational-database-service)

- [Launch Template](#launch-template)

- [Application Load Balancer](#application-load-balancer)

- [Auto Scaling Group](#auto-scaling-group)

</br>

## 🧪 Testes

## 🧙‍♂️ Autora

<p>Feito com 💛 por Sarah Cabral<p>

<p>Vamos nos conectar?</p>

[![Gmail Badge](https://img.shields.io/badge/-Sarah_Cabral-006bed?style=flat-square&logo=Gmail&logoColor=white&link=mailto:sahyneer@gmail.com)](mailto:sahyneer@gmail.com)
[![Linkedin: Sarah Cabral](https://img.shields.io/badge/-in/sahyneer-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/sahyneer//)](https://www.linkedin.com/in/sahyneer/)
[![GitHub](https://img.shields.io/github/followers/sahyneer?label=follow&style=social)](https://github.com/sahyneer)

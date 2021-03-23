# Documento de Visão

## Histórico de revisão

| Data       | Autor                                        | Modificações                      | Versão |
| ---------- | -------------------------------------------- | --------------------------------- | ------ |
| 23/02/2021 | [Ana Júlia](https://github.com/aluzianobriceno) e [Luiz Gustavo](https://github.com/LightZX) | Adicionando início do documento de visão | 1.0    _|
| 26/02/2021 | [Ana Júlia](https://github.com/aluzianobriceno) e [Luiz Gustavo](https://github.com/LightZX) | Atualizando o início do documento | 1.1    |
| 27/02/2021 | [Ana Júlia](https://github.com/aluzianobriceno) | Finalizando a Introdução, Posicionamento, Recursos do Produto e Restrições | 1.2    | 
| 27/02/2021 | [Ana Júlia](https://github.com/aluzianobriceno) e [Luiz Gustavo](https://github.com/LightZX) | Correção e incremento de alguns tópicos| 1.3    |

## __Introdução__

Este documento de visão tem como objetivo apresentar o escopo e o propósito do Projeto Kokama, definir todas as funcionalidades do aplicativo que será desenvolvido, explicar de uma maneira clara e precisa todos problemas que estão sendo resolvidos. Para que juntos, a equipe desenvolvedora e o cliente cheguem num produto final que seja satisfatório. 

### __Propósito__

O projeto tem como finalidade ajudar o povo Kokama a salvar a sua cultura que tem sido negligenciada por tanto tempo, mais especificamente a sua língua. Com a criação de um aplicativo que faça a tradução do português para kokama e vice-versa, eles terão uma nova maneira de aprender e ensinar sua língua. Portanto, o propósito desse projeto aumenta, e deixa de ser somente trazer de volta a um idioma quase perdido e passa a ser de uma cultura inteira, podendo ainda ajudar a disseminar uma luta de um povo quase esquecido pelo restante do país.

### __Escopo__

Em um cenário onde a população indígena é constantemente atacada, se faz necessário tomar medidas que solucionem seus problemas. Um deles é a difuculdade em se comunicar com pessoas que não falam a sua língua, portanto, um aplicativo que faça essa tradução é muito bem vindo. Assim como uma forma que facilite o ensino desse idioma para outras pessoas. A perda de sua cultura é outro problema que enfrentam, então ajuadá-los a dissemina-lá trará muitos ganhos ao povo Kokama, pois sua história estará guardada de maneira que não será possível perde-lá.


### __Definições, acrônimos e abreviações__

* FGA - Faculdade do Gama.
* UnB - Universidade de Brasília.
* MDS - Métodos de Desenvolvimento de Software.
* EPS - Engenharia de Projeto de Software.
* App - Aplicativo mobile, para o sistema operacional Android.
* Back-end - Ele é o responsável, em termos gerais, pela implementação da regra de negócio.
* Front-end - Parte da aplicação que interage diretamente com o usuário.
* IOS - Sistema Operacional da Apple.
* Apple Store - Loja de aplicativos da Apple.
* Play Store - Loja de aplicativos Android.

### __Visão Geral__

Esse documento é divido em 6(seis) partes iniciais. A primeira sendo a Introdução, que fala sobre o propósito do projeto e em que contexto ele se encontra; A segunda parte é o Posicionamento, expõe sobre o negócio que está por trás do produto, explica o problema que o app resolve; a terceira parte fala sobre as partes interessadas no aplicativo, o cliente, o desenvolvedor e o usuário; a quarta parte se refere ao produto que está sendo desenvolvido; a parte cinco faz referência aos recursos do aplicativo; a sexta parte, Restrições e por último as referências que ajudaram no processo de construção desse documento. 

## __Posicionamento__

### __Oportunidade de Negócios__

Esse aplicativo tem como objetivo principal traduzir palavras do Kokama para português e vice-versa. Facilita o ensino dessa língua e mostra um pouco da cultura Kokama.  

### __Instrução do Problema__ 
Os povos indígenas, através dos anos, vem sofrendo com o descaso da sociedade para com eles, tendo como consequências a perda de suas culturas. O povo Kokama não seria diferente, nessa pandemia eles perderam cerca de 90 anciões, isso demonstra uma perda significativa de conhecimentos das suas culturas. Uma solução bem sucedida traria benefícios para toda a sociedade, documentando e guardando informações, facilitando a comunicação com os Kokamas e futuramente com outros povos indígenas, ajudando a causa deles. (e mostrando para o resto do mundo que eles estão ali, que eles existem e são tão importantes quanto qualquer um.)*

### __Instrução de Posição do Produto__

Para a professora Altaci, quem viu a necessidade de armazenar e disseminar o conhecimento da sua cultura, esse aplicativo fornece bem mais que uma ajuda, mas sana uma necessidade de seu povo. O tradutor kokama é um aplicativo que traduz a língua dos kokama para o português. Já existe um aplicativo que faz isso, porém ele não foi assertivo nos seus resultados, gerando problemas ao invés de resolvê-los. O nosso produto difere dele, quanto a comunicação com o cliente, estamos usando uma metodologia de desenvolvimento que coloca a experiência com o cliente na frente, assim o resultado será o mais próximo possível daquilo que é esperado pelos estudantes, professores e demais interessados na cultura Kokama.


## __Descrições da Parte Interessada e dos Usuários__

### __Resumo da Parte Interessada__

| Grupo                       | Descrição                             | Responsabilidade             |
| --------------------------- | ------------------------------------- | ---------------------------- |
| Equipe de Gestão do Projeto | Alunos da disciplina de EPS, FGA-UnB  | Gerir e direcionar os desenvolvedores da matéria de MDS, como divisão de trabalhos e documentação do projeto |
| Equipe de Desenvolvimento   | Alunos da disciplina de MDS, FGA-UnB  | Documentar, desenvolver, testar e entregar um produto final que atinja as expectativas do cliente e satisfaça as suas necessidades |
| Professor                   | Professor das disciplinas EPS e MDS FGA-UnB | Orientar e avaliar os trabalhos desenvolvidos pela equipe de EPS e MDS |
| Cliente                     | Professora Altaci, que precisa ajudar a cultura do seu povo se manter viva e passa-lá adiante |  Liderar a sua equipe para entregar os materias para a equipe de desenvolvimento. Manter contato frequente com a equipe de desenvolvedores para sanar as dúvidas e ajudar com a própria visão do produto final |
| Equipe do Cliente           | Alunos da Professora Altaci, que irão ajudar no desenvolviemnto do projeto | Ajudar a documentar as frases e palavras traduzidas da língua kokama para o português e também os caracteres especiais para que sejam colocados no aplicativo |


### __Resumo do Usuário__

| Grupo                     | Descrição                                | Responsabilidade                                                |
| ------------------------- | ---------------------------------------- | --------------------------------------------------------------- |
| Professor                 | Professora Altaci                        | Fornecer palavras na língua kokama e suas respectivas traduções |
| Alunos                    | Alunos que se interssam pelo povo Kokama | Utilizar o aplicativo para aprender mais a língua               |
| Povo Kokama               | Residentes e descendentes da cultura kokama que querem passar para os filhos o aprendizado de forma mais intuitiva e fácil | Utilizar o app para aprender e perpetuar a língua |
| Pessoas                   | Entusiastas da cultura Kokama que desejam aprender a língua | Utilizar o app para aprender a lígua e a cultura kokama | 


### __Ambiente do Usuário__

Dispositivo Smartphone com capacidade de rodar aplicativos desenvolvidos tanto para Android como IOS.


## __Visão Geral do Produto__

### __Perspectiva do Produto__
O Projeto Kokama é um aplicativo mobile multiplataforma, com o intuito de ajudar os Kokamas, alunos, professores e entusiastas dessa cultura a traduzir palavras, facilitar o ensinamento desse idioma e ensinar um pouco sobre o povo Kokama àqueles que não os conhecem. Esse aplicativo conta com funções de tradução, cadastramento de palavras e atividades,além de mostrar a história e cultura do povo Kokama.

### __Resumo das Capacidades__


| Benefícios para o Cliente | Recursos                                 |
| ------------------------- | ---------------------------------------- |
| Fácil atualização das palavras e suas definições | Como super usuário pode modificar informações do aplicativo sobre os Kokamas |
| Adição de atividades | Professores podem adicionar atividades sobre a língua de diversas formas para complementar o aprendizado |
| Separação de tópicos das palavras | Separação de conjuntos específicos de palavras por meio de flash cards modificáveis |


| Benefícios para o Usuário  | Recursos                                 |
| -------------------------  | ---------------------------------------- |
| Aprender o idioma Kokama   | Flashcards interativos de aprendizado e o pŕoprio tradutor | 
| Conhecer a cultura Kokama  | Partes informativas no aplicativo indicando algumas informações sobre o povo no geral |
| Exercitar os conhecimentos | Podendo realizar exercicios interativos para fixação do que foi aprendido |


### __Licenciamento e Instalação__
O aplicativo Projeto Kokama, será disponibilizado por meio da Play Store e Apple Store, para celulares do tipo Android e IOS, contando com uma instalação simples e intuitiva, melhorando a experiência do usuário.**

## __Recursos do Produto__

### __Tradução__
É a principal função do aplicativo, o usuário entra com uma palavra em português e recebe a respectiva palavra em Kokama e vice-versa. As traduções também possuem ditos femininos e masculinos, frases de exemplo do idioma Kokama.

### __Cadastro de Palavras__
O administrador poderá adicionar palavras novas conforme a necessidade de utilizá-las for surgindo.

### __Exercícios de Fixação__
O usuário terá a ajuda desses exercícios para aprender melhor as novas palavras que descobriu utilizando o aplicativo, isso funcionará com a ajuda de flashcards, que mostram a palavra e a sua tradução no verso.

### __Atividades de Ensino__
Essas atividades funcionarão como um "complete a frase" ou "escolha a alternetiva correta". Frases incompletas aparecem na tela e o usuário terá que completar com uma palavra da língua Kokama.

### __Cadastro de Atividades__
O administrador poderá adicionar novas atividades conforme a sua necessidade.

### __História dos Kokamas__
O usuário terá disponível para leitura um relato sobre os Kokamas, explicando um pouco da sua história e cultura.


## __Restrições__

### __Restrições de Design__
O aplicativo deve fazer referência as cores utilizadas no app anterior, pois estão relacionadas a história do povo Kokama. A logo anterior deve ser preservada o máximo possível.

### __Restrições de Implementação__
O sistema terá o back-end desenvolvido na linguagem (A Definir) e o front-end (A Definir).

### __Restrições de Segurança__
O sistema não permite pessoas não autorizadas mudar significados e informações de traduções, visto que é um patrimônio cultural do povo

### __Restrições de Uso__
Para o cadastro de novas palavras e atividades é necessário ser administrador do sistema. Usuário comum poderá ter login na aplicação.


## __Referências__
IBM Knowledge Center - Documento de Visão: Estruturas de um Documento de Visão. 

Disponível em:
https://www.ibm.com/support/knowledgecenter/pt-br/SSWMEQ_4.0.6/com.ibm.rational.rrm.help.doc/topics/r_vision_doc.html 

Acesso em: 27 de Fevereiro de 2021.
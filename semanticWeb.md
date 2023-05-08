## 1-1 A Web

**Questão 1. 1.0 Pts**

Por que a World Wide Web (WWW) alcançou um avanço?

[ ] Documentos podem ser transferidos de um computador para
outro

[X] Documentos estão conectados por links

[ ] Documentos podem ser encontrados por um mecanismo de pesquisa

**Questão 2. 1.0 Pts**

Quais novos recursos traz a chamada Web 2.0?

[ ] Introdução de conteúdo multimídia

[ ] Experiência aprimorada do usuário

[X] Participação simplificada do usuário

## 1-2 Os Limites da Web

**Questão 1. 1.0 Pts**

A Web é baseada na linguagem de marcação HTML. HTML descreve

[X] como a informação é apresentada

[X] como a informação está vinculada (linked)

[ ] o que significa a informação

## 1-3 Compreensão

**Questão 1. 1.0 Pts**

A experiência considera todas as informações que você aprendeu e coloca em contexto com o mundo em que você está vivendo.
Mas para uma comunicação bem-sucedida ...

[X] ... tanto o remetente quanto o receptor devem considerar o mesmo contexto.

[ ] ... remetente e receptor têm que falar alto e claro.

[ ] ... a pragmática do receptor tem que ser clara.

[X] … a informação tem que ser transmitida e interpretada corretamente.

## 1-4 Os Limites da Web (continuação)

**Questão 1. 1.0 Pts**

Em que áreas problemáticas a Web atinge seus limites hoje?

[ ] Programação

[ ] Semântica

[ ] Extração de informações

[X] Personalizações

[ ] Educação

[ ] Transporte

[ ] Contexto

[X] Recuperação de informação

**Question 2. 1.0 Pts**

A pesquisa na Web tradicional baseada em palavras-chave leva a ...

[X] possivelmente muitos resultados de pesquisa irrelevantes.

[X] possivelmente poucos resultados relevantes.

[ ] muitos resultados corretos.

[ ] possivelmente muitos resultados não acessíveis.

## 1-5 A Visão da Web Semântica

**Questão 1. 1.0 Pts**

O que significa "compreensível por máquina"?

[ ] O conteúdo pode ser lido por máquinas e apresentado de uma maneira que seja compreensível para o ser humano.

[ ] O conteúdo é lido por máquinas e transferido para metadados
semânticos.

[ ] O conteúdo é bem estruturado e pode ser lido por máquinas.

[X] O conteúdo pode ser lido e interpretado corretamente por máquinas.

## 1-6 A Visão da Web Semântica (continuação)

**Questão 1. 1.0 Pts**

Uma entidade semântica é ...

[ ] uma URI com uma informação sobre o seu tipo de classe.

[X] um objeto ou coisa com um determinado significado explícito.

[ ] um objeto com uma determinada URI e outras informações de RDF.

**Questão 2. 1.0 Pts**

Qualquer Classe pode ter ...

[ ] apenas uma subclasse.

[X] mais de uma subclasse.

[ ] nenhuma subclasse.

**Questão 3. 1.0**

A DBpedia é ...

[ ] um site com informações semânticas.

[ ] um armazenamento de dados RDF.

[X] a versão semântica da Wikipedia.

## 1-7 Aplicações na Web de Dados

**Questão 1. 1.0**

Quais são os problemas gerais de recuperação de documentos
com mecanismos de pesquisa convencionais?

[X] usabilidade e personalização insuficientes.

[X] identificação de entidades semânticas.

[X] interpretando a string de consulta corretamente.

[ ] a desambiguação automática da string de consulta resulta em resultados de pesquisa incorretos.

## 2-1 Como identificar as coisas? - URIs

**Questão 1. 3.0 Pts**

Qual é a diferença entre um URI e um URL?

[X] URL indica apenas a localização de um recurso

[X] URI combina URL e URN

[ ] URI e URL indicam o mesmo

[ ] URI é um identificador persistente para um recurso da Web, que permanece inalterado durante o ciclo de vida

[X] URIs também servem para referenciar objetos do mundo real, fora da Web

**Questão 2. 3.0 Pts**

Um URI pode consistir em

[X] caminho (path) do sistema de arquivos

[X] parâmetros de consulta

[ ] informações sobre o tipo da entidade

[X] host ou nome de domínio

[ ] link de página web

[X] identificador de fragmento

[ ] designador

**Questão 3. 3.0 Pts**

Qual é a diferença entre apresentação e representação de um recurso na Web?

[ ] A apresentação determina a representação de um recurso na web.

[X] A apresentação de um recurso na Web é mostrada em um navegador da Web.

[X] A representação representa um recurso na Web.

[ ] A representação de um recurso identifica o recurso na Web.

[X] A representação determina a apresentação de um recurso na web.

[ ] A apresentação de um recurso identifica o recurso na Web.

## 2-2 Como representar fatos? - RDF (1)

**Questão 1. 3.0 Pts**

Qual(is) parte(s) de uma tripla RDF deve(m) necessariamente ser(em) representada(s) por um URI?

[ ] objeto

[X] propriedade

[X] sujeito

**Questão 2. 3.0 Pts**

Qual é a diferença entre um recurso literal e um recurso desreferenciável ?

[ ] Um literal só pode ser sujeito ou objeto em uma tripla RDF.

[X] Um literal não pode ser referenciado na Web.

[ ] Um recurso não requerido não pode ser referenciado na Web.

[ ] Um recurso desreferenciável só pode ser sujeito ou objeto em um triplo RDF.

[X] Um recurso desreferenciável pode ser sujeito, propriedade ou objeto em uma tripla RDF.

**Questão 3. 3.0 Pts**

Quais são / é um RDF-XML-Serialization correto para a informação "Ernie tem 43 anos"?

O seguinte cabeçalho (xml-head) é usado:

<xml version = “1.0“ encoding = “utf-8“>
<rdf: RDF xmlns: rdf = "http://www.w3.org/1999/02/22-rdf-syntax-ns#"
xmlns: ex = "http://exemplo.org/Exemplo#">

[X] <description rdf:about="http://example.org/Example#Ernie"ex:age="43"></description>

[X] <description rdf:about="http://exemplo.org/Exemplo#Ernie"><age
rdf:datatype="http://www.w3.org/2001/XMLSchema#int">43</age>
</description>

[X] <description rdf:about="http://example.org/Example#Ernie"><age>43</age></description>

[ ] <description rdf:about="http://example.org/Example#Ernie"><age=""43""></age></description>

**Questão 4. 2.0 Pts**

Quais são / qual é a(s) serialização(ões) RDF-XML correta(s) para a informação "Sesame Street está estrelando (starring) Ernie"?
O seguinte cabeçalho (xml-head) é usado:

<xml version = “1.0“ encoding = “utf-8“>
<rdf: RDF xmlns: rdf = "http://www.w3.org/1999/02/22-rdf-syntax-ns#"
xmlns: ex = "http://exemplo.org/Exemplo#">

[ ] <description rdf: about = "http://example.org/Example#Sesame_Street">
<starring> ex: Ernie </starring> </description>

[ ] <description rdf: about = "http://example.org/Exemplo#Sesame_Street"
ex: starring = "http://example.org/Example#Ernie"> </description>

[X] <description rdf: about = "http://example.org/Example#Sesame_Street">
	<starring rdf: resource = "http://example.org/Example#Ernie"> </starring>
	</description>

**Questão 5. 2.0 Pts**

Quais são / qual é a(s) serialização(ões) RDF-Turtle correta(s) para representar a informação "Sesame Street está estrelando (starring) Ernie”. O prefixo seguinte é usado:

@prefix ex: http://example.org/Example#.

[ ] ex:Sesame_Street; ex:starring ex:Ernie]

[X] ex:Sesame_Street ex:starring ex:Ernie .

[ ] "ex:Sesame_Street" ex:starring "ex:Ernie" .

[ ] ex/Sesame_Street ex/starring ex/Ernie .

## 2-4 Como representar fatos? - RDF (3)

**Questão 1. 2.0 Pts**

O que um nó em branco não tem?

[ ] um rótulo (label)

[ ] uma representação em RDF Turtle

[ ] quaisquer instruções descrevendo o nó

[X] um identificador global único/exclusivo

**Questão 2. 2.0 Pts**

Como um nó em branco pode ser desreferenciado?

[ ] de jeito nenhum

[ ] ele não precisa ser desreferenciado

[ ] somente pelo nó pai

[ ] pelo seu URI

[ ] de qualquer lugar

[X] por seu id de nó

[ ] somente dentro do mesmo gráfico

## 2-5 Como representar fatos? - RDF (4)

**Questão 1. 2,0 Pts**

O que o seguinte gráfico de RDF indica?

@prefix rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>.

@prefix ex: <http://example.org/StarWars#>.

````ex:Imperator ex:annoyedBy [
 a rdf:Statement ;
 rdf:subject ex:Luke ;
 rdf:predicate ex:foundOut ;
 rdf:object [a rdf:Statement ; rdf:subject ex:DarthVader ;
rdf:predicate ex:fatherOf ; rdf:object ex:Luke] ] .
````

[X] O Imperator está irritado com Luke por ele saber que Darth
Vader é seu pai.

[ ] O Imperator não é o pai de Luke.

[ ] Darth Vader é o pai de Luke.

[ ] O Imperator sabe que Luke é o pai de Darth Vader.

**Questão 2. 2.0 Pts**

Quais são os problemas da Reificação?

[ ] Uma reificação não pode ser desreferenciada.

[X] Reificação pode causar conflitos de tipos (classes, indivíduos, propriedades).

[ ] Uma reificação pode causar uma contradição de RDF.

[X] Reificação pode causar uma possível recursão infinita.

[ ] Uma reificação não pode ser expressa em RDF-XMLSerialization.

## 2-6 Como modelar classes e relações? – RDFS

**Questão 1. 2.0 Pts**

Quais das seguintes classes foram introduzidas pelo vocabulário RDFSchema (rdfs :)?

[X] rdfs:Class

[ ] rdfs:Property

[X] rdfs:Datatype
# RESTEE

Archetype para criar projetos REST EE com a LIB rest-util.

## Informações
* **Tipo:** ARCHETYPE
* **Finalidade:** Criar projeto REST EE com a LIB rest-util.
* **Gerenciamento e Automação:** Maven

## Comandos

	mvn archetype:create-from-project

Na pasta target/generated-sources/archetype:

Edita: pom.xml
 
	Coloca parametros para publicação FTP: https://www.evernote.com/shard/s11/sh/f142ef28-be99-4d4a-b423-f8da8df72825/bd1a9c2660bbf813509e57df841a6f34

Editar: archetype/main/resources/archetype-resources/pom.xml

	Retira os comentários indesejaveis

Depois de alterar, roda:
 
	mvn install
	mvn deploy
		
		
		
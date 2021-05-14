# Autenticação com `Firebase` em Aplicativos `Android`

Basicamente o `Google Firebase` é uma plataforma de `Backend-as-a-Service (BaaS)`, fornecendo um set de recursos prontos para usar em `APIs` e `SDKs` que permitem ao desenvolver `Android` se focar na construção do seu `app`, sem se preocupar com desenvolvimento de `backend`, `banco de dados`, etc. Com um modelo de negócio escalável, permite que você comece seu `app` sem pagar nada e depois ir pagando conforme a sua base de usuários cresce.

### Pré-requisitos

Para poder usar em `apps Android` é necessário:
- Dispositivo possua a `versão 4.0` ou superior
- `Google Play Services 11.0.4` ou superior
- `Android Studio versão 1.5` ou superior

Também é necessário que você tenha instalado no computador de desenvolvimento o `Google Play Services` do Repositório do Google, disponível no `SDK Manager` do `Android Studio`.

Existem duas formas de adicionar `Firebase` ao seu projeto no `Android Studio`. Uma é inserindo as dependências manualmente no arquivo `build.gradle`. A outra, mais moderna, é usando o `Firebase Assistant`.

Para usar o emulador nativo do Android para os testes, certifique-se de criar seu AVD usando uma imagem que possua a Play Store instalada para que o `Google Play Services` possa ser atualizado facilmente (uma das exigências do Firebase é ter a última versão do `Google Play Services` instalado).

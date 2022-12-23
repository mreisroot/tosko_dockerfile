# Tosko Dockerfile

E olha só, um repositório dedicado ao Dockerfile bem toskão que criei no Day 1 do treinamento "Descomplicando o Docker", da LINUXtips.

Para construir a imagem, execute:

`docker image build -t toskeira:1.0 .`

O arquivo tem 5 etapas:

1. Definição da imagem base sendo a imagem do Debian.

2. Definição do LABEL da imagem.

3. Definição de uma variável de ambiente no container da imagem.

4. Atualização dos repositórios Debian, instalação do pacote `stress` e limpeza do cache do apt.

5. Execução automática do comando `stress` em background no container.

É nois, vai!

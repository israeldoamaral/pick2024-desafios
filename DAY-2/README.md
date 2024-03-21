## DESAFIO DO DIA 2

Agora que você já sabe como colocar a App para rodar, você precisa coloca-la em uma imagem de container! E para isso, você precisa criar um DockerFile e lá, adicionar todos os detalhes necessários!

Nessa atividade você não tem o passo a passo de como criar cada tarefa, afinal, aqui é um desafio! Hora de você estudar, se dedicar e concluir esse desafio!

Esse não é um teste fácil, então tenha paciência com você!

### Passos

1. Criar um conta no Docker Hub, caso ainda não possua uma.  
2. Criar uma conta no Github, caso ainda não possua uma.  
3. Criar um Dockerfile para criar uma imagem de container para a nossa App  
        O nome da imagem deve ser SEU_USUARIO_NO_DOCKER_HUB/linuxtips-giropops-senhas:1.0  
4. Fazer o push da imagem para o Docker Hub, essa imagem deve ser pública  
5. Criar um repo no Github chamado LINUXtips-Giropops-Senhas, esse repo deve ser público.  
6. Fazer o push do cógido da App e o Dockerfile.
7. Criar um container utilizando a imagem criada.  
    O nome do container deve ser giropops-senhas  
    Você precisa deixar o container rodando  
8.  O Redis precisa ser um container  

[!TIP]  
Preste atenção no uso de variável de ambiente, precisamos ter a variável REDIS_HOST no container. Use sua criatividade!
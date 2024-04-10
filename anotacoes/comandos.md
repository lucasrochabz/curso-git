## Comandos

**git init**

Cria um novo repositório local no diretório atual. É utilizado para iniciar um novo projeto.

**git clone**

Copia um repositório remoto existente para sua máquina local, permitindo colaboração ou trabalho em projetos já existentes.

**git status**

Mostra o estado do seu diretório de trabalho e da área de preparação. É uma boa prática executar esse comando frequentemente para manter-se atualizado sobre o estado do projeto.

**git add & git add .**

Adiciona as alterações no seu diretório de trabalho à área de preparação. `git add .` adiciona todas as alterações, enquanto `git add <file>` adiciona alterações específicas.

**git commit**

Registra as alterações na área de preparação como um novo instantâneo no repositório local, junto com uma mensagem descritiva.

**git push**

Envia os commits locais para o repositório remoto, mantendo-o atualizado.

**git pull**

Baixa os últimos commits de um repositório remoto e mescla-os com seu branch local, atualizando o repositório local.

**git branch**

Lista, cria, renomeia ou exclui branches no seu repositório local. Os branches são usados para desenvolver funcionalidades isoladas sem interferir no branch principal.

**git checkout**

`git checkout -b <nova-da-branch>`

Troca seu diretório de trabalho para um branch ou commit diferente, descartando quaisquer alterações não commitadas. Também é usado para criar um novo branch a partir de um commit específico.

**git merge**

Combina as alterações de um branch em outro, criando um novo commit se não houver conflitos. É importante lidar com conflitos de forma adequada durante o merge.

**git diff**

Mostra as diferenças entre dois commits, branches, arquivos, ou o diretório de trabalho e a área de preparação. É útil para revisar alterações antes de confirmá-las.

**git log**

Mostra o histórico de commits no branch atual, juntamente com suas mensagens, autores e datas. É útil para rastrear o histórico de commits e entender as mudanças feitas ao longo do tempo.

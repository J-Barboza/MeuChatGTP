# Especificações Funcionais:

#### Autenticação da API: 
> O aplicativo permite ao usuário inserir uma chave de API da OpenAI, que será usada para autenticar as solicitações à API. Uma vez inserida, a chave de API não pode ser vista ou alterada, mas pode ser deletada e inserida novamente.

#### Validação da chave da API: 
> O usuário pode definir um intervalo de tempo para a validação da chave da API.

#### Interação com a API da OpenAI: 
> O aplicativo permite ao usuário fazer perguntas à API da OpenAI através de um prompt de pergunta. As respostas da API são exibidas em um textarea.

#### Gerenciamento de chats: 
> O aplicativo permite ao usuário criar um novo chat, que automaticamente se torna o chat ativo e disponível. O chat anterior é eliminado ao criar um novo.

#### Submissão de perguntas: 
> O aplicativo possui um botão para submeter a pergunta ao API da OpenAI e um botão para limpar o prompt da pergunta.

#### Armazenamento de mensagens: 
> As mensagens dos chats são armazenadas no dispositivo do usuário.

# Especificações Não Funcionais:

#### Segurança: 
> A chave da API da OpenAI deve ser armazenada de maneira segura no dispositivo do usuário para prevenir acessos não autorizados.

#### Desempenho: 
> O aplicativo deve ser capaz de processar as respostas da API da OpenAI em um tempo adequado, fornecendo uma experiência de usuário eficiente.

#### Usabilidade: 
> A interface do usuário deve ser intuitiva e fácil de usar, com um fluxo claro de ações para o usuário.

#### Portabilidade: 
> O aplicativo deve funcionar corretamente em diferentes versões do sistema operacional e em diferentes dispositivos.

#### Disponibilidade: 
> O aplicativo deve funcionar corretamente mesmo quando o dispositivo não estiver conectado à internet (embora a funcionalidade de perguntar à API da OpenAI não funcione sem uma conexão de internet).
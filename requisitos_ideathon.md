# Requisitos Ideathon

Este documento apresenta os requisitos detalhados de duas apresentações finalistas do Ideathon, contendo dois casos de uso para cada uma, suas respectivas histórias de usuário e critérios de aceitação.

---

## 1. Primeira Apresentação: AgroSmart (Gestão Inteligente para Pequenos Agricultores)

### 1.1. Casos de Uso

*   **Caso de Uso 01: Monitoramento de Irrigação**
    *   **Ator Principal:** Agricultor
    *   **Descrição:** O agricultor visualiza os níveis de umidade do solo em tempo real através do aplicativo e aciona ou programa o sistema de irrigação automatizado.
*   **Caso de Uso 02: Consulta de Preços de Insumos**
    *   **Ator Principal:** Agricultor
    *   **Descrição:** O agricultor pesquisa e compara os preços de fertilizantes e sementes fornecidos por diferentes cooperativas locais parceiras.

---

### 1.2. Histórias de Usuário e Critérios de Aceitação

#### História de Usuário 1 (Referente ao Caso de Uso 01)
*   **Como** pequeno agricultor,
*   **Quero** monitorar a umidade do solo e acionar a irrigação remotamente,
*   **Para que** eu possa evitar o desperdício de água e garantir a saúde das plantações.

**Critérios de Aceitação:**
1.  **Dado que** o sensor de solo detecta umidade abaixo de $30\%$, **quando** o sistema envia o alerta, **então** uma notificação push é exibida no celular do agricultor.
2.  **Dado que** o usuário está na tela de controle, **quando** ele clica no botão "Ligar Irrigação", **então** o sistema aciona a bomba de água em até $3$ segundos.
3.  **Dado que** a irrigação foi iniciada, **quando** o limite de umidade ideal é atingido, **então** o sistema desliga a bomba automaticamente.

---

#### História de Usuário 2 (Referente ao Caso de Uso 02)
*   **Como** produtor rural,
*   **Quero** comparar os preços de insumos agrícolas na minha região,
*   **Para que** eu possa economizar na compra de sementes e fertilizantes.

**Critérios de Aceitação:**
1.  **Dado que** o usuário acessa a aba de mercado, **quando** ele digita o nome do insumo desejado, **então** uma lista com os preços de diferentes fornecedores é exibida.
2.  **Dado que** a lista de preços está visível, **quando** o usuário filtra por "menor preço", **então** os resultados são ordenados do mais barato para o mais caro.
3.  **Dado que** o usuário seleciona um fornecedor, **quando** ele clica em "Ver Contato", **então** os dados de telefone e endereço da loja parceira são mostrados.

---

## 2. Segunda Apresentação: EduAcess (Plataforma Inclusiva de Estudos)

### 2.1. Casos de Uso

*   **Caso de Uso 01: Tradução Automática para Libras**
    *   **Ator Principal:** Aluno com Deficiência Auditiva
    *   **Descrição:** O aluno ativa a ferramenta de tradução em tempo real para assistir às videoaulas com suporte em Língua Brasileira de Sinais (Libras).
*   **Caso de Uso 02: Ajuste de Contraste e Fonte**
    *   **Ator Principal:** Aluno com Baixa Visão
    *   **Descrição:** O aluno personaliza o tamanho das fontes e o contraste da tela de leitura para facilitar o acompanhamento do material de estudo.

---

### 2.2. Histórias de Usuário e Critérios de Aceitação

#### História de Usuário 3 (Referente ao Caso de Uso 01)
*   **Como** estudante com deficiência auditiva,
*   **Quero** contar com um avatar tradutor de Libras nas videoaulas,
*   **Para que** eu possa compreender todo o conteúdo didático sem barreiras de comunicação.

**Critérios de Aceitação:**
1.  **Dado que** o aluno abre uma videoaula, **quando** ele clica no ícone "Ativar Libras", **então** o avatar virtual aparece na tela realizando a tradução simultânea.
2.  **Dado que** o avatar está ativo, **quando** o aluno pausa o vídeo, **então** a tradução em Libras pausa instantaneamente no mesmo frame.
3.  **Dado que** o usuário prefere maior visibilidade, **quando** ele ajusta o tamanho do avatar nas configurações, **então** a janela do tradutor é redimensionada sem travar a reprodução.

---

#### História de Usuário 4 (Referente ao Caso de Uso 02)
*   **Como** estudante com baixa visão,
*   **Quero** alterar o contraste e o tamanho da fonte dos textos da plataforma,
*   **Para que** eu possa ler os conteúdos didáticos com maior conforto visual.

**Critérios de Aceitação:**
1.  **Dado que** o usuário está nas configurações de acessibilidade, **quando** ele seleciona o modo "Alto Contraste", **então** o fundo da tela muda para preto e as letras para branco.
2.  **Dado que** o texto está visível, **quando** o usuário clica no botão de aumentar fonte ($+$), **então** o tamanho do texto aumenta em $20\%$ a cada clique.
3.  **Dado que** as preferências foram alteradas, **quando** o aluno faz logout e entra novamente na plataforma, **então** as configurações de acessibilidade salvas são mantidas.


# BaseFixer Plugin by Pitu

O **BaseFixer** é um plugin customizável para servidores Rust, projetado para simplificar o reparo de estruturas enquanto otimiza o desempenho do servidor.

---

## Key Features

### Customizable Command Activation
- Configure o comando para ativar o plugin via o arquivo de configuração.

### Configurable Messages and Colors
- Personalize todas as mensagens exibidas no jogo e suas cores.

### Flexible Repair Material Configuration
- Escolha quais materiais são necessários para reparos:
  - **Wood**
  - **Stone**
  - **Metal Fragments** (padrão)
  - **High-Quality Metal** (padrão)

### Permission System
- **Permissões Disponíveis**:
  - `basefixer.use`: Necessária para usar o comando.
  - `basefixer.noplayertax`: Isenta os jogadores da necessidade de materiais.

---

## Performance Optimizations

### Dynamic Batching
- Ajusta dinamicamente a quantidade de entidades processadas por segundo com base na carga do servidor.

### Rate Limiting
- Controla o número de comandos de reparo simultâneos para reduzir o impacto no servidor.

### Asynchronous Processing
- Desloca tarefas intensivas para threads assíncronas, melhorando o desempenho do servidor.

---

## Configuration Options

O plugin oferece diversas opções de configuração para se adequar às necessidades do seu servidor:

1. **Entities Per Second**:
   - Define o número de entidades processadas por segundo.
2. **Damage Repair Cooldown**:
   - Tempo de cooldown entre comandos de reparo.
3. **Repair Cost Multiplier**:
   - Multiplicador para o custo de materiais de reparo.
4. **Global Repair Limit**:
   - Limite máximo de entidades reparadas de uma vez.
5. **Command**:
   - Comando para ativar o plugin (padrão: `/br`).
6. **Messages**:
   - Mensagens customizáveis para diferentes estados do plugin.
7. **Repair Materials**:
   - Materiais necessários para reparos:
     - Wood
     - Stone
     - Metal Fragments
     - High-Quality Metal

---

Este plugin é altamente configurável e ideal para servidores que buscam manter um equilíbrio entre funcionalidade e desempenho. Faça ajustes no arquivo de configuração para aproveitar ao máximo o BaseFixer!


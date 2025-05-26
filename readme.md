# S.O. 2025.1 - Atividade 02 - Introdução a Linux usando Docker no Windows

## Informações Gerais
- **Disciplina**: Sistemas Operacionais (TADS/IFRN)  
- **Professor**: Leonardo A. Minora  
- **Aluno**: Gustavo Henrique da Cruz Maciel 
- **Matrícula**: 20232014040003
---

## 1. Introdução
Nesta atividade, explorei os fundamentos do Linux através de um contêiner Docker com Fedora, praticando:
- Navegação em diretórios  
- Manipulação de arquivos  
- Gerenciamento de pacotes  
- Controle de permissões e processos  

---

## 2. Relato das Atividades

### 2.1 Inicialização do Contêiner
![Captura de tela 2025-05-26 195947](https://github.com/user-attachments/assets/37e1bd09-8288-4848-aa1d-be9e50a6c8e7)

### 2.2 Navegação Básica
![Captura de tela 2025-05-26 200358](https://github.com/user-attachments/assets/26fe0e58-0b30-45fe-90d0-440abff907cf)

### 2.3 Manipulação de Arquivos
![Captura de tela 2025-05-26 200501](https://github.com/user-attachments/assets/35a258d7-9c15-4319-91ca-aa45803ad28e)

### 2.4 Gerenciamento de Pacotes
![Captura de tela 2025-05-26 200521](https://github.com/user-attachments/assets/cdb173e8-4ed8-447f-876e-24d74e434d7a)

### 2.5 Permissões de Arquivos
![Captura de tela 2025-05-26 200553](https://github.com/user-attachments/assets/dade4a33-e507-4aba-98ce-afb989017f40)

### 2.6 Gerenciamento de Processos
![Captura de tela 2025-05-26 200624](https://github.com/user-attachments/assets/5c6eb66b-fba0-447f-805a-299460105747)

### 2.7 Encerramento
![Captura de tela 2025-05-26 200642](https://github.com/user-attachments/assets/b2b1a59b-eff1-434c-aa15-1f133522a2ff)

## 3. Conclusão e Reflexões

### **Resultados Alcançados**
| Habilidade | Aprendizado |
|------------|-------------|
| **Comandos básicos** | Dominei `ls`, `cd`, `mkdir`, `cp/mv/rm` para navegação e manipulação de arquivos |
| **Gerenciamento de pacotes** | Aprendi a usar `dnf install/remove` para controle de software |
| **Permissões** | Entendi como `chmod` altera permissões de execução (ex: `u+x`) |
| **Docker** | Executei meu primeiro contêiner Linux no Windows sem instalação direta |

### **Desafios Encontrados**
```bash
# Problema mais significativo:
ps aux | grep sleep  # Falhou porque o pacote 'procps' não estava instalado
```
### Lições Aprendidas
1. Verificação de pacotes:
- Sempre conferir se ferramentas essenciais estão instaladas (ps, top, etc.)

2. Boas práticas:
- Usar tree para visualizar estrutura de pastas

3. Documentar comandos em um arquivo .txt para referência futura
Erros comuns:
- Digitar chmod utx em vez de u+x (atenção à sintaxe!)

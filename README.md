# 🐧 Linux Scripts - Protheus

🚀 **Repositório com scripts para administração do ambiente Protheus em Linux**

Este repositório contém **scripts shell** para tarefas de **backup**, **atualização**, **limpeza** e **manutenção** de ambientes **TOTVS Protheus**, organizados de forma padronizada para facilitar o uso, versionamento e histórico de mudanças.

---

## 📂 Estrutura

| Script                                   | Descrição                                                   |
|------------------------------------------|-------------------------------------------------------------|
| `protheus_backup_application`            | Realiza backup completo da aplicação                        |
| `protheus_backup_download`               | Realiza backup da aplicação e disponibiliza na pasta downloads |
| `protheus_clean_server`                  | Limpa arquivos temporários ou desnecessários do servidor    |
| `protheus_remove_ctree`                  | Remove o CTREE Server                                       |
| `protheus_update_artefacts`              | Atualiza artefatos (AppServer, WebApp, tlpp, etc.)          |
| `protheus_update_dbaccess`               | Atualiza DBACCESS e dbapi.dll                               |
| `protheus_update_pdfprinter_2410`        | Atualiza PDFPrinter na release 2410                         |
| `protheus_update_printer_2410`           | Atualiza printer unificado na release 2410                  |
| `protheus_update_printer_pdfprinter_2310` | Atualiza printer e PDFPrinter em releases inferiores        |
| `protheus_update_webmonitor`             | Atualiza e configura o WebMonitor                           |

---

## ⚙️ Padrão de Nomenclatura

Todos os scripts seguem o padrão:

protheus_<ação><alvo><release>

- **Ação:** `backup`, `update`, `clean`, `remove`...
- **Alvo:** aplicação, módulo ou componente.
- **Release:** opcional, quando aplicável (ex.: `2410`, `2310`).

---

## 📌 Como usar

1. Clone o repositório:
   ```bash
   git clone https://github.com/SEU-USUARIO/linux-scripts.git
   cd linux-scripts

Execute:

./protheus_backup_application.sh

⚠️ Atenção: execute como usuário adequado e revise permissões antes de rodar scripts em produção.

## 🗂️ Boas práticas

✅ Mantenha os scripts atualizados.

✅ Padronize novos nomes.

✅ Crie branches para mudanças maiores.

✅ Use mensagens de commit claras.

✅ Se necessário, adicione data ou autor no cabeçalho do script.

## 👨‍💻 Autor
Pedro Cocis

Técnico de Serviços Cloud • TOTVS & Protheus Lover

LinkedIn • pedro.cocis@totvs.com.br

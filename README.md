# Olá, eu sou o Hallisson! 👋

Estudante de **ADS (Análise e Desenvolvimento de Sistemas)** na Anhanguera e desenvolvedor Python especializado em **RPA** para automação de rotinas fiscais no Windows.

## 🚀 Sobre mim
- 🔭 Atualmente trabalhando em automações fiscais (REINF, DCTFWEB, SPED, ICMS, IRRF)
- 🛠️ Construo RPAs desktop com **pyautogui, pywinauto e Win32 API**
- 📄 Extração e geração de dados com **pdfplumber** e **openpyxl**
- 🖥️ Interfaces de controle com **Tkinter**

- [LinkedIn](https://www.linkedin.com/in/hallisson-edu-30697a426/)
- [hallissonedu08@gmail.com](mailto:hallissonedu08@gmail.com)

## 💻 Minhas Ferramentas e Tecnologias
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Windows](https://img.shields.io/badge/windows-0078D6?style=for-the-badge&logo=windows&logoColor=white)
![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)
![MySQL](https://img.shields.io/badge/mysql-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Linux](https://img.shields.io/badge/linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)




## 🤖 Projetos em Destaque

### 🔹 RPA REINF/DCTFWEB — Alterdata Fiscal
Automação completa do fluxo de apuração REINF/DCTFWEB no Alterdata Fiscal, com roteamento PF/PJ, regras fiscais de IRRF centralizadas e lógica de retry para falhas de interface. Arquitetura com injeção de dependência (DatabaseManager, ExcelFormatter, GoogleDriveManager). Validado contra planilha de referência com 130 registros consolidados.

### 🔹 RPA EFD Contribuições (SPED)
Pipeline de 9 módulos para processamento em lote de arquivos SPED (1 a 10 por execução), com reinício automático e retry em caso de falha. Inclui geração de arquivos EFD "sem movimento" via formulário Tkinter. **Em produção.**

### 🔹 RPA PDF → Excel (ICMS)
Pipeline de 9 módulos, com arquitetura produtor-consumidor via threading, que monitora pastas em busca de guias de ICMS em PDF, extrai números de NF e valores principais, e grava os dados em seções organizadas de Excel (DIFERENCIAL, ANTECIPADO, SUBSTITUIÇÃO, FCP).

### 🔹 RPA_Alterdata_NotasF — Automação via Win32 API
Toolkit de automação de baixo nível para o Alterdata (aplicação Delphi/DevExpress), usando Win32 API para contornar limitações de foco e detecção de componentes de hover, incluindo scripts de diagnóstico de UI via `EnumChildWindows` e `WindowFromPoint`. **Em produção.**



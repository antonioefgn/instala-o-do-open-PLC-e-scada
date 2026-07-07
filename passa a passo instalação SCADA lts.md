# 📥 Instalação do SCADA-LTS no Windows

Este tutorial descreve o passo a passo para instalar o **SCADA-LTS** no Windows.

---

##  1 - Pré-requisitos

- Sistema operacional: Windows 10 ou 11
- [Java Development Kit (JDK))](https://aka.ms/download-jdk/microsoft-jdk-11.0.18-windows-x64.msi) instalado
- Necessário estar utilizando o usuário Administrador

---

## 2 - Instalação JDK

1 - Baixe o Java Development Kit disponibilizado acima
2 - Execute e siga os passos clicando em "Next", conforme a figura abaixo:

<img width="493" height="382" alt="instalacao_jdk_00" src="https://github.com/user-attachments/assets/19efbaa0-00a5-475d-84b5-154d622840a2" />


3 - SIga a atualização até essa janela, marque para instalar no disco local a opção referente a **"Set JAVA_HOME variable"**  conforme a figura abaixo:

<img width="490" height="382" alt="instalacao_jdk_01" src="https://github.com/user-attachments/assets/d16dbe0a-7832-4fce-bfc3-471de253cc40" />




------

##  3 - Download do SCADA-LTS

1. Acesse o site oficial do SCADA-LTS: [https://github.com/SCADA-LTS/windows-installer/releases](https://github.com/SCADA-LTS/windows-installer/releases)
2. Baixe a versão disponibilizada no repositório (a versão testada e utilizada no curso será a **2.7.8.1**)

<img width="910" height="674" alt="instalacao_scadalts_00" src="https://github.com/user-attachments/assets/3ab88244-93d1-49b6-ba7f-471f0ee2d218" />


3 - Execute o arquivo siga a instalação normalmente.

<img width="488" height="383" alt="instalacao_scadalts_01" src="https://github.com/user-attachments/assets/2153bf8b-a71c-4d43-b7fa-5e4a3d2adc8a" />


4 - Na página de configuração do Tomcat durante a instalação, deixe da seguinte forma:

<img width="491" height="385" alt="instalacao_scadalts_02" src="https://github.com/user-attachments/assets/a619c20b-0331-43a1-9cb2-aeea536b0f03" />


5 - Na página de configuração do MySQL Server, marque a opção de instalar em um servidor local, a configuração ficará dessa forma:

<img width="482" height="377" alt="instalacao_scadalts_03" src="https://github.com/user-attachments/assets/4910c0a7-aaf9-4ec6-80a2-0e4a3ac58a99" />


6 - Após a instalação, na área de trabalho será criado três atalhos, dois para ligar e desligar o servidor SCADA e o atalho para abrir a interface do SCADA. Porém, o link por padrão no navegador é **http://localhost:8080/Scada-LTS**

------

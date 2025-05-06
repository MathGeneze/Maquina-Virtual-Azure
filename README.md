# Projeto Azure - Criação e Configuração de uma Máquina Virtual

<!----------- Introdução ---------->
## 📌 Introdução
Este repositório faz parte de um desafio prático na plataforma de ensino **DIO** durante o **Bootcamp XP - Cloud com IA**, onde o intuito é auxiliar o processo de **Criação** e **Configuração** de uma **Máquina Virtual (VM)** através da plataforma **Microsoft Azure**.           

Abaixo você encontrará Resumos, Anotações e Dicas para melhor aprendizado e futuras aplicações na Azure.

<!----------- Sumário ---------->
## <a id="sumario">📃 Sumário</a>
- [🌐 O que é o Microsoft Azure?](#o-que-é-o-microsoft-azure)
- [☁️ Passo a Passo: Criando uma Máquina Virtual](#passo-a-passo-criando-uma-máquina-virtual)
- [📈 Dicas Importantes](#dicas-importantes)
- [💡 Conclusão do Projeto](#conclusão-do-projeto)

<!----------- O que é o Microsoft Azure? ---------->
## <a id="o-que-é-o-microsoft-azure">🌐 O que é o Microsoft Azure?</a>
Azure é a plataforma de computação em nuvem da Microsoft que oferece uma ampla variedade de serviços com alta escalabilidade, incluindo Máquinas Virtuais, Armazenamento, Análise, Rede e Inteligência Artificial (IA).

Destaques da plataforma:

* Infraestrutura como Serviço (IaaS)
* Plataforma como Serviço (PaaS)
* Integração com ferramentas de DevOps
* Recursos avançados de segurança e conformidade

## <a id="passo-a-passo-criando-uma-máquina-virtual">☁️ Passo a Passo: Criando uma Máquina Virtual</a>
1. Acesse o **Portal Azure** 
   * Site: https://portal.azure.com

2. Clique no Ícone *"Máquinas Virtuais"*  
   * **Criar > Máquina Virtual do Azure**
   * 
  <img src="https://github.com/user-attachments/assets/f5694bfe-3472-4159-b6ed-28bedb784324" width="430"/>

3. Definindo as configurações da Máquina Virtual
    * Nome da VM (Ex: `vm-projeto-dados`);
    * Localização (Ex: Brazil South);
    * Sistema Operacional (Ex: Ubuntu Server 24.04 LTS);
    * Configuração de Hardware (Ex: Standard D2s)

5. Método de Autenticação  
   * Escolher entre **senha** ou **chave SSH** (Ideal para VM's Linux).
  
6. Revisão  
   * Revise todas as configurações definidas *(nome, localização, etc.)*. Se estiver tudo correto, clique em **"Criar"** para iniciar a implantação da VM.

<!----------- Dicas importantes ---------->
## <a id="dicas-importantes">📈 Dicas Importantes</a>
* Mantenha o produto simples e fácil de usar desde o início.
* Utilize sempre regiões próximas ao seu usuário para melhor experiência
* Pare qualquer processo quando não estiver em uso para evitar custos.

<!----------- Conclusão do Projeto ---------->
## <a id="conclusão-do-projeto">💡 Conclusão do Projeto</a>
A prática de criação e configuração de uma Máquina Virtual no Azure foi essencial para consolidar os conhecimentos sobre infraestrutura em nuvem. Foi possível entender, na prática, como provisionar recursos, aplicar configurações corretas e utilizar boas práticas para garantir desempenho e segurança no ambiente virtualizado.

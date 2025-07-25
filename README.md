## *Playbook de Ansible* para Instalação e Configuração do cliente *Certbot*

Como forma de promover a adopção da utilização do protocolo **ACME** na comunidade **RCTS**, a **FCCN** disponibiliza um pacote de *Ansible* que permite instalar e configurar um **cliente de ACME** para servidores *Linux*, especificamente o cliente [**certbot**](https://certbot.eff.org/).

### 1. Documentação playbook de *Ansible*

Um elemento essencial para a utilização do processo de gestão automática de certificados é a existência de contas ACME, neste caso na entidade certificadora (CA) da *HARICA*.

#### 1.1. FCCN
A gestão interna destas contas, nomeadamente a sua criação, alteração ou remoção é da responsabilidade do grupo **SID** da **Área ASR**.

**Assim, e para a utilização do procedimento implementado no *playbook*, é essencial o pedido de uma conta ACME da *HARICA*.**

Os passos a serem seguidos para o pedido de uma dessas contas encontram-se disponíveis na Secção [Pacote de ACME FCCN - Pré-Requisitos](https://share.fccn.pt/sites/rctscertificados/ACME/acme_internal_fccn/#page-toc-11).

#### 1.2. Outras Instituições RCTS

[Documentação para as Instituições](https://share.fccn.pt/sites/rctscertificados/ACME/acme).

# Homelab

Meu laboratório pessoal de infraestrutura e redes.

Este projeto foi criado para estudar e praticar conceitos de:

- Redes
- Linux
- Virtualização
- Docker
- Armazenamento
- Serviços self-hosted
- Segurança e acesso remoto

## Ambiente atual

Meu homelab utiliza o **Proxmox** como plataforma principal de virtualização.

Atualmente, o ambiente possui máquinas virtuais e serviços organizados da seguinte maneira:


Hardware
   │
   ▼
Proxmox
   │
   ├── Home Assistant
   │
   ├── OpenMediaVault
   │      │
   │      └── Docker
   │             │
   │             └── Nextcloud
   │
   └── Tailscale
```

### Serviços

- **Proxmox** — plataforma principal de virtualização
- **Home Assistant** — automação residencial
- **OpenMediaVault** — gerenciamento de armazenamento e serviços
- **Docker** — execução de containers dentro do OpenMediaVault
- **Nextcloud** — serviço de armazenamento e sincronização de arquivos
- **Tailscale** — acesso remoto ao ambiente

## Estrutura do ambiente

O **Proxmox** é responsável pela virtualização do laboratório.

Dentro do Proxmox são executados o **Home Assistant**, o **OpenMediaVault** e o **Tailscale**.

O **Nextcloud** é executado em um container Docker que está hospedado dentro do OpenMediaVault.

A estrutura principal é:

```text
Proxmox
│
├── Home Assistant
│
├── OpenMediaVault
│      │
│      └── Docker
│             │
│             └── Nextcloud
│
└── Tailscale
```

## Objetivos

- Aprender infraestrutura de redes na prática
- Aprofundar meus conhecimentos em Linux
- Estudar virtualização e containers
- Aprender Docker
- Estudar armazenamento e gerenciamento de servidores
- Aprender conceitos de segurança e acesso remoto
- Documentar problemas, soluções e configurações
- Construir experiência prática através de projetos

## Projetos

A documentação dos componentes do laboratório será organizada em seções próprias.

- [Proxmox](./proxmox/)
- Networking *(em desenvolvimento)*
- Docker *(em desenvolvimento)*
- Nextcloud *(em desenvolvimento)*
- Tailscale *(em desenvolvimento)*

---

Este laboratório está em constante evolução e será utilizado como ambiente de estudos e prática em infraestrutura, redes e administração de sistemas.

# Projeto de Redes - Cisco Packet Tracer

## Descrição

Este projeto simula uma infraestrutura de rede corporativa utilizando o Cisco Packet Tracer.

A topologia foi desenvolvida com múltiplas redes locais interligadas por roteadores Cisco 2911, permitindo comunicação entre diferentes segmentos da rede.

O projeto também possui um servidor central responsável pelo serviço de DNS para todos os computadores da infraestrutura.

---

##IMAGEM DO PROJETO

<img width="1573" height="843" alt="image" src="https://github.com/user-attachments/assets/9a153d30-48c1-4b1e-99b5-3b822288d664" />

## Objetivos do Projeto

- Simular uma rede corporativa
- Configurar roteamento entre redes
- Implementar serviço DNS centralizado
- Permitir comunicação entre todas as LANs
- Realizar testes de conectividade

---

## Estrutura da Rede

### Redes Utilizadas

| Rede | Gateway |
|------|----------|
| 192.168.10.0/24 | 192.168.10.1 |
| 192.168.20.0/24 | 192.168.20.1 |
| 192.168.30.0/24 | 192.168.30.1 |
| 192.168.40.0/24 | 192.168.40.1 |

### Redes Entre Roteadores

| Rede |
|------|
| 192.168.50.0 |
| 192.168.60.0 |
| 192.168.70.0 |
| 192.168.80.0 |

---

## Equipamentos Utilizados

- Roteadores Cisco 2911
- Switches Cisco 2950T-24
- PCs clientes
- Servidor DNS

---

## Serviço DNS

O servidor foi configurado para fornecer resolução de nomes para todos os computadores da rede.

Todos os PCs utilizam o DNS configurado no servidor central.

---

## Funcionalidades Implementadas

- Comunicação entre diferentes redes
- Roteamento entre roteadores
- Configuração de gateways
- Serviço DNS centralizado
- Testes de ping entre redes
- Estrutura hierárquica de rede

---

## Testes Realizados

- Ping entre PCs de redes diferentes
- Comunicação com o servidor
- Resolução DNS em todas as redes
- Verificação de conectividade entre roteadores

---

## Como Executar

1. Abra o arquivo `.pkt` no Cisco Packet Tracer
2. Aguarde a inicialização dos dispositivos
3. Utilize os PCs para realizar testes:
   - `ping`
   - acesso por nome DNS
4. Verifique o funcionamento do servidor DNS

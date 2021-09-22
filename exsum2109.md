## Team Automation

---

## Obbiettivi raggiunti 2021

---

<!-- .slide: style="text-align: left;"> -->
#### Dismissione automazione Ansible_v1
  - dismissione infrastruttura AWX
  - refactoring e porting dei servizi sotto la nuova infrastruttura di Ansible_v2

---

<!-- .slide: style="text-align: left;"> -->
#### Automazione
  - provisioning monitoraggio VM su Neteye4
  - provisioning (PSP) del layer RETE VM (NSX, VLAN, IP, DNS)
    - statico sulle tipologie oggi a catalogo (e.g. dietro balancer, standalone)
  - provisioning (PSP) del layer STORAGE VM
    - dinamico via label (e.g. gold, silver, bronze)

---

<!-- .slide: style="text-align: left;"> -->
Automazione via PSP dei processi di OPS su una VM
  - gestione FS
  - gestione FW

---
### CMDB

---

Definizione Entità/Relazione Servizio

![q](img/swimlaneOBPfase1.png)

---

<!-- .slide: style="text-align: left;"> -->
- Autodiscovery layer VM (esempio storage, ram, cpu, rete)
- Integrazione dei processi di reportistica:
  - e.g. stato aggiornamento server

---

## Provisioning a Catalogo

---

<!-- .slide: style="text-align: left;"> -->
- Building Block: VM, apache, tomcat, solr, zookeeper, certificati TLS
- Servizi: u-buy, idp, oracle, mysql, confluence, unifind

---

<!-- .slide: style="text-align: left;"> -->
Deliverables in Q4:
  - in progress: esse3-web
  - attesa validazione cliente: titulus, conserva

---

## Provisioning NON a Catalogo

---

<!-- .slide: style="text-align: left;"> -->
Definita la modalità operativa gestito tramite BB di Servizi
(e.g. cinwaf, metadataprovider, bestr, codau)
  - integrazione con CMDB
  - configurazioni e codice tracciato/versionato
    - https://gitlab.cineca.it/cineca-norole

---

## Operation Management

---

<!-- .slide: style="text-align: left;"> -->
Gestione dell'infrastruttura di Automazione: evolutive, aggiornamenti, fix
  - Portale di SelfService Provisioning (PSP): https://psp-console.cineca.it/dashboard
  - Automation Platform: Ansible Tower - https://ansible-tower-web-svc-tower-prod.ose.private.cineca.it
  - CMDB: NetBox - https://netbox.private.cineca.it/

---

<!-- .slide: style="text-align: left;"> -->
Gestione (implementazione, evolutive, bugfix) del codice ansible e python dell'automazione
  - https://gitlab.cineca.it/cineca-galaxy
  - https://gitlab.cineca.it/cineca-playbook
  - https://gitlab.cineca.it/ansible-utils

---

### Alcuni numeri

---

<!-- .slide: style="text-align: left;"> -->
- Effort Team: 1,5FTE/anno
- VMs gestite: 600
- Instance Type gestite: 800
  - VH apache, tomcat, solr, zookepper, oracle, mysql

---

## NEXT

---

<!-- .slide: style="text-align: left;"> -->
Automazione via PSP dei processi di OPS su una VM
  - gestione FS
  - gestione FW
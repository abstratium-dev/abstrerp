# TODO

These TODOs are to be resolved by the developer, NOT THE LLM.

## Today

- sign up for new account in abstrauth, with automatic creation of roles that is valid over all microservices, which says that you are a registered user, but with no other particular roles

## Tomorrow


## Later (not yet necessary for initial release)


## Other microservices

- [ ] abstraprint: templating and printing and archiving of documents
      - CALL IT abstradocs? in README.md it talks about abstraoutput? is one of them already in the master port file?
- [ ] abstrapay: payment processing
  - encapsulates stripe, etc.
  - creates receipts using abstraprint
  - creates invoices using abstraprint
- [X] abstrapact: contract management, sales processes and products
  - encapsulates sales processes for products. encapsulates products too since the basis of any contract is a product.
- [X] abstoggle: feature toggle service
  - e.g. master toggle for all b2c UIs
- [X] abstrerp: this repo with docs and docker compose files and shared scripts, etc.
- [X] abstraccount: double entry book keeping
- [X] abstrasst: AI assistant
- [X] abstradex: CRM
- [X] abstrauth: authentication and authorization
- [X] abstracore: the framework and base of all microservices
- product uis
  - [X] abstracertification
    - uses abstraprint to create certification documents
  - ... others e.g. kdg or using things like abstraccount
- [ ] grafana et al. for monitoring and alerting
  - can we use that to monitor the health of the system and alert if services aren't available?


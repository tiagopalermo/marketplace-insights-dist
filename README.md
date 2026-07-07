# marketplace-insights-dist

Repositório de **distribuição** da extensão Marketplace Insights.

Contém **apenas os artefatos empacotados** — nunca o código-fonte:

- `updates.xml` — manifesto de atualização (o Chrome consulta este arquivo)
- `buscai-vX.Y.Z.crx` — instalador assinado da extensão

O código-fonte fica em repositório **privado** separado. Estes artefatos são publicados automaticamente pelo script de release (`release.ps1`) a cada nova versão.

> Instalação e auto-update são configurados via política do Chrome (`setup.reg`) — solicite ao responsável.

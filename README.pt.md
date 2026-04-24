# EnvStudio Feedback

<p align="right">
  <a href="README.md">English (US)</a>
  |
  <a href="README.zh-Hans.md">简体中文</a>
  |
  <a href="README.zh-Hant.md">繁體中文</a>
  |
  <a href="README.ja.md">日本語</a>
  |
  <a href="README.de.md">Deutsch</a>
  |
  <a href="README.fr.md">Français</a>
  |
  <a href="README.es.md">Español</a>
  |
  <a href="README.ru.md">Русский</a>
  |
  <a href="README.ko.md">한국어</a>
</p>

## Sobre o EnvStudio

O **EnvStudio** é um gerenciador moderno de variáveis de ambiente do Windows baseado em WinUI 3. Ele substitui o antigo diálogo "Propriedades do Sistema → Variáveis de Ambiente" por uma experiência nativa do Windows 11.

<p align="center">
  <img src="https://prunelab.net/products/envstudio/covers/pt/cover1.png" width="48%" />
  <img src="https://prunelab.net/products/envstudio/covers/pt/cover2.png" width="48%" />
</p>

## Baixar

<p>
  <a href="https://apps.microsoft.com/detail/9nl5scxw3320" target="_blank">
    <img src="https://get.microsoft.com/images/en-us%20dark.svg" width="200" alt="Download from Microsoft Store"/>
  </a>
</p>

## Principais funcionalidades

- **Editor visual intuitivo** — Adicione, edite, exclua e reordene variáveis de ambiente com uma interface WinUI 3 moderna.
- **Gerenciamento de lista PATH** — Reordenação com arrastar e soltar, detecção de duplicatas e de links quebrados.
- **Detecção de conflitos EXE** — Escaneia todos os diretórios do PATH em busca de executáveis e mostra quais são sobrescritos por entradas anteriores, com um clique para pular para a entrada conflitante.
- **Detecção de conflitos de escopo** — Quando uma variável de usuário oculta uma variável de sistema com o mesmo nome, mostra um tachado com ícone de aviso para que você sempre saiba qual valor está realmente em vigor.
- **Alternância não destrutiva** — Desative uma variável sem excluí-la. Renomeia silenciosamente o valor do registro preservando os dados originais. Reative a qualquer momento com um clique.
- **Verificações de segurança ao excluir** — Antes de excluir uma variável, escaneia todas as outras variáveis em busca de referências `%VARNAME%` e avisa sobre possíveis quebras.
- **Pré-visualização de expansão** — Passe o mouse sobre qualquer valor contendo referências `%VAR%` para ver o caminho totalmente resolvido em um tooltip.
- **Detecção de mudanças externas** — Monitora o registro em tempo real. Se outro programa modificar variáveis de ambiente enquanto o EnvStudio está aberto, você recebe uma notificação imediata.
- **Sistema de perfis** — Salve, troque e aplique perfis de variáveis para diferentes ambientes de desenvolvimento (ex. "Java 8", "Node.js", "AI/ML").
- **Snapshot e reversão** — Snapshots automáticos antes de cada alteração, com visualização diff estilo Git e reversão em um clique.
- **Busca e filtro** — Encontre rapidamente variáveis entre os escopos de Usuário e Sistema com suporte a regex. Subentradas PATH correspondentes são automaticamente expandidas com um badge de contagem.
- **Exportação** — Exporte variáveis para formatos PowerShell, Batch ou arquivo .env para compartilhar com sua equipe ou restaurar após uma reinstalação.
- **Elevação UAC** — Elevação de administrador transparente para editar variáveis do Sistema.
- **Transmissão instantânea** — Alterações são imediatamente transmitidas ao sistema via `WM_SETTINGCHANGE`.

## 100% Offline · Totalmente gratuito

O EnvStudio opera **totalmente offline, sem telemetria ou coleta de dados.** Sua configuração de ambiente permanece estritamente na sua própria máquina.

Todas as funcionalidades são **totalmente gratuitas**, sem anúncios ou paywalls. Uma opção de doação poderá ser adicionada no futuro, mas nenhuma funcionalidade será restrita.

Consulte nossa [Política de Privacidade](https://prunelab.net/pt/products/envstudio/privacy) para mais detalhes.

---

## Feedback

> **Nota:** Este repositório **não contém** o código fonte do EnvStudio. Ele é dedicado à coleta de feedback dos usuários e ao rastreamento de problemas.

| Ação | Link |
|------|------|
| Reportar um bug | [Criar relatório de bug](https://github.com/PruneLab/EnvStudio-Feedback/issues/new?template=bug_report.yml) |
| Sugerir funcionalidade | [Enviar solicitação](https://github.com/PruneLab/EnvStudio-Feedback/issues/new?template=feature_request.yml) |
| Ver todos os Issues | [Issues](https://github.com/PruneLab/EnvStudio-Feedback/issues) |

## Antes de reportar

Pesquise primeiro os [Issues existentes](https://github.com/PruneLab/EnvStudio-Feedback/issues) para evitar duplicatas.

Ao relatar um bug, inclua:
- **Versão do EnvStudio** (em Configurações → Sobre)
- **Versão do Windows** (ex. Windows 11 23H2)
- **Passos para reproduzir** o problema
- **Comportamento esperado** vs **comportamento real**
- Capturas de tela (se aplicável)

## Ideias de funcionalidades

Adoramos ouvir suas ideias! Antes de enviar:
- Verifique se alguém já sugeriu
- Descreva o caso de uso — que problema isso resolveria?
- Mockups ou referências são sempre bem-vindos

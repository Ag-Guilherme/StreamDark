# StreamDark
StreamDark — Plataforma de Streaming
O que é
O StreamDark é uma plataforma web de streaming com visual escuro (estilo YouTube dark mode) que permite centralizar, organizar e reproduzir vídeos de diversas fontes em um único lugar. Tudo funciona localmente no navegador, sem necessidade de servidor.
Funcionamento por Tópicos
1. Visual e Interface
Design totalmente escuro com acentos em vermelho
Layout responsivo que funciona em desktop, tablet e celular
Navegação por abas: Todos, Filmes, Séries, Clips e Favoritos
Grid de cards com thumbnails automáticas (para YouTube)
2. Fontes de Vídeo Suportadas
YouTube — basta colar o link, o sistema extrai o ID automaticamente e gera a thumbnail
Google Drive — colar o link do arquivo, o sistema incorpora o player do Drive
Links Diretos — qualquer URL direta de vídeo (.mp4, .webm, .m3u8, etc.)
3. Painel Administrativo (Protegido por Senha)
Senha padrão: admin123
Acessado pelo botão "Admin" no canto superior direito
Permite adicionar, visualizar e excluir vídeos
Mostra estatísticas (total de vídeos, por fonte, favoritos)
Busca rápida entre todos os vídeos cadastrados
Exportar e importar backup completo em JSON
4. Player Integrado
Reproduz vídeos do YouTube via embed oficial
Reproduz arquivos do Google Drive via preview
Reproduz links diretos via tag <video> nativa
Suporte a streams HLS (.m3u8) via hls.js
Painel lateral com vídeos relacionados
Botões de favoritar e copiar link
5. Sistema de Favoritos
Qualquer vídeo pode ser marcado como favorito
Aba dedicada "Favoritos" na navegação principal
Salvos no localStorage do navegador
6. Categorias
Filmes, Séries, Clips, Geral
Cada vídeo é classificado em uma categoria ao ser adicionado
Filtro rápido por abas no topo
7. Persistência de Dados
Todos os dados são salvos no localStorage do navegador
Não precisa de banco de dados ou servidor
Backup exportável/importável em formato JSON
8. Adição de Conteúdo
Pelo botão Admin → + Adicionar (painel completo)
Ou pelo modal rápido (se disponível)
Suporte a YouTube, Google Drive e links diretos
Resumo Rápido
Recurso
Detalhes
Senha Admin
admin123
Fontes
YouTube, Google Drive, Links Diretos
Categorias
Filmes, Séries, Clips, Geral
Armazenamento
localStorage (navegador)
Backup
Exportar/Importar JSON
Player
Embed + HLS.js
Servidor
Não precisa — tudo roda no navegador

# FILE:README.md

# App para a radio Brazilian Waves

Este é um Progressive Web App (PWA) simples que criei para ouvir a rádio **Brazilian Waves** no celular. A motivação principal foi a necessidade de um player funcional e minimalista, que tentasse se reconectar automaticamente caso a conexão fosse interrompida.

## Por que criei este app?

Ao ouvir a webradio enquanto dirigia, percebi que, quando a conexão caía, era necessário clicar novamente no botão de play. Inconveniente e inseguro (até porque o botão, no site, é bem pequeno). Este app resolve esse problema.

# Funcionalidades

- Reproduz a rádio de forma simples e direta (como PWA o autoplay funciona assim que abre-se o app);
- Tenta reconectar automaticamente quando a conexão cai.

# Problemas

Está bem simples. Não tem um fallback para uso no navegador (que bloqueia o autoplay). JS não é minha praia e não consegui fazer funcionar a mudança do botão quando está tentando reconectar. Mas serve ao propósito.

# Direitos

Fiz esse webapp para uso pessoal. A rádio Brazilian Waves é uma webradio curitibana que gosto muito de escutar (https://brazilianwavesofsound.com/). Os dados vêm do serviço de streaming utilizado pela rádio no próprio site (https://maxcast.com.br/).
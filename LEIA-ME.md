# Estante: instalação no Samsung (Android)

O app funciona 100% offline depois de instalado. Jogos e fotos ficam guardados no próprio celular.

## Caminho recomendado: GitHub Pages + "Instalar app" (gratuito, ~10 min)

Neste caminho o Chrome gera um **WebAPK**, que é um APK de verdade: aparece na gaveta de apps, em Configurações > Aplicativos e abre em tela cheia.

1. Crie uma conta em github.com (grátis).
2. Clique em **New repository**, dê o nome `estante` e marque **Public**. Depois clique em **Create repository**.
3. Clique em **uploading an existing file** e arraste os 7 arquivos desta pasta (sem a pasta, só os arquivos). Depois clique em **Commit changes**.
4. Vá em **Settings > Pages**. Em *Branch* escolha `main` e `/ (root)` e clique em **Save**.
5. Aguarde 1 ou 2 minutos. O endereço será `https://SEU-USUARIO.github.io/estante/`.
6. No celular, abra esse endereço no **Chrome**. Toque em ⋮ e depois em **Instalar app** (ou **Adicionar à tela inicial > Instalar**).
7. Abra o app uma vez com internet. A partir daí ele funciona offline.

> O repositório público contém só o código do app. Seus jogos e fotos **nunca** saem do celular.

## Alternativa: gerar o arquivo .apk

1. Com o site do passo 5 no ar, acesse **pwabuilder.com** e cole o endereço.
2. Clique em **Package for stores**, escolha **Android** e depois **Download**.
3. O zip gerado traz um `.apk`. Copie para o celular e instale, permitindo "instalar apps desconhecidos" para o app de arquivos.

## Backup (importante)

- Em ⚙︎ use **Exportar backup**. O arquivo `.json` contém os jogos e as fotos. Salve no Google Drive ou no PC.
- Desinstalar o app ou limpar os dados do Chrome **apaga a coleção**.
- Para trocar de celular: instale o app no novo aparelho e use **Restaurar backup**.

## Observações

- A consulta ao PriceCharting abre o site e precisa de internet. Todo o resto funciona offline.
- A cotação do dólar é definida em ⚙︎ e converte os valores de US$ para R$.
- Não use o **Samsung Internet** para instalar: prefira o Chrome, que gera o WebAPK completo.

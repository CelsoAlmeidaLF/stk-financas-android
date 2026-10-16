# Finanças da Casa · página de download Android

Página estática (GitHub Pages) para baixar no celular os APKs do Finanças da Casa:

- **App completo**, Capacitor: [stk-financas-capacitor](https://github.com/CelsoAlmeidaLF/stk-financas-capacitor)
- **Piloto nativo**, Kotlin: [stk-financas-kotlin](https://github.com/CelsoAlmeidaLF/stk-financas-kotlin)

Página: https://celsoalmeidalf.github.io/stk-financas-android/

Os botões usam o link fixo `releases/latest/download/…`, então publicar uma Release nova nos repos dos apps (`scripts/publicar-apk.sh`) já atualiza o download, sem mexer aqui. A versão, o tamanho e a data são lidos da API do GitHub no navegador; se ela falhar, o link continua funcionando.

Sem build: HTML, fontes locais (Space Grotesk e IBM Plex Mono, SIL OFL 1.1) e o gerador de QR Code (MIT), que aparece só no computador para baixar apontando a câmera do celular.

## Licença

Proprietária, todos os direitos reservados. Veja [LICENSE](LICENSE).

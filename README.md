# Finanças da Casa · página de download Android

Página estática (GitHub Pages) para baixar no celular os APKs do Finanças da Casa:

- **App completo**, Capacitor: [stk-financas-capacitor](https://github.com/CelsoAlmeidaLF/stk-financas-capacitor)
- **Piloto nativo**, Kotlin: [stk-financas-kotlin](https://github.com/CelsoAlmeidaLF/stk-financas-kotlin)

Página: https://celsoalmeidalf.github.io/stk-financas-android/

Os APKs ficam em `apk/` e são servidos pela própria página, no mesmo site. Assim o download não passa pelo `github.com`: no Android, o app do GitHub pode capturar esse link e o arquivo nunca chega à pasta Downloads. `scripts/publicar-apk.sh`, nos repos dos apps, cria a Release, copia o APK para cá, atualiza `apk/versoes.json` (versão, data e tamanho) e publica a página.

Sem build: HTML, os APKs, fontes locais (Space Grotesk e IBM Plex Mono, SIL OFL 1.1) e o gerador de QR Code (MIT), que aparece só no computador para baixar apontando a câmera do celular.

## Licença

Proprietária, todos os direitos reservados. Veja [LICENSE](LICENSE).

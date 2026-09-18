# Compilar pelo celular com GitHub Actions

1. Crie um repositório no GitHub.
2. Extraia este projeto e envie **todo o conteúdo da pasta `android-wrapper`** para o repositório.
3. No GitHub, abra **Actions**.
4. Selecione **Build Farencci APK**.
5. Toque em **Run workflow**.
6. Aguarde a compilação.
7. Abra a execução concluída e baixe o artefato **Farencci-debug-apk**.
8. Dentro do artefato estará `app-debug.apk`.

O app já está configurado para carregar https://farencci.netlify.app/ em uma WebView nativa, sem barra de URL, com permissões de câmera e microfone para WebRTC.

Observação: o workflow usa uma build Debug, adequada para testes e instalação direta no Android.

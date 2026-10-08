# Gerar APK pelo celular

1. Crie um repositório no GitHub.
2. Envie os arquivos deste projeto para a raiz do repositório.
3. Faça commit na branch main.
4. Abra Actions > Build Android APK.
5. Aguarde a execução terminar.
6. Abra a execução verde e baixe o Artifact `CameraPhotoSelector-debug`.
7. Dentro dele estará `app-debug.apk`.

Importante: o arquivo gradlew precisa estar na raiz e `.github/workflows/build-apk.yml` precisa ser preservado.

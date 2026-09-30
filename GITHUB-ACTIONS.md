# ZWhisper Rebuilt — GitHub Actions

Este projeto foi preparado para gerar automaticamente um APK debug pelo GitHub Actions.

## Como gerar o APK

1. Crie um repositório no GitHub.
2. Envie **todo o conteúdo deste ZIP** para o repositório.
3. Abra a aba **Actions**.
4. Selecione **Build ZWhisper APK**.
5. Clique em **Run workflow**.
6. Quando terminar, abra a execução concluída.
7. Na seção **Artifacts**, baixe `ZWhisper-Rebuilt-debug`.
8. Extraia o ZIP baixado e instale o arquivo `.apk` no Android.

O workflow usa JDK 17 e executa `./gradlew assembleDebug`.

Observação: o workflow não contém chaves de assinatura de produção; o APK é um build debug para testes.

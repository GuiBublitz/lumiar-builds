# vigilia-builds

Builds automáticos do **Vigília**. Este repositório existe só para hospedar o APK —
o código-fonte fica em repositório privado.

Ele é público de propósito: o app baixa a atualização direto daqui, e um repositório
privado exigiria embutir um token no APK — que qualquer pessoa que baixasse o arquivo
conseguiria extrair.

## Instalar

Baixe o APK mais recente em **[Releases](../../releases/latest)** e abra no aparelho.

O app checa por atualização sozinho ao abrir. O Android sempre pede confirmação para
instalar aplicativo de fora da Play Store — isso é do sistema e não tem como contornar.

## Arquivos de cada release

| Arquivo | O que é |
|---|---|
| `vigilia.apk` | o app, IL2CPP ARM64 |
| `version.json` | manifesto que o app lê para saber se há versão nova |

O `versionCode` é a contagem de commits do repositório de código — um número que só cresce.

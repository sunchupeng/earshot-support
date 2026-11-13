# Earshot AI support

Public usage documentation and issue tracking for the proprietary Earshot / 聽懂 iPhone app. Maintained for the app's developer, Chupeng Sun. This documentation was prepared with the developer's authorized AI assistant and checked against the published app information and recorded demonstrations.

- [App Store](https://apps.apple.com/us/app/id6830550013)
- [Product website](https://earshot.chuchu1226.chatgpt.site/)
- [Japanese buying guide](https://earshot.chuchu1226.chatgpt.site/ja/)

## Requirements and purchase

Earshot requires iOS 17 or later on a compatible iPhone. The U.S. App Store price was US$4.99 as checked on November 13, 2026. Local prices vary. The app uses a one-time purchase and requires no app account, subscription or in-app purchase.

The text translation model is bundled with the app and runs on the device. Speech recognition and speech playback depend on the device, language and prepared Apple on-device language resources. Preparing those resources may require a network connection. Check the required language and mode on your device before relying on it offline.

## Regional model licence

The bundled HY model's licence excludes use in the European Union, United Kingdom and South Korea, including travel in those regions. Earshot is unavailable in those App Store regions and mainland China. Store availability and permission to use the bundled model are separate conditions.

## Import a file and keep a bilingual record

1. Choose file translation in Earshot and select a TXT file or a PDF with extractable text from the iOS Files picker.
2. Choose the source and target languages, then translate the extracted paragraphs.
3. Read the original beside the translation and check any important details.
4. Save the result in local history if you want to reopen it in the app.
5. Choose the PDF export, then use the iOS share sheet to save or share the generated document.

File limits are 6 MB per file, 80 PDF pages, 300 paragraphs and 30,000 extracted characters. Scanned-image and password-protected PDFs are unsupported. Complex original layouts are not preserved. Translation output can change meaning or add details, so verify important instructions against the original.

## Actual example and evidence boundaries

The [TXT import demonstration](https://earshot.chuchu1226.chatgpt.site/demo/#file-import) includes a fictional, AI-assisted 57-word English handoff note, its uncorrected Chinese output and the resulting bilingual PDF. It was recorded with development version 1.0.1(19) on an iOS 27 Simulator. The result was saved through the share sheet and reopened in Files. Local-history saving was checked separately after recording. This example establishes that recorded workflow in that environment. Physical-iPhone performance and general translation quality remain unverified by this demonstration.

- [Original TXT](https://earshot.chuchu1226.chatgpt.site/assets/demo/earshot-handoff-import.txt)
- [Uncorrected bilingual PDF](https://earshot.chuchu1226.chatgpt.site/assets/demo/earshot-file-import-bilingual.pdf)
- [Japanese-input example](https://earshot.chuchu1226.chatgpt.site/ja/#japanese-file-sample)

The raw English-to-Chinese output includes awkward bottle wording, added leaving instructions and lost phone-call specificity. The linked files retain those errors.

## Report a problem or request a change

[Open an issue](https://github.com/sunchupeng/earshot-support/issues/new) with your app version, iOS version, iPhone model, language pair and translation mode. For file problems, include the file type, approximate size and whether its text can be selected. Describe the steps, expected result and observed result. A short fictional or redacted example helps reproduce the problem. Public issues can be read by other people.

For speech problems, say whether the Apple on-device resources were prepared and whether the issue also occurs with typed text. The app's local translation history stays on the device. Review any example before posting it publicly.

This repository contains public documentation and support discussions. The iPhone application and bundled model retain their respective licences. Bug reports and feature requests receive individual review, with no promised response time or fix date.

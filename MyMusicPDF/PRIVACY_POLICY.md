# Privacy Policy / Política de Privacidade — MyMusicPDF

**Developer / Desenvolvedor:** Machado Digital Works (`machadodigitalworks@gmail.com`)  
**Last updated / Última atualização:** November 20, 2026 / 20 de Novembro de 2026  
**Terms of Service / Termos de Serviço:** <https://brunovam.github.io/MDW-Privacy/MyMusicPDF/terms.html>

---

## 🇧🇷 Português

### 1. Resumo e Compromisso com a Privacidade
O **MyMusicPDF** foi desenvolvido com foco prioritário na privacidade do músico:
- **Zero Coleta de Partituras ou Arquivos Pessoais:** Suas partituras em PDF, anotações vetoriais em PDF, notas de repertório em Markdown e pacotes (`.mymusicpdf`) são processados exclusivamente de forma local no seu dispositivo e nunca são enviados para servidores nossos.
- **Processamento de Áudio 100% Local:** O recurso de Afinador Cromático analisa frequências sonoras em tempo real na memória volátil (RAM) pelo algoritmo YIN e descarta o áudio instantaneamente. Não há gravação de som, armazenamento em disco ou transmissão de voz.
- **Modelo de Monetização Transparente:** O aplicativo pode ser utilizado gratuitamente com a exibição de banners de anúncios fora do palco de leitura, ou 100% sem anúncios mediante a contratação opcional da assinatura **MyMusicPDF Pro**.

### 2. Permissões Utilizadas
- **Microfone (`RECORD_AUDIO` no Android / `NSMicrophoneUsageDescription` no iOS):** Utilizado estritamente pelo Afinador Cromático para capturar a frequência acústica de notas musicais em tempo real. Nenhum áudio é gravado ou transmitido.
- **Armazenamento de Partituras PDF (Android: `READ_EXTERNAL_STORAGE` com `maxSdkVersion="32"`, `WRITE_EXTERNAL_STORAGE` com `maxSdkVersion="29"`, `MANAGE_EXTERNAL_STORAGE`; iOS: `NSDocumentsFolderUsageDescription`):** Utilizados exclusivamente para indexar pastas de partituras PDF locais, abrir PDFs externos, salvar edições/anotações nos PDFs escolhidos e importar/exportar repertórios (`.mymusicpdf`). Permissões de mídia/fotos (`READ_MEDIA_IMAGES`) não são declaradas nem utilizadas.
- **Transparência iOS (`NSUserTrackingUsageDescription` / ATT) & StoreKit:** No iOS gratuito, solicita consentimento ATT (recusa não limita recursos); assinaturas são processadas via Google Play Billing ou Apple App Store / RevenueCat.
- **Wakelock (`WAKE_LOCK`):** Evita o bloqueio ou desligamento acidental da tela durante apresentações ao vivo ou ensaios musicais.
- **Acesso à Rede e Faturamento (`INTERNET`, `com.android.vending.BILLING`):** Utilizados para exibição de anúncios no plano gratuito e processamento seguro da assinatura **MyMusicPDF Pro**.

### 3. Serviços de Terceiros e Coleta Técnica de Dados
O aplicativo não exige criação de conta nem envia dados pessoais para servidores próprios. Para viabilizar a distribuição gratuita e o gerenciamento de assinaturas, o MyMusicPDF integra:
- **Google AdMob & Google UMP SDK (Google LLC):** Exibe anúncios em formato banner na versão gratuita, com gerenciamento de consentimento GDPR/LGPD via **Google UMP** antes da inicialização do AdMob (opções revisáveis nas Configurações). O Google AdMob pode coletar identificadores técnicos do dispositivo (AAID ou IDFA mediante consentimento ATT), localização aproximada inferida por IP, interações com anúncios e dados de diagnóstico/medição para veiculação de anúncios e prevenção a fraudes, em conformidade com as [Políticas de Privacidade do Google](https://policies.google.com/privacy).
- **Google Play Billing, Apple App Store (StoreKit) & RevenueCat:** Utilizados para o processamento de compras integradas, histórico de assinaturas e validação da assinatura **MyMusicPDF Pro**. Nenhum dado de cartão de crédito é coletado ou armazenado pelo MyMusicPDF; todas as transações são intermediadas pela Google Play Store / Apple App Store e validadas de forma anônima pelo [RevenueCat](https://www.revenuecat.com/privacy).

### 4. Exclusão de Dados e Conformidade (LGPD / GDPR)
- Todos os dados de repertórios, anotações e preferências residem localmente no diretório privado protegido do SQLite (sem compartilhamento público via iOS File Sharing e sem backup automático em nuvem no Android via `allowBackup="false"`). Ao desinstalar o aplicativo, esses dados locais são eliminados automaticamente pelo sistema operacional.
- Consulte também os [Termos de Serviço](https://brunovam.github.io/MDW-Privacy/MyMusicPDF/terms.html). Dúvidas ou solicitações podem ser enviadas para: `machadodigitalworks@gmail.com`.

---

## 🇺🇸 English

### 1. Summary and Commitment to Privacy
**MyMusicPDF** is built with musician privacy as a foundational principle:
- **Zero Personal File Collection:** Your PDF sheet music, vector PDF annotations, Markdown stage notes, and setlist packages (`.mymusicpdf`) are processed strictly locally on your device and are never sent to our servers.
- **100% Local Audio Processing:** The built-in Chromatic Tuner processes acoustic frequencies in real time in volatile memory (RAM) using the YIN algorithm and discards audio instantly. No sound is ever recorded, saved to disk, or transmitted.
- **Transparent Hybrid Monetization:** The application can be used free of charge supported by non-intrusive banner ads outside the live reader, or completely ad-free via an optional **MyMusicPDF Pro** subscription.

### 2. Permissions Used
- **Microphone (`RECORD_AUDIO` on Android / `NSMicrophoneUsageDescription` on iOS):** Used exclusively by the Chromatic Tuner to calculate musical frequencies in real time. No audio is ever recorded, saved, or transmitted.
- **PDF Sheet Music Access (Android: `READ_EXTERNAL_STORAGE` capped at `maxSdkVersion="32"`, `WRITE_EXTERNAL_STORAGE` capped at `maxSdkVersion="29"`, `MANAGE_EXTERNAL_STORAGE`; iOS: `NSDocumentsFolderUsageDescription`):** Used solely to scan and index local PDF sheet music folders, open external PDFs, save annotations into selected PDFs, and import/export setlists (`.mymusicpdf`). Gallery media permissions (`READ_MEDIA_IMAGES`) are not declared or used.
- **iOS Tracking Transparency (`NSUserTrackingUsageDescription` / ATT) & StoreKit:** On iOS free-tier builds, users can allow or decline advertising tracking without losing any features; subscriptions are handled by Google Play or Apple App Store / RevenueCat.
- **Screen Wake Lock (`WAKE_LOCK`):** Keeps your screen on during live performances and rehearsal sessions.
- **Network and In-App Billing (`INTERNET`, `com.android.vending.BILLING` / StoreKit):** Used for loading banner ads in the free tier and processing the optional **MyMusicPDF Pro** subscription.

### 3. Third-Party Services, UMP Consent & Technical Data Collection
The app does not require user accounts and does not operate remote user databases. To provide free ad-supported access and subscription management, MyMusicPDF integrates:
- **Google AdMob & Google UMP SDK (Google LLC):** Serves banner ads in the free version after collecting **Google UMP** privacy consent preferences for GDPR/LGPD compliance (reviewable in Settings). Google AdMob may collect technical device identifiers (AAID or ATT-consented IDFA), approximate IP-based location, ad interactions, and performance diagnostics for ad delivery, fraud prevention, and measurement under [Google's Privacy Policy](https://policies.google.com/privacy).
- **Google Play Billing, Apple App Store (StoreKit) & RevenueCat:** Used to securely process subscriptions, purchase history, and verify the **MyMusicPDF Pro** entitlement. No payment card data is collected or stored by MyMusicPDF; all purchases are handled directly by Google Play / Apple App Store and anonymously validated by [RevenueCat](https://www.revenuecat.com/privacy).

### 4. Protected Storage, Data Deletion & Contact
- All setlists, annotations, and preferences are stored locally in the app's private SQLite directory (with iOS File Sharing and Android auto-backup disabled via `allowBackup="false"`). Uninstalling the app automatically deletes all local records via the operating system.
- Review our [Terms of Service](https://brunovam.github.io/MDW-Privacy/MyMusicPDF/terms.html). Contact **Machado Digital Works** at: `machadodigitalworks@gmail.com`.

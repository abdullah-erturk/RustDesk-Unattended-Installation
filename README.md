# RustDesk Silent Installation

![Rustdesk](https://github.com/abdullah-erturk/RustDesk-Unattended-Installation/blob/main/rustdesk.jpg)


     Türkçe Açıklama

# RustDesk Sessiz Kurulum Betiği

Bu betik, **RustDesk** yazılımını otomatik ve sessiz bir şekilde kurmanıza olanak tanır. **RustDesk**, uzak masaüstü bağlantısı sağlayan ücretsiz ve açık kaynaklı bir yazılımdır. Bu betik sayesinde, **RustDesk**'i en son sürümüyle güvenle indirip kurabilirsiniz.

## Özellikler

- **Sessiz Kurulum:** Kullanıcıya herhangi bir etkileşimde bulunmadan **RustDesk** yazılımını kurar.
- **Otomatik Güncelleme:** Betik, GitHub üzerinden en son stabil sürümü otomatik olarak indirir ve kurar.
- **64-bit ve 32-bit Desteği:** 
  - **64-bit** sürümü, **Flutter** desteğinin olmaması nedeniyle Windows 8.1 ve alt sürümlerde kurulumda hata verebilir.
  - Bu nedenle, **Windows 8.1** ve alt sürümlerde betik, **RustDesk**'in 32-bit olan son sürümünü indirip kuracaktır.
  - Ayrıntılı bilgi için:
  - https://github.com/rustdesk/rustdesk/issues/10085
  - https://github.com/rustdesk/rustdesk/discussions/763

- **Özelleştirilebilir Kurulum:** RustDesk sunucunuz varsa, betik üzerinden sunucu adresinizi ve anahtarınızı tanımlayabilirsiniz.
- **RustDesk İndirme ve Kurulum:** Betik, **RustDesk**'in en son sürümünü GitHub üzerinden indirir. İndirme işlemi tamamlandıktan sonra yazılımı sessizce kurar.
- **Özelleştirme Seçenekleri:** Eğer bir **RustDesk** sunucunuz varsa, betik üzerinde sunucu adresinizi (domain) ve sunucunuzun ürettiği anahtarı (key) belirterek RustDesk'i bu sunucuya bağlamanızı sağlar.
- Betik dosyasındaki 

"set domain=" ve "set key="

değişkenlerine kendi sunucunuza ait bilgileri ekleyebilirsiniz.

Bu kısımları hiç değiştirmezseniz RsutDesk public server kullanılacaktı


## Kurulum Adımları

1. Betiği çalıştırarak, **RustDesk** yazılımının indirilmesini ve kurulmasını sağlayın.
2. Kurulum tamamlandığında, otomatik olarak bir kısayol oluşturulacak ve programı başlatabileceksiniz.

## Bağlantılar

- **RustDesk Projesi:** [RustDesk GitHub](https://github.com/rustdesk/rustdesk)

## Lisans

Bu betik, **Abdullah ERTÜRK** tarafından hazırlanmış olup **MIT Lisansı** altında lisanslanmıştır.




     English Explanation

# RustDesk Silent Installation Script

This script allows you to automatically and silently install **RustDesk** software. **RustDesk** is a free and open-source software that provides remote desktop connectivity. With this script, you can securely download and install **RustDesk** with its latest version.

## Features

- **Silent Installation:** Installs **RustDesk** software without any user interaction.
- **Automatic Update:** The script automatically downloads and installs the latest stable version from GitHub.
- **64-bit and 32-bit Support:**
  - The latest **64-bit** version of **RustDesk** fails to install on **Windows 8.1** and below due to a lack of **Flutter** support.
  - Therefore, on **Windows 8.1** and lower versions, the script installs the latest **32-bit** version of **RustDesk**.
  - For detailed information:
  - https://github.com/rustdesk/rustdesk/issues/10085
  - https://github.com/rustdesk/rustdesk/discussions/763

- **Customizable Installation:** If you have a **RustDesk** server, you can specify your server address and key through the script.
- **RustDesk Download and Installation:** The script downloads the latest version of **RustDesk** from GitHub and silently installs it once the download is complete.
- **Customization Options:** If you have a **RustDesk** server, the script allows you to specify your server address (domain) and the key generated by your server to connect **RustDesk** to this server.

## Installation Steps

1. Run the script to download and install **RustDesk** software.
2. Upon completion, a shortcut will be automatically created to launch the program.

## Links

- **RustDesk Project:** [RustDesk GitHub](https://github.com/rustdesk/rustdesk)

## License

This script is authored by **Abdullah ERTÜRK** and licensed under the **MIT License**.

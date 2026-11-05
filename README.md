# ComputerTemp

Bilgisayar sıcaklığını izlemek için geliştirilen bir .NET uygulaması.

> Bu depo [metintnc/ComputerTemp](https://github.com/metintnc/ComputerTemp) projesinin bir çatalıdır.

## Proje Yapısı

| Klasör | Açıklama |
| --- | --- |
| `Temp/` | Ana uygulama |
| `Temp.Tests/` | Birim testleri |
| `Temp.sln` | Visual Studio çözüm dosyası |

## Gereksinimler

- Windows (donanım sensörlerine erişim için)
- [.NET SDK](https://dotnet.microsoft.com/download) (proje dosyasında belirtilen sürüm)
- Visual Studio 2022 veya `dotnet` CLI

## Kurulum ve Çalıştırma

```bash
git clone https://github.com/ahmetcankse/ComputerTemp.git
cd ComputerTemp
dotnet restore
dotnet build
dotnet run --project Temp
```

Sıcaklık sensörlerini okumak için uygulamayı **yönetici olarak** çalıştırmak gerekebilir.

## Testler

```bash
dotnet test
```

## Katkıda Bulunma

1. Depoyu çatallayın
2. Yeni bir dal açın: `git checkout -b ozellik/yeni-ozellik`
3. Değişikliklerinizi commit edin
4. Dalı gönderin ve Pull Request açın

## Lisans

Lisans bilgisi için orijinal depoya bakın:
[metintnc/ComputerTemp](https://github.com/metintnc/ComputerTemp)

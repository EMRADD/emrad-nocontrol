# emrad-nocontrol

**emrad-nocontrol**, FiveM için geliştirilmiş bir script olup araçların havadayken kontrol edilmesini engeller ve düşüş yüksekliğine göre araca zarar verir veya patlatır. Gerçekçiliği artırmak amacıyla tasarlanmıştır.

## Özellikler

- 🚫 Araç havadayken yön tuşları (W, A, S, D) devre dışı bırakılır.
- 📉 Araç yere çarptığında düşüş yüksekliğine göre motor hasarı veya patlama uygulanır.
- ⚙️ Tamamen yapılandırılabilir `config.lua` dosyası ile esnek kullanım.

## Yapılandırma (`config.lua`)
```lua
Config.MinFallToDamage = 10.0       -- Bu yükseklikten sonra motor hasarı alır
Config.MinFallToExplode = 18.0      -- Bu yükseklikten sonra araç patlar
```

## Kurulum

1. Dosyaları `resources/[local]` klasörüne atın.
2. `server.cfg` dosyasına aşağıdaki satırı ekleyin:
   ```
   ensure emrad-nocontrol
   ```

## Lisans

MIT Lisansı — detaylar için `LICENSE` dosyasına bakınız.

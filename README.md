
# Xq-Company İşletim Sistemi

## 📌 Proje Hakkında

Bu proje, **Xq-Company** tarafından geliştirilen ve özelleştirilmiş bir işletim sistemi dağıtımıdır. Sistem, modern bilgisayar mimarisine uygun olarak 64-bit (X64) mimarisi için optimize edilmiştir ve tam Türkçe dil desteği sunar.

## 🎯 Sistem Özellikleri

### Teknik Özellikler
- **Mimari**: x64 (64-bit) - modern işlemcilerle tam uyumlu
- **Dil Desteği**: Türkçe (TR) ve İngilizce (EN) çift dil seçeneği
- **Sürüm**: DV5 (Geliştirme Sürüm 5)
- **Format**: ISO İmaj Dosyası (Kurulum için hazır)
- **Sistem Gereksinimler**: 
  - Minimum 2 GB RAM
  - Minimum 20 GB boş disk alanı
  - USB 3.0 veya DVD sürücüsü (kurulum için)

### Özellikler
✅ Türkçe tam dil desteği  
✅ İngilizce alternatif dil  
✅ Optimize edilmiş 64-bit performans  
✅ Sistem yönetim araçları  
✅ Geliştirici araçları ve kütüphaneleri  

## 📥 İndirme ve Kurulum

### Doğrudan İndirme Linki

<a href="https://github.com/bro635756-spec/Xq-Company/raw/main/IRM_CEI_X64FRE_TR-TR-EN-EN_DV5_XQOS-v1.iso" class="download-btn" style="display: inline-block; padding: 10px 20px; background-color: #28a745; color: white; text-decoration: none; border-radius: 5px; font-weight: bold;">
  ⬇️ SİSTEMİ İNDİR (.ISO)
</a>

**Dosya Adı**: `IRM_CEI_X64FRE_TR-TR-EN-EN_DV5_XQOS-v1.iso`

### Dosya Bilgileri
| Özellik | Bilgi |
|---------|-------|
| **Mimari** | x64 (64-bit) |
| **Sürüm** | DV5 (Geliştirme) |
| **Dil** | Türkçe / İngilizce |
| **Format** | ISO İmaj |
| **Kalite** | FRE (Serbest) |

### Kurulum Adımları

#### 1️⃣ ISO Dosyasını İndirin
Yukarıdaki bağlantıdan ISO dosyasını bilgisayarınıza indirin.

#### 2️⃣ Önyükleme Medyası Oluşturun

**Windows için:**
- [Rufus](https://rufus.ie/) veya [Etcher](https://www.balena.io/etcher/) gibi araçları kullanın
- ISO dosyasını seçin
- USB sürücüyü bağlayın
- Yazma işlemini başlatın

**Linux/Mac için:**
```bash
# USB sürücüyü tanımlayın
lsblk  # veya diskutil list

# ISO dosyasını yazın
sudo dd if=IRM_CEI_X64FRE_TR-TR-EN-EN_DV5_XQOS-v1.iso of=/dev/sdX bs=4M && sync

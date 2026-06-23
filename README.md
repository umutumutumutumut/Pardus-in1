# Pardus Sistem Kontrolu

Pardus icin terminalde CPU, RAM, disk ve sicaklik bilgisini gosteren basit bir Python uygulamasi.

## Ozellikler

- CPU kullanimini gosterir.
- RAM kullanimini gosterir.
- Disk kullanimini gosterir.
- Uygun sensor varsa sicaklik bilgisini gosterir.
- Terminalde renkli ve okunabilir bir arayuz sunar.

## Kurulum

Projeyi indirin:

```bash
git clone https://github.com/umutumutumutumut/Pardus-in1.git
cd Pardus-in1
```

Gerekli paketleri kurun:

```bash
python3 kurulum.py
```

Kurulum hata verirse Pardus terminalde elle sunu deneyin:

```bash
sudo apt install python3-colorama python3-pyfiglet
```

## Calistirma

```bash
python3 sistem_kontrol.py
```

## Dosyalar

- `sistem_kontrol.py`: Sistem bilgilerini gosteren ana uygulama.
- `kurulum.py`: Gerekli Python paketlerini kuran yardimci dosya.

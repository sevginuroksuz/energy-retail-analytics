# Case Study 02 - Elektrik Verisi Analizi

Bu proje, `data/elektrik_veri.xlsx` dosyasi uzerinden enerji perakende sektorune ait elektrik tuketim, tahsilat ve odeme zamanlamasi verilerini analiz etmek icin hazirlanmistir.

## Proje Yapisi

```text
case_study02/
|-- data/
|   `-- elektrik_veri.xlsx
|-- notebooks/
|   |-- notebook_01_veri_kesfi.ipynb
|   |-- notebook_02_gorsellestirme.ipynb
|   `-- notebook_03_veri_hikayesi.ipynb
|-- outputs/
|   `-- figures/
|-- README.md
`-- requirements.txt
```

## Kurulum

```bash
pip install -r requirements.txt
```

## Notebooks

- `notebook_01_veri_kesfi.ipynb`: Veri yukleme, tanimlayici istatistikler, eksik deger kontrolu, negatif/sifir tuketim incelemesi, aykiri deger analizi ve hesap sinifi bazli tuketim istatistikleri.
- `notebook_02_gorsellestirme.ipynb`: Dagilim, zaman serisi, karsilastirma, odeme zamanlamasi ve iliski analizi grafiklerini uretir; gorselleri `outputs/figures` altina kaydeder.
- `notebook_03_veri_hikayesi.ipynb`: Bulgulari problem tanimi, hipotez, analiz, bulgular ve is onerileri akisi ile storytelling formatinda toparlar.

## Veri

Ana veri dosyasi:

```text
data/elektrik_veri.xlsx
```

Not: Excel dosyasi boyutu nedeniyle Git LFS ile takip edilmektedir.

Excel dosyasi 5 sayfa icerir:

- `Tahsilat`
- `Tahsilat 1`
- `Tahakkuk`
- `Tahakkuk 1`
- `Tahakkuk 2`

## Ciktilar

Grafikler su klasore kaydedilir:

```text
outputs/figures/
```

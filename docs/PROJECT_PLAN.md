# Proje Plani

```json
{
  "proje": {
    "ad": "Tekstil ERP Sistemi",
    "tip": "Enterprise Resource Planning",
    "sure": "12 ay",
    "butce": "850000 TL",
    "takimBuyuklugu": 12,
    "aciklama": "Tekstil fabrikası için kapsamlı ERP çözümü"
  },
  "moduller": [
    {
      "ad": "Üretim Takibi",
      "sure": "10 hafta",
      "oncelik": "Yüksek",
      "ozellikler": [
        "İş emri oluşturma ve takibi",
        "Makine durumu izleme",
        "Üretim planlaması",
        "Kapasite yönetimi",
        "Operasyon takibi",
        "Vardiya yönetimi",
        "Real-time üretim göstergeleri"
      ],
      "teknolojiler": ["ASP.NET Core", "SignalR", "SQL Server", "Angular"],
      "baguimlilik": []
    },
    {
      "ad": "Hammadde Stok Yönetimi",
      "sure": "8 hafta",
      "oncelik": "Yüksek",
      "ozellikler": [
        "Stok takibi",
        "Lot yönetimi",
        "Min-max stok seviyeleri",
        "Tedarikçi entegrasyonu",
        "Depo yönetimi",
        "Barkod sistemi",
        "Envanter sayımı"
      ],
      "teknolojiler": ["ASP.NET Core", "Entity Framework", "SQL Server", "Angular"],
      "baguimlilik": []
    },
    {
      "ad": "Sipariş Takibi",
      "sure": "9 hafta",
      "oncelik": "Yüksek",
      "ozellikler": [
        "Müşteri siparişleri",
        "Sipariş durumu takibi",
        "Teslimat planlaması",
        "Fatura entegrasyonu",
        "Sevkiyat yönetimi",
        "Sipariş onay süreci",
        "Müşteri bildirimleri"
      ],
      "teknolojiler": ["ASP.NET Core", "Entity Framework", "SQL Server", "Angular"],
      "baguimlilik": ["Stok Yönetimi"]
    },
    {
      "ad": "Muhasebe Entegrasyonu",
      "sure": "7 hafta",
      "oncelik": "Orta",
      "ozellikler": [
        "Otomatik fiş oluşturma",
        "Maliyet hesaplama",
        "Finansal raporlama",
        "Bütçe takibi",
        "Vergi hesaplamaları",
        "E-fatura entegrasyonu",
        "Nakit akış takibi"
      ],
      "teknolojiler": ["ASP.NET Core", "Entity Framework", "SQL Server", "Crystal Reports"],
      "baguimlilik": ["Sipariş Takibi", "Stok Yönetimi"]
    },
    {
      "ad": "Personel Yönetimi",
      "sure": "6 hafta",
      "oncelik": "Orta",
      "ozellikler": [
        "Personel bilgi sistemi",
        "Bordro hesaplama",
        "İzin takibi",
        "Performans değerlendirme",
        "Eğitim yönetimi",
        "Yetkinlik matrisi",
        "Mesai takibi"
      ],
      "teknolojiler": ["ASP.NET Core", "Entity Framework", "SQL Server", "Angular"],
      "baguimlilik": []
    },
    {
      "ad": "Kalite Kontrol",
      "sure": "8 hafta",
      "oncelik": "Yüksek",
      "ozellikler": [
        "Kalite test planları",
        "Test sonuçları kayıt",
        "Hatalı ürün takibi",
        "Kalite standartları",
        "Müşteri şikayetleri",
        "İyileştirme önerileri",
        "Kalite sertifikaları"
      ],
      "teknolojiler": ["ASP.NET Core", "Entity Framework", "SQL Server", "Angular"],
      "baguimlilik": ["Üretim Takibi"]
    },
    {
      "ad": "CRM",
      "sure": "7 hafta",
      "oncelik": "Orta",
      "ozellikler": [
        "Müşteri veritabanı",
        "Satış fırsatları",
        "Müşteri iletişim geçmişi",
        "Kampanya yönetimi",
        "Müşteri segmentasyonu",
        "Satış raporları",
        "Müşteri memnuniyeti"
      ],
      "teknolojiler": ["ASP.NET Core", "Entity Framework", "SQL Server", "Angular"],
      "baguimlilik": ["Sipariş Takibi"]
    },
    {
      "ad": "Raporlama",
      "sure": "5 hafta",
      "oncelik": "Yüksek",
      "ozellikler": [
        "Üretim raporları",
        "Stok raporları",
        "Finansal raporlar",
        "Performans göstergeleri",
        "Dashboard ekranları",
        "Otomatik rapor gönderimi",
        "Export özellikleri"
      ],
      "teknolojiler": ["Power BI", "Crystal Reports", "SQL Server", "SSRS"],
      "baguimlilik": ["Tüm Modüller"]
    }
  ],
  "fazlar": [
    {
      "ad": "Analiz ve Tasarım",
      "sure": "6 hafta",
      "aktiviteler": [
        "İş analizi",
        "Sistem tasarımı",
        "Veritabanı tasarımı",
        "UI/UX tasarım",
        "Teknik dokümantasyon"
      ]
    },
    {
      "ad": "Temel Modül Geliştirme",
      "sure": "16 hafta",
      "aktiviteler": [
        "Üretim takibi geliştirme",
        "Stok yönetimi geliştirme",
        "Sipariş takibi geliştirme",
        "Temel entegrasyonlar"
      ]
    },
    {
      "ad": "İleri Modül Geliştirme",
      "sure": "14 hafta",
      "aktiviteler": [
        "Muhasebe entegrasyonu",
        "Personel yönetimi",
        "Kalite kontrol",
        "CRM geliştirme"
      ]
    },
    {
      "ad": "Raporlama ve Test",
      "sure": "8 hafta",
      "aktiviteler": [
        "Raporlama modülü",
        "Entegrasyon testleri",
        "Kullanıcı testleri",
        "Performans testleri"
      ]
    },
    {
      "ad": "Devreye Alma",
      "sure": "4 hafta",
      "aktiviteler": [
        "Sistem kurulumu",
        "Veri migrasyonu",
        "Kullanıcı eğitimi",
        "Go-live desteği"
      ]
    }
  ],
  "takim": [
    {
      "rol": "Proje Yöneticisi",
      "sayi": 1,
      "beceriler": ["Proje yönetimi", "ERP deneyimi", "Tekstil sektörü"]
    },
    {
      "rol": "Sistem Analisti",
      "sayi": 2,
      "beceriler": ["İş analizi", "ERP süreçleri", "Dokümantasyon"]
    },
    {
      "rol": "Backend Developer",
      "sayi": 3,
      "beceriler": ["ASP.NET Core", "SQL Server", "Entity Framework"]
    },
    {
      "rol": "Frontend Developer",
      "sayi": 2,
      "beceriler": ["Angular", "TypeScript", "HTML/CSS"]
    },
    {
      "rol": "Veritabanı Uzmanı",
      "sayi": 1,
      "beceriler": ["SQL Server", "Performans optimizasyonu", "Veri modelleme"]
    },
    {
      "rol": "Test Uzmanı",
      "sayi": 2,
      "beceriler": ["Test otomasyonu", "Manuel test", "ERP testleri"]
    },
    {
      "rol": "DevOps Uzmanı",
      "sayi": 1,
      "beceriler": ["Azure", "CI/CD", "Deployment"]
    }
  ],
  "teknolojiler": {
    "backend": ["ASP.NET Core 6", "Entity Framework Core", "SignalR"],
    "frontend": ["Angular 15", "TypeScript", "Bootstrap"],
    "veritabani": ["SQL Server 2019", "Redis Cache"],
    "raporlama": ["Power BI", "Crystal Reports", "SSRS"],
    "deployment": ["Azure App Service", "Azure SQL Database"],
    "entegrasyon": ["REST API", "SOAP Web Services", "Message Queue"]
  },
  "riskler": [
    {
      "risk": "Karmaşık iş süreçleri",
      "olasilik": "Yüksek",
      "etki": "Yüksek",
      "onlem": "Detaylı iş analizi ve iteratif geliştirme"
    },
    {
      "risk": "Veri migrasyonu zorlukları",
      "olasilik": "Orta",
      "etki": "Yüksek",
      "onlem": "Erken veri analizi ve test migrasyonları"
    },
    {
      "risk": "Kullanıcı direnci",
      "olasilik": "Orta",
      "etki": "Orta",
      "onlem": "Kapsamlı eğitim ve change management"
    }
  ],
  "kaliteMetrikleri": {
    "performans": "Sayfa yükleme süresi < 3 saniye",
    "kullanilabilirlik": "Kullanıcı memnuniyeti > %85",
    "guvenilirlik": "Uptime > %99.5",
    "olceklenebilirlik": "1000 eşzamanlı kullanıcı desteği"
  },
  "teslimatlar": [
    {
      "ad": "Sistem Tasarım Dokümanı",
      "tarih": "6. hafta"
    },
    {
      "ad": "Temel Modüller Beta",
      "tarih": "22. hafta"
    },
    {
      "ad": "Tam Sistem Test",
      "tarih": "44. hafta"
    },
    {
      "ad": "Canlı Sistem",
      "tarih": "48. hafta"
    }
  ]
}
```
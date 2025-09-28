# Dinamik Akıllı Burs ve Etkinlik Bulucu

# Amaç:
Öğrencilerin staj, burs, yarışma, hibe ve benzeri fırsatları kaçırmaması için web scraping ve yapay zekâ destekli özetleme teknikleriyle, kullanıcının bölümü, ilgi alanı ve kişisel takvimine göre anlık bildirim gönderen akıllı bir platform.



┌───────────────────────────┐
│  Kaynak Siteler           │
└───────────────┬───────────┘
                │  Web Scraper (Python, Playwright/BeautifulSoup)
                
┌───────────────▼───────────┐
│  Veri Kuyruğu (RabbitMQ)  │
└───────────────┬───────────┘
                │  ETL & Çok Dilli NLP
                
┌───────────────▼───────────┐
│  ML Modeli (BERT/LLM)     │
└───────────────┬───────────┘

                │
┌───────────────▼───────────┐
│  API (FastAPI/Django)     │
└───────────────┬───────────┘

                │
┌───────────────▼───────────┐
│  Frontend (React/Next.js) │
└───────────────────────────┘

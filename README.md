# Web Scraping with Selenium

![What is Web Scraping](https://blog.apify.com/content/images/2023/09/what-is-web-scraping-websites-web-scraper-structured-data-1.png)

> *Image Source: [Apify Blog](https://blog.apify.com/what-is-web-scraping/)*

This repository contains a collection of web scraping scripts using **Selenium** for scraping company profiles and business information from various websites. The scripts are designed to automate browser interactions to gather dynamic content from the following websites:

- [Glints](https://glints.com/id/companies?countries=ID): Scrapes company profiles and job listings from Glints.
- [Kalibrr](https://www.kalibrr.id/id-ID/home): Scrapes company data, job opportunities, and other relevant business details.
- [Indonesia Investments](https://www.indonesia-investments.com/id/bisnis/profil-perusahaan/item74): Scrapes company profiles and business-related information for investment insights.
- [IDX](https://www.idx.co.id/id/perusahaan-tercatat/profil-perusahaan-tercatat): Scrapes data about listed companies on the Indonesia Stock Exchange (IDX).

These scripts use **Selenium WebDriver** to handle dynamic content loading, such as JavaScript-driven websites. The collected data can be exported to various formats such as CSV or JSON for further analysis and processing.

## Sample Data Collected

Here’s a sample of the collected data:

| **NAMA**            | **LOKASI-PERUSAHAAN**                | **COMPANY-SIZE** | **INDUSTRI**                | **WEBSITE**                                      | **JOB-TITLE**            | **LOKASI-KERJA**           | **TIPE-PEKERJAAN** | **PENGALAMAN**   | **GAJI**         | **SYARAT-KELULUSAN** | **CONTACT NUMBER**    | **EMAIL**                    |
|---------------------|-------------------------------------|------------------|----------------------------|------------------------------------------------|--------------------------|----------------------------|---------------------|------------------|------------------|----------------------|------------------------|-----------------------------|
| Zglow Clinic        | Jakarta Timur, DKI Jakarta, Indonesia | 51 - 200 karyawan| Hospital & Health Care      | [https://www.zglowclinic.id/](https://www.zglowclinic.id/)  | BEAUTICIAN KLINIK KECANTIKAN | Serpong, Tangerang Selatan, Banten | Full Time           | 1 – 3 tahun      | Tidak Ditampilkan | Minimal Sarjana (S1)   | +628112167711         | marketing.bmi0101@gmail.com |
| PT ABADI TIMUR MANDIRI | Jakarta Selatan, DKI Jakarta, Indonesia | 11 - 50 karyawan | Renewables & Environment    | [https://www.instagram.com/ucoku.id](https://www.instagram.com/ucoku.id) | HSE Officer               | Gedangan, Kab. Sidoarjo, Jawa Timur | Full Time           | 1 – 3 tahun      | Tidak Ditampilkan | Minimal Sarjana (S1)   | +628119329818         | Tiffany@ucoku.com           |

## Requirements
- Python 3.x
- Selenium
- WebDriver (ChromeDriver, GeckoDriver, etc.)

## License
This project is licensed under the MIT License.

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

## Project Directory Structure

```plaintext
.
├── 1. scraper-idx.ipynb                Jupyter Source File        50 KB
├── 2. scraper-kalibrr.ipynb             Jupyter Source File        4.005 KB
├── 3. scraper-indonesia_investments.ipynb Jupyter Source File        8 KB
├── 4. scraper-companies-website.ipynb   Jupyter Source File        113 KB
├── 5. scraper-glints.ipynb              Jupyter Source File        35 KB
├── requirements.txt                    Text Document              7 KB
```

## Requirements
To install the required dependencies, use the following command after cloning this repository:

```
pip install -r requirements.txt
```

This will install the necessary libraries and dependencies such as Selenium and others for scraping tasks.

## License
This project is licensed under the MIT License.

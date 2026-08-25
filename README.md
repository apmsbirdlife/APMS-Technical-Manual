# APMS Manual

Technical manual for the Automated Penguin Monitoring System (APMS), developed by BirdLife South Africa for long-term monitoring of African penguin (*Spheniscus demersus*) colonies.

## 🌐 Read the manual

The rendered manual is available at: **xxxxxxxxxx**

## 📖 About

The APMS uses RFID detection and weighbridge technology to automatically record individual penguin identities and body masses at colony gates. This manual covers hardware construction, software configuration, field deployment, and data processing.

## 🛠 Contributing

Contributions and corrections are welcome. To suggest a change:

1. Click **Edit this page** on any page of the manual website, or
2. Open an [issue](https://github.com/YOUR-ORG/apms-manual/issues) on this repository, or
3. Fork the repository, make your changes, and submit a pull request

## 📁 Repository structure

```
apms-manual/
├── _quarto.yml          # Site configuration
├── index.qmd            # Introduction
├── 01_solar.qmd         # Solar power supply
├── 02_internet.qmd      # Internet and Wi-Fi
├── 03_scales_platform.qmd
├── 04_apms_monitor.qmd
├── 05_apms_main_unit.qmd
├── 06_aws_s3.qmd
├── 07_raspberry_pi.qmd
├── 08_arduino.qmd
├── 09_biomark.qmd
├── 10_testing.qmd
├── 11_crontab.qmd
├── 12_commissioning.qmd
├── 13_data_processing.qmd
├── 14_maintenance.qmd
├── 15_accuracy.qmd
├── 16_conclusion.qmd
└── images/              # All figures and photos
```

## 🔧 Building locally

To render the manual locally you need [Quarto](https://quarto.org/docs/get-started/) installed, then:

```bash
quarto preview
```

## 📄 Licence

This manual is released under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). You are free to share and adapt the material with attribution.

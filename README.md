## Hi! I'm Antoine Merino

I live in Valence (France), currently working in Paris as a **software engineer**. I mainly do backend development. I try to contribute modestly to open-source projects in my free time.

<!--
**Merinorus/Merinorus** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

Feel free to connect with me on [LinkedIn](https://www.linkedin.com/in/antoine-merino/). Please add a note so I don't mistake you for a bot or a random recruiter.

### Skills and Experience

- **Domains**: Software design and architecture, development, testing, CI/CD
- **Languages**: Python, C++, C, Java, HTML/CSS
- **Databases**: MariaDB, MySQL, AWS RDS, PostgreSQL, SQL DB optimization (indexing, normalization, deadlock mitigation), MongoDB, AWS DocumentDB, Redis
- **Other**: Memcached
- **DevOps/Infra**: Docker, Ansible, Ubuntu/Debian server, Kibana, Grafana
- **Platforms**: Windows, macOS, Linux, Android, Embedded systems & Microcontrollers
- **Other**: electronics, photovoltaics, car mechanics


### Some open-source contributions
#### Code

##### C++
- [ZXing-CPP](https://github.com/zxing-cpp/zxing-cpp): Barcode image processing library. Added support for reading DX Film Edge barcodes on 35mm films. [[Ticket]](https://github.com/zxing-cpp/zxing-cpp/issues/662)


##### C
- [Zint](https://github.com/zint/zint): Barcode generation software. Added support for generating DX Film Edge barcodes. [[Ticket]](https://sourceforge.net/p/zint/tickets/327/)

##### Python
- [Paperless-ngx](https://github.com/paperless-ngx/paperless-ngx): A [Django](https://github.com/django/django)-based document management system that scans, performs OCR, organizes, and enables full-text search of documents. Worked mainly on performance improvements ([full list](https://github.com/paperless-ngx/paperless-ngx/pulls?q=is%3Apr+author%3AMerinorus+is%3Amerged+sort%3Aupdated-desc)), including:
  - Faster page loading by eliminating N+1 queries [[PR]](https://github.com/paperless-ngx/paperless-ngx/pull/10657)
  - Faster classifier training and predictions [[PR]](https://github.com/paperless-ngx/paperless-ngx/pull/10363)
  - Faster date parsing [[PR]](https://github.com/paperless-ngx/paperless-ngx/pull/10181)
  - Database read-caching [[PR]](https://github.com/paperless-ngx/paperless-ngx/pull/9784)
  - Database connection pooling [[PR]](https://github.com/paperless-ngx/paperless-ngx/pull/10354)

- [Limits](https://github.com/alisaifee/limits): Rate limiting library used by famous frameworks ([Flask](https://github.com/alisaifee/flask-limiter), [FastAPI / Starlette](https://github.com/laurentS/slowapi)...):
  - Implemented the [sliding window counter](https://blog.cloudflare.com/counting-things-a-lot-of-different-things/) algorithm, a memory-efficient approximation of the moving window algorithm. Supported backends: RAM, Redis and Memcached. The author added support for MongoDB. [[Ticket]](https://github.com/alisaifee/limits/discussions/245)
  - Improved Memcached backend's performance.
  - Fixed a race condition issue in RAM backend.
- [Flask-Pydantic](https://github.com/bauerji/flask-pydantic): [Flask](https://github.com/pallets/flask) (web framework) extension to integrate with [Pydantic](https://github.com/pydantic/pydantic) (data validation library). Added backward compatibility with Pydantic V1. [[Ticket]](https://github.com/bauerji/flask-pydantic/issues/90)
- [FastAPI-MVC](https://github.com/fastapi-mvc/fastapi-mvc): [FastAPI](https://github.com/tiangolo/fastapi) (web framework) project generator. Fixed installation failure with Python versions 3.10 and above. [[Ticket]](https://github.com/fastapi-mvc/fastapi-mvc/issues/60)
- [Freqtrade](https://github.com/freqtrade/freqtrade): crypto trading bot. Added weekly and monthly reports on Telegram. [[Ticket]](https://github.com/freqtrade/freqtrade/issues/5527)

#### Issues raised
- [Graby](https://github.com/j0k3r/graby): Web page content extractor used by [Wallabag](https://github.com/wallabag/wallabag). Asked for support for a two-step login. [[Help needed!]](https://github.com/j0k3r/graby/issues/326)
- [Koreader](https://github.com/koreader/koreader): Ebook reader application. Found a bug due to a misleading French translation. [[Issue]](https://github.com/koreader/koreader/issues/10650)
- [python-jose](https://github.com/mpdavis/python-jose): JOSE python library. Vulnerability not fixed in a dependency. [[Issue]](https://github.com/mpdavis/python-jose/issues/341)
- [pypdf](https://github.com/py-pdf/pypdf): Python PDF library. Found a bug where PDFs were not merged correctly after an update. [[Issue]](https://github.com/py-pdf/pypdf/issues/1344)
- [pur](https://github.com/alanhamlett/pip-update-requirements): Python package update tool. Asked for a dry mode that can list packages to be upgraded. [[Issue]](https://github.com/alanhamlett/pip-update-requirements/issues/50)
- [pydantic-i18n](https://github.com/boardpack/pydantic-i18n): Internationalisation for [Pydantic](https://github.com/pydantic/pydantic) error messages. Found an issue with static code typing. [[Issue]](https://github.com/boardpack/pydantic-i18n/issues/74)

#### Current projects
- [The Big Film Database](https://github.com/merinorus/thebigfilmdatabase-website): a website for exploring [the largest open-source database of 35mm photographic films](https://github.com/dxdatabase/Open-source-film-database).

#### Past projects
- [Flexible Flight Search](https://github.com/Merinorus/fff): find cheap round-trip flights with more flexible dates than online flight comparators.
- [eBay announce generator](https://github.com/Merinorus/ebay-announce-generator): personal template for pretty eBay listings.
- [Rocksmith profile sync](https://github.com/Merinorus/rocksmith-profile-sync): Sync your [Rocksmith 2014](https://en.wikipedia.org/wiki/Rocksmith_2014) profile across multiple machines.

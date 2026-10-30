# LinkNest

## Demo (0.5× speed)

https://github.com/user-attachments/assets/7a3cead8-82b3-4d1a-b10e-d995e614aa3a

LinkNest is a small Flask URL shortener for turning long URLs into neat, shareable links. It uses Base26 short codes, MySQL to store links, and Redis to cache lookups.

Maintained and customized by [Ayush Sharma](https://github.com/Ayushsharma77). This version builds on the original MIT-licensed project by Rizwan Hasan; see [LICENSE](LICENSE) for the copyright notices and terms.

## Database Schema

* [MySQL schema](MySQL-Database-Schema/MySQL-Database-Schema.sql)

## Run locally

Copy `.env.example` to `.env`, fill in all three values with private random secrets, and keep `.env` private. In PowerShell, copy it with:

```powershell
Copy-Item .env.example .env
```

Then start the app and its services with Docker Compose:

```bash
docker compose up -d
```

Then open [http://localhost:8080](http://localhost:8080) in your browser.

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## Maintainer

[Ayush Sharma](https://github.com/Ayushsharma77)

## License

[MIT](LICENSE)

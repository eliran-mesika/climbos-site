# ClimbOS Site Agent Notes

## Product Focus

- This repo is the static public site for ClimbOS at `climbos.mesikalabs.com`.
- Keep claims aligned with the current app state. Do not add account, cloud sync, medical advice, injury diagnosis, or paid feature claims unless the app repo and App Store metadata support them.
- Keep the site focused on support, privacy, terms, and concise product positioning.

## MesikaLabs Contact Points

- General support: `support@mesikalabs.com`
- Privacy: `privacy@mesikalabs.com`
- Billing: `billing@mesikalabs.com`
- Legal: `legal@mesikalabs.com`
- ClimbOS support: `climbos@mesikalabs.com`

## Validation

- Local smoke test: `python3 -m http.server 8091 --bind 127.0.0.1`
- Check `/`, `/support/`, `/privacy/`, `/terms/`, `/robots.txt`, `/sitemap.xml`, and `/llms.txt`.
- Hosted checks after deploy: `curl -I -L https://climbos.mesikalabs.com/ https://climbos.mesikalabs.com/robots.txt https://climbos.mesikalabs.com/sitemap.xml`

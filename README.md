# NepremicnineScraping

<p float="left">
  <img src="./docs/screenshot-mail.png" height="500" />
</p>

**Runs only on local device, because of Cloudflare protection**

While you are away, you may miss a great deal. This scraper was supposed to fix that.

App features
- Scraping Nepremicnine.net
- Alerting via email

## Tech stack
![Bun](https://img.shields.io/badge/Bun-000000?style=for-the-badge&logo=bun&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white) 
![Nodemailer](https://img.shields.io/badge/Nodemailer-22B573?style=for-the-badge&logo=gmail&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=for-the-badge)

## Getting Started
To get the project running, follow these steps.

### Prerequisites
Bun required

- macOS: `brew install bun`
- Windows: `winget install Oven-sh.Bun`

### Installation

1.  Clone the repo
    ```sh
    git clone https://github.com/domensapac/nepremicnine-scraping.git
    ```
    ```sh
    cd nepremicnine-scraping
    ```
2.  Create .env file and fill following
    ```sh
    SUPABASE_URL=
    SUPABASE_ANON_KEY=
    NODEMAILER_PASS= //google 16 digit app password
    NODEMAILER_ADDRESS= 
    ```
3.  Install bun packages 
    ```sh
    bun install
    ```
4.  Install playwright
    ```sh
    bunx playwright install
    ```
5.  Run the scraper
    ```sh
    bun run index.ts
    ```
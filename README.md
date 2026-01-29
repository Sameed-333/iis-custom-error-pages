# IIS Custom Error Pages (Custom 404)

This mini-project demonstrates how to configure a **custom 404 error page** in IIS on Windows. It includes adding a 404 rule in IIS Error Pages, adjusting feature settings to use custom pages, and verifying the result in a browser.

**Course:** System & Network Administration (SNA Lab)  
**Tool Used:** Internet Information Services (IIS)  
**Focus:** Custom error handling, IIS Error Pages configuration, 404 validation

---

## Tools & Technologies
- Windows 11 (similar steps apply on Windows 10 / Windows Server)
- IIS (Internet Information Services)
- IIS Manager (Error Pages feature)

---

## Project Files
- `report/` (lab report / documentation)
- `assets/` (screenshots: configuration steps and verification)

---

## What’s Demonstrated
- Launching IIS Manager and selecting the target site
- Configuring a custom **404** entry using IIS **Error Pages**
- Using either:
  - **File** (static page), or
  - **Execute a URL on this site** (dynamic handling)
- Editing feature settings to ensure **Custom error pages** are applied
- Testing the configuration by opening a non-existent page in a browser

---

## Key Learning
- How IIS handles HTTP status errors via the Error Pages feature
- How to map status code 404 to a custom page or handler
- How to validate custom error behavior from the client side

---

## Screenshots
Evidence is available in `assets/`:
- `01-iis-manager-site-selected.png`
- `02-error-pages-add-404.png`
- `03-edit-feature-settings-custom.png`
- `04-404-test-in-browser.png`

---

## How to Run
1. Clone the repository:
```bash
git clone https://github.com/Sameed-333/iis-custom-error-pages.git
```

2. Navigate to the project folder:

```bash
cd iis-custom-error-pages
```

3. Review documentation and evidence:
- Open the report inside `report/`
- Review screenshots in `assets/`

4. Validate (high-level):
- Add a custom 404 entry in IIS Error Pages for the target site
- Ensure feature settings are set to use custom error pages
- Test by browsing a non-existent URL and confirm your custom 404 page appears

---

## Disclaimer
This project is for educational purposes only as part of a university SNA lab. It demonstrates IIS custom error page configuration in a controlled environment and is not intended as a complete production hardening guide.

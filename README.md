# Andimus

Public pages of Andimus, the shared sign-in for the system's apps (ViPharmind, ViLearnest):
home, `/privacy` and `/terms`. Google's OAuth consent screen (Google Cloud project `andimus`)
links to them. Static HTML, deployed on Vercel at https://andimus.vercel.app.

```bash
vercel deploy --prod   # only needed without the Git integration
```

| Part | Site | Repository |
| --- | --- | --- |
| Andimus (these pages, Google sign-in in GCP project `andimus`) | https://andimus.vercel.app | doanan293/Andimus |
| ViPharmind | https://vipharmind.vercel.app | doanan293/ViPharmind |
| ViLearnest | https://vilearnest.vercel.app | doanan293/ViLearnest |

A push to `main` deploys the site.

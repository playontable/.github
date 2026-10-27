## Codebase

PlayOnTable was developed using the following GPL/DSL languages:

*For the **backend***

- **Python**

*For the **frontend***

- **SASS**
- **HTML**
- **JavaScript**

## Dependencies

Python backend `requirements.txt` file contains 2 dependencies:

- [FastAPI](https://fastapi.tiangolo.com/) (for WebSocket connections)
- [Uvicorn](https://uvicorn.dev/) (as ASGI web server)

Frontend depends on 1 JavaScript library delivered from [jsDelivr](https://www.jsdelivr.com/) CDN:

- [GSAP](https://gsap.com/) (for dragging items on the table)

## Production

PlayOnTable.com backend is deployed on [Vercel](https://vercel.com/), as well as the frontend, as PWA ([Progressive Web App](https://developer.mozilla.org/en-US/docs/Web/Progressive_web_apps))

It's also available on Android on [Google Play Store](https://play.google.com/store/apps/details?id=com.playontable.app) as TWA ([Trusted Web Activity](https://developer.android.com/develop/ui/views/layout/webapps/trusted-web-activities)), build with [PWABuilder](https://www.pwabuilder.com/)

The "_.com_" TLD web domain is registered on [Ionos](https://www.ionos.it/) (it's possible to check [there](https://who.is/whois/playontable.com) PlayOnTable.com WHOIS)
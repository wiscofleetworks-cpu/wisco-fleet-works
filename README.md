# Wisco Fleet Works

Website for Wisco Fleet Works LLC, a mobile fleet maintenance and repair business in Madison, Fitchburg and DeForest, WI.

The site is a single static `index.html` with no build step, deployed on Vercel.

- Quote form: Formspree form "Wisco Fleet Works Quote Requests" (`xjyyzpqz`), which emails wiscofleetworks@gmail.com. If `FORMSPREE_ENDPOINT` in `index.html` is emptied, the form falls back to a pre-filled email.
- Preview: `vercel deploy`. Production: `vercel deploy --prod`.

# Nexus Travels — website

The public site: one HTML file and six photographs.

    public/index.html     the whole site
    public/images/        the photographs
    wrangler.jsonc        Cloudflare Pages settings

## Deploying

Connected to Cloudflare Pages from this repository, every push to `main`
deploys itself. Nothing else to do.

If the project is still on drag-and-drop instead, upload the `public`
folder and ignore `wrangler.jsonc`.

## What is not in here

The owner-only **Edit site** and **Bookings** panels, and the booking and
client records behind them. Those live on the Claude artifact and do not
travel. Export the CSV from the Bookings panel regularly — it is the only
copy that survives.

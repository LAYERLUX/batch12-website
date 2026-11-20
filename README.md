# Batch 12 website

The website for **Batch 12**, small-batch jams, salsas and pickles from Haymarket, Virginia. Live at https://batch12.com.

## How it works
- Plain HTML and CSS: no build step. Each page is its own `.html` file, and all pages share `styles.css`.
- Hosted on **Netlify**, which publishes this repository automatically every time a change is saved to the `main` branch.
- Photos for the Farm to Jar gallery live in `g/`.

## Pages
| File | Page |
|---|---|
| `index.html` | Home |
| `flavors.html` | Flavor Guide (all flavors, search and filters) |
| `farm-to-jar.html` | Farm to Jar photo gallery |
| `story.html` | Our Story |
| `find-us.html` | Where to Buy and contact |
| `order.html` | Order request form |
| `thanks.html`, `order-thanks.html` | Thank-you pages after a form is sent |

## Forms
The email sign-up (`newsletter`) and the order request (`order-request`) use **Netlify Forms**. Submissions appear in Netlify under **Forms**, and email notifications go to therealbatch12@gmail.com. Keep the `data-netlify="true"` attribute and the hidden `form-name` field on each form, or Netlify stops collecting them.

# WebTea Connect

A responsive project directory and studio landing page for WebTea. The homepage brings the studio, business websites, event experiences, and experiments together in one place, with direct links to the deployed destinations.

## Stack

- Plain HTML, CSS, and JavaScript
- No dependencies, build step, or API keys
- Responsive layout with accessible navigation
- Live project cards with search and category filters
- SEO metadata and Organization structured data

## Run locally

Open `index.html` in any modern browser. No install command is needed.

## Deploy to Vercel

1. Import `viratsingh862008-blip/Webteaconnect` into Vercel.
2. Use the **Other** framework preset if Vercel asks for a framework.
3. Leave the build command empty and use `.` as the output directory.
4. Deploy.

Because this is a static site, every edit to `index.html` can be deployed without a compile step.

## Updating the directory

Project records live in the `projects` array near the end of `index.html`. Each record contains a project name, destination domain, URL, category, card copy, and visual theme. Add or update records there to change the directory. The filter counts update automatically.

The project cover artwork is made from CSS and typography; it is an editorial visual, not a screenshot of the destination website.

## Contact CTA

The project enquiry button currently uses `easypzbuisness@gmail.com`. Update the mailto address in `index.html` if WebTea adopts a dedicated studio inbox.
